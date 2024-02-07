# Downloading Cura
I use Cura to slice all the files for this printer and setting up the profiles and materials for this printer is very easy.
<p align="center">
  <img src="https://img.utdstc.com/icon/97a/a5e/97aa5e531fee9e0b18d7028609d091062db6e392c49e45859ba0aeeeb118eae4:200" />
</p>
<br>
<br>
Lets start by identifying your type of Macbook. Go to the top left and click the Apple logo, then select "About This Mac"
<br><br>
<img width="440" alt="Screen Shot 2024-02-06 at 10 29 42 AM" src="https://github.com/EAMalyshev/BVHS-Cura/assets/155656835/d6adf58b-6fa4-4d3d-8ea8-3f5e3e19a522">
<br><br>
If next to "Chip" it says Apple M1, we will download "MacOS-ARM64.dmg", if it says anything else like "Intel", we will download "MacOS-x64.dmg"
<br><br>
<img width="574" alt="Screen Shot 2024-02-06 at 10 30 29 AM" src="https://github.com/EAMalyshev/BVHS-Cura/assets/155656835/f021924c-043f-44cb-a809-0b09e9231902">
<br><br>
Download the latest version of <a href="https://ultimaker.com/software/ultimaker-cura/">Ultimaker Cura</a> to your computers desktop based on your macbook.
<br><br>
<img width="471" alt="Screen Shot 2024-02-06 at 10 48 56 AM" src="https://github.com/EAMalyshev/BVHS-Cura/assets/155656835/2c2ac407-c753-408e-8ed4-a96da9bfc8ab">
<br><br>
Double Click the .dmg file and agree to the Terms of Service.
<br><br>
<img width="639" alt="Screen Shot 2024-02-06 at 10 49 54 AM" src="https://github.com/EAMalyshev/BVHS-Cura/assets/155656835/0d98411f-e9f5-4b23-807b-d85ce1590443">
<br><br>
This will open the following window.
<br><br>
<img width="681" alt="Screen Shot 2024-02-06 at 10 51 21 AM" src="https://github.com/EAMalyshev/BVHS-Cura/assets/155656835/1bbed668-4ef9-424e-8578-dd056b1f1333">
<br><br>
Rather than dragging this into your applications folder, drag and drop this onto your desktop.
<br><br>
<img width="953" alt="Screen Shot 2024-02-06 at 10 53 22 AM" src="https://github.com/EAMalyshev/BVHS-Cura/assets/155656835/7cfb6f29-c0d0-4d6a-857f-a12764ece7f7">
<br><br>
Cura will now stay on your desktop and you can access it anytime!
<br><br>
This step is important. RIGHT-CLICK the application, and press "Open", then press "Open" again. This will open Cura. You only have to do this once; this is because Apple doesnt "Approve" a lot of apps outside of the App Store, and as a result, some apps require you to manually confirm that this app is safe the first time you open it.
<br><br><br><br>

# Cura Setup
Welcome to Cura!
<br><br>
<img width="1440" alt="Screen Shot 2024-02-06 at 11 15 34 AM" src="https://github.com/EAMalyshev/BVHS-Cura/assets/155656835/293182a3-c470-4ce1-b9cf-d03794aecb3c">
<br><br>
Lets start configuring everything. Press "Get Started", agree to the Terms of Service by pressing "Agree", skip the short info slide by pressing "Next", and skip making a Ultimaker account by pressing "Skip". This will bring you to the printer selection screen. Press "Non Ultimaker printer".
<br><br>
<img width="602" alt="Screen Shot 2024-02-06 at 11 20 58 AM" src="https://github.com/EAMalyshev/BVHS-Cura/assets/155656835/bbf638be-cd29-403c-a197-62ee2d38a2d9">
<br><br>
On the following menu, press the dropdown menu labeled "Add a non-Networked printer".
<img width="602" alt="Screen Shot 2024-02-06 at 11 35 01 AM" src="https://github.com/EAMalyshev/BVHS-Cura/assets/155656835/56a47ae1-44e0-4bb7-84f8-c2c21426a3b6">
<br><br>
Press "Next" (We did select a random printer, but we will delete this later. This is only temporary), then skip the info screen by pressing "Skip", then press "Finish".
<br><br><br><br>

