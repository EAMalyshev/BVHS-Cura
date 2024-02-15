# Klipper Tuning and RPI Documentation!
Welcome to the documentation of the prtinters. This isnt going to as extensive and user friendly as the Cura setup.
<br><br><br><br>

# What Will be Covered?
Most of the things there is to known can be read in the <a href="https://www.klipper3d.org/Overview.html">Klipper Documentation</a>. The only things I will cover in this document is setup of the raspberry pi, setup of the access point, setting up KIAUH, installing klipper, setting up connecting over UART and usb, my basic tuning on this printer, and the custom .def.json for this printer on Cura. This was a very large project for me, but I really enjoyed it and hope others can benifit or learn from it.
<br><br><br><br>

# The Raspberry Pi
The entire klipper setup runs on a Raspberry Pi 3 B+. It has 1GBs of ram which is enough for 2 basic cartesian printers running at low speeds and possibly a webcam, which I didnt implement incase it violated privacy in some way.
<br><br><br><br>

# The Access Point
This was one of the hardest parts of the project. When I first tried to set it up, I was learning how to configure this on Debian 11. Raspberry pi OS recently switched to Debian 12 which has systemd-networkd alongside NetworkManager; this created ip address conflicts between systemd-networkd and NetworkManager. After I banged my head against a very solid brick wall which was this problem for a week, I figured it out and switched to Debian 11. For setting up the access point, you need DNSMasq and hostAPD. DNSMasq is responsible for both DHCP which assigns ip addresses on a network, and DNS which is responsible for translating domain names into IP addresses. hostAPD is used to create a wireless hotspot. After installing DNSMasq and hostAPD, set hostAPD to start on boot. You will also need to install netfilter-persistant and iptables-persistant which are used managing firewall rules defined by iptables. You then need to modify /etc/dhcpcd.conf and set 192.168.4.1 as the raspberry pis own static ip. Then enable ipv4 forwarding in /etc/sysctl.d/routed-ap.conf. Make sure to also edit /etc/dnsmasq.conf and give it a pool of ip addresses that DHCP can assign to devices. Lastly, and most importantly, edit /etc/hostapd/hostapd.conf to broadcast the proper access point for you to connect to; for our specific case,