# Configuration and Importing Profiles
Lets start by installing the Moonraker plugin, which allows us to send files wirelessly. Press "MarketPlace" on the top right.
<br><br>
<img width="1440" alt="Screen Shot 2024-02-06 at 11 43 23 AM" src="https://github.com/EAMalyshev/BVHS-Cura/assets/155656835/5f64d522-6d60-4437-b45a-74fce5a60350">
<br><br>
Then search for "moonraker" in the search bar. This will pull up the moonraker plugin. Press install, agree the plugin license by pressing "Accept", then close out the window.
<br><br>
<img width="779" alt="Screen Shot 2024-02-06 at 11 49 40 AM" src="https://github.com/EAMalyshev/BVHS-Cura/assets/155656835/2e6b08f6-9c15-4d63-aeb0-5b2f16d6ae14">
<br><br>
This part is optional, but you can configure your preferences, theme, etc. by going to the "Preferenecs" button on the top left, then pressing "Configure Cura...".
<br><br>
<img width="1440" alt="Screen Shot 2024-02-06 at 11 54 51 AM" src="https://github.com/EAMalyshev/BVHS-Cura/assets/155656835/b6373f50-c927-4a4c-9bee-be0742e703e7">
<br><br>
This will pull up the following menu. You dont have to touch any of them, but I personally choose to change Currency to "$", Theme to "Ultimaker Dark", Turn on "Slice automatically", Turn off "Scale extremely small models", and Turn off "Send (anonymous) print information". After you finish, close out the window.
<br><br>
<img width="781" alt="Screen Shot 2024-02-06 at 11 59 41 AM" src="https://github.com/EAMalyshev/BVHS-Cura/assets/155656835/070b4667-9d8d-4466-b872-72d5e166746c">
<br><br>
Before we close out cura, lets open the configuration folder by pressing "Help", then "Show Configuration Folder". This will open a folder in your finder. We will access this later.
<br><br>
<img width="1440" alt="Screen Shot 2024-02-06 at 12 10 35 PM" src="https://github.com/EAMalyshev/BVHS-Cura/assets/155656835/63b9ad63-d9d3-4fdb-9e8d-fed70864358c">
<br><br>
After installing the Moonraker plugin and changing your preferences, close out of Cura. This will apply all the changes youve made. Now we can pull up the folder we opened earlier.
<br><br>
<img width="916" alt="Screen Shot 2024-02-06 at 12 13 07 PM" src="https://github.com/EAMalyshev/BVHS-Cura/assets/155656835/8a56c457-eb6f-4cbc-b3dd-2cff18125889">
<br><br>
This folder is used to manage everything in Cura. We are going to add in a definition for our BVHS printers.
<br><br>
Download the "<a href="https://github.com/EAMalyshev/BVHS-Cura/blob/main/Cura/creality_ender3pro.def.json">creality_ender3pro.def.json</a>" file from this github.
<br><br>
<img width="1440" alt="Screen Shot 2024-02-06 at 12 35 59 PM" src="https://github.com/EAMalyshev/BVHS-Cura/assets/155656835/974d5919-815d-41bf-bdd4-7a26d62326ac">
<br><br>
Place the file you just downloaded into the "definitions" folder.
<br><br>
<img width="487" alt="Screen Shot 2024-02-06 at 12 37 47 PM" src="https://github.com/EAMalyshev/BVHS-Cura/assets/155656835/b1a0857c-970d-456d-978d-95034a9adbe7">
<br><br>
After you place the file in the definitions folder, you can close this folder out and once again load Cura
<br><br>
<img width="505" alt="Screen Shot 2024-02-06 at 12 50 07 PM" src="https://github.com/EAMalyshev/BVHS-Cura/assets/155656835/64470c1a-7bfb-4811-89d6-422df24cb9da">
<br><br>

Lets add the new printer by pressing "Settings", "Printer", selecting "Add Printer...". This will bring us to a familiar screen. Press "Non Ultimaker printer".
<br><br>
<img width="776" alt="Screen Shot 2024-02-06 at 12 54 17 PM" src="https://github.com/EAMalyshev/BVHS-Cura/assets/155656835/57d15595-6157-47bb-ae9d-db75795b209f">
<br><br>
Then once again, select "Add a non-networked printer". We will this time scroll all the way down to the bottom and select "BVH Printers" and "Ender 3 Pro".
<br><br>
<img width="774" alt="Screen Shot 2024-02-06 at 12 56 53 PM" src="https://github.com/EAMalyshev/BVHS-Cura/assets/155656835/d8089ee5-ca40-47c9-8c83-5e5174878b0a">
<br><br>
Then add "Add", then skip the next menu by pressing "Next", which will bring back you back to a screen with all the printers. Now, with the printer you temporarily added at the start, press the menu icon, then "Remove".
<br><br>
<img width="774" alt="Screen Shot 2024-02-06 at 2 56 54 PM" src="https://github.com/EAMalyshev/BVHS-Cura/assets/155656835/8bc74375-0055-43fe-8a5b-f52d26a1b4c4">
<br><br>
Your printer menu should only have the Ender 3 Pro. Select Ender 3 Pro, and press "Connect Moonraker"
<br><br>
<img width="781" alt="Screen Shot 2024-02-06 at 3 07 53 PM" src="https://github.com/EAMalyshev/BVHS-Cura/assets/155656835/271166ff-0f18-4b6d-b4ee-7a8a6061eb8a">
<br><br>
This will pull up another Menu. In the "Address(URL)", type in "http://192.168.4.1" (This is the printers IP).
<br><br>
<img width="775" alt="Screen Shot 2024-02-06 at 3 13 19 PM" src="https://github.com/EAMalyshev/BVHS-Cura/assets/155656835/0289c6d3-4144-4655-8bf8-4d96a6577b62">
<br><br>
Selecet the "Upload" tab at the top of the menu, and in tab, select "UFP with Thumbnail". You can press "Create" which will bring you back to the previous screen.
<br><br>
<img width="777" alt="Screen Shot 2024-02-06 at 3 14 43 PM" src="https://github.com/EAMalyshev/BVHS-Cura/assets/155656835/250e5047-20ca-43aa-b4c1-e4c841f5874a">
<br><br>
Now, lets import the material and profile. Download <a href="https://github.com/EAMalyshev/BVHS-Cura/blob/main/Cura/BVHS-Speed.xml.fdm_material">BVHS-Speed.xml.fdm_material</a>. Go to the "Materials" tab on the side.
<br><br>
<img width="778" alt="Screen Shot 2024-02-06 at 3 34 23 PM" src="https://github.com/EAMalyshev/BVHS-Cura/assets/155656835/8b68496c-1217-4018-8c3e-04ab05d83edf">
Press "Import" and select the file you just downloaded. Now if you scroll to the bottom, you should find a section called "⋆ School E3P" with "Speed PLA" Under it. If everything is correct. you can close out of this window.
<br><br>
Now when you want to print with PLA, select the material dropdown menu and under the filament go down to Speed PLA
<br><br>
<img width="1440" alt="Screen Shot 2024-02-07 at 7 21 06 AM" src="https://github.com/EAMalyshev/BVHS-Cura/assets/155656835/ff618486-f8ce-4f67-8a38-6cc207a634f8">
<br><br>
Lets lastly setup the profile. Download <a href="https://github.com/EAMalyshev/BVHS-Cura/blob/main/Cura/BVHS-Speed.curaprofile">BVHS-Speed.curaprofile</a>. Then back in Cura, go once again to "Preferences", then "Configure Cura..."
<br><br>
<img width="1440" alt="Screen Shot 2024-02-07 at 7 23 42 AM" src="https://github.com/EAMalyshev/BVHS-Cura/assets/155656835/290e243c-12a0-4da3-b34f-baba04154be8">
<br><br>
This time, instead of going to materials, we are going to go to "Profiles"
<br><br>
<img width="770" alt="Screen Shot 2024-02-07 at 7 24 58 AM" src="https://github.com/EAMalyshev/BVHS-Cura/assets/155656835/659d6428-e098-4e2e-9b6a-49c6d918fa5f">
<br><br>
Press "Import", and select the file you just downloaded. It should now show up under "Custom Profiles" as "Speed PLA". You can now close out of this window.
