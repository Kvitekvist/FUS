# FUS

- [FUS](#fus)
  - [Installation](#installation)
    - [First time installation](#first-time-installation)
      - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
      - [Steam Config](#steam-config)
        - [Disable the Steam Overlay](#disable-the-steam-overlay)
      - [Set the Game language to English](#set-the-game-language-to-english)
      - [Clean Skyrim](#clean-skyrim)
      - [Reinstall Skyrim](#reinstalling-skyrim-vr)
      - [Creation Club Updating Protection](#creation-club-updating-protection)
      - [Start Skyrim VR](#start-skyrim-vr)
      - [Using Wabbajack](#using-wabbajack)
        - [Preparations](#preparations)
        - [Downloading and Installing](#downloading-and-installing)
        - [FAQ - Problems with Wabbajack](#faq---problems-with-wabbajack)
  - [Post-Installation](#post-installation)
   - [Activate the Essential Files](#activate-the-essential-files)
   - [Choose ENB or Reshade](#choose-enb-or-reshade)
  - [Updating](#updating)
  - [Removing the Modlist](#removing-the-modlist)
- [How to start up FUS](#how-to-start-up-fus)
- [The full modlist](#the-full-modlist)
- [FAQ](#faq)
- [Changelog](#changelog)

## FUS - Fundamentals, Updates, and Stuff

FUS is a fundamental modlist for Skyrim VR that offers 3 profiles.\

FUS (Basic): Including the barebones for a good VR experience.\
FUS RO (Basic + Visuals): Also includes some visual improvements.\
FUS RO DAH (Basic + Visuals + Gameplay): Also includes several mods that alter gameplay, both VR-specific and general ones.

This modlist is meant to be used by people who either want to start their own totally personal modlist but dont want to bother with the basic stuff (in that case use the basic profile), or by people who want to have an as fast as possible mod list installation to get Skyrim VR running with a generally vanilla-lore-friendly overhaul and never come back (in that case use the visuals, or the gameplay in addition if you like fun).

The entire modlist can be found at the bottom of this page.

This Readme is work in progress at the moment! If you have comments, send a message to u/Cangar on reddit.

## Installation

This may look like a good amount of work but the process is fast and you just need to follow the steps :)\
Do not despair! Don't run away! If you feel like anything is unclear please drop a message to u/Cangar on reddit. I will do my best to clear things up and add the clarification for the next user.

### First time installation

These steps are only needed if you install this Modlist for the first time. If you update the Modlist, jump straight to [Updating](#updating)!

#### Installing Microsoft Visual C++ Redistributable Package

I doubt you need to do this since you likely already have this installed. The package is required for MO2 and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

#### Steam Config

##### Disable the Steam Overlay

The Steam Overlay can cause issues with ENB and is recommended to be turned off.

Open the Properties window (right click the game in your Library->Properties), navigate to the _General_ tab and un-tick the _Enable the Steam Overlay while in-game_ checkbox.

#### Set the Game language to English

Just do it. This entire Modlist is in English and 99% of all mods you will find are also in English. We highly recommend playing the game in English and **will not give support to people with a non-English game**. Wabbajack does not support SkyrimVR files in other languages either. Wabbajack will fail file validation for other languages.

Open the Steam Properties window, navigate to the _Language_ tab and select _English_ from the dropdown menu.

#### Clean Skyrim

Delete the following directories:
1. Open Stem Steam
2. Right click on “Skyrim VR”
3. Choose: Properties >>  Local Files >>  Browse

![image](https://i.ibb.co/V33zFWt/steam-folder.png)

4. Delete all content in the folder. Do not reinstall yet.
5. Open Windows Search and copy/paste %LOCALAPPDATA%
6. Delete the Skyrim VR folder
7. Navigate to Users\YOURNAME\Documents\My Games\
8. Delete the SkyrimVR folder

#### Reinstalling Skyrim VR

Open Steam and ensure that Skyrimis uninstalled through on it.
Reinstall Skyrim VR from Steam.
Run the Skyrim VR launcher through Steam and let it detect your settings, then close the launcher. This is only necessary once.

#### Creation Club Updating Protection

Every time the Creation Club releases new content SKSEVR breaks. A fixed version of SKSEVR usually releases fast, but to ensure your game isn’t broken for a few days follow these steps:
Open your Steam Library
Find The Elder Scrolls V: Skyrim VR and open the properties
Click Properties
Click the Updates tab
Under the Automatic Updates section, select “Only update the game when I launch it”

#### Start Skyrim VR

After you have done everything above and got a clean Skyrim VR installation ready, start the Launcher and and let it do the initial graphics check. Do not worry about this part as the installation will replace this graphics settings.
Start the game and exit once you're in the main menu. This will make sure that some of the tools the Mod Organizer that comes with FUS will find the Skyrim VR folder.

### Using Wabbajack

#### Preparations

Grab the latest release of Wabbajack from [here](https://www.wabbajack.org/#/) and place the `Wabbajack.exe` file in a _working folder_. This folder **must not** be in a _common folders_ like your Desktop, Downloads or Program Files folder. It's best to create a Wabbajack folder near the root level of your drive like `C:/Wabbajack`.

#### Downloading and Installing

Now, create a new folder on the root of your gaming drive, the drive where you want everything to be installed. Name it "FUS".

The download and installation process can take a very long time depending on your system specs. Wabbajack will calculate the amount of threads it will use at the start of the installation. To have the highest amount of threads and thus the fastest speed, it is advised to have the working folder on an SSD. We highly recommend getting Nexus premium membership to automate the download process.


1. Download the latest FUS release from here:
https://github.com/Kvitekvist/FUS/releases

2. Open Wabbajack:

![image](https://i.ibb.co/JK3rdZc/Browse-modlist.png)

3. Run the downloaded FUS.wabbajack install file and set the installation folder to the folder you just created. The downloads path should automatically fill in the installation path.

4. Click the Go/Begin button
5. Wait for Wabbajack to finish
6. If you run into any issues see the next section. If the installation is successful, proceed to [Post-Installation](#post-installation).

#### FAQ - Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off so you lose no progress.

**"Could not download x"**:

If a mod updated and the old files got deleted, it is impossible to download them. In this case just wait till I update the Modlist.

**"x is not a whitelisted download"**:

This can happen when we update the modlist. Check if a new update is available and wait if there is none. Sorry for the inconvenience.

**"Wabbajack could not find my game folder"**:

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, but get this error, go back to the [beginning](#first-time-installation) and make sure everything is set up correctly.

**"Windows is reporting that a virus has been detected"**:

Windows 10 has started to auto quarantine the usvfs_proxy_x86.exe file from the latest version of Mod Organizer 2 saying a threat was detected . This is a known false postive confirmed by the MO2 Devs. You can fix this by adding an exemption for MO2 Folder to your Antivirus. Example for windows defender can be found [here](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

## Post-Installation

### Activate the Essential Files

DO NOT RUN LOOT! Everytime you run LOOT a kitten dies and we cry in the corner. The load order is exactly as it should be, do not change it.

First, run the program named Essentials Files from Mod Organizer 2.
This step will add the required files for SKSE, Engine Fixes, DLL loader and other essential files that cannot be handled by MO2.

![image](https://i.ibb.co/KrvCB09/essentials1.jpg)

Then Click "OK" if you get a message saying something about "Failed to check for update". This is ok.

![image](https://i.ibb.co/P5mpMfH/enb2.jpg)

Then navigate to the Presets menu by pressing the symbol in the top left (the three lines). The menu should look like this:

![image](https://i.ibb.co/YkFSZJ1/enb3.jpg)

Then you will see this menu:

![image](https://github.com/Kvitekvist/FUS/blob/main/images/essential%20files.png?raw=true)

1. You must activate the the "00 Essential Files" option. All others are optional.
2. "00 3D Audio" ads 3D audio \ surround to SkyrimVR. Really good, effectively essential, but you might get a bit more performance without.
3. SteamVR - This is on by default, necessary if you run the game via SteamVR.
4. opencompoisite - This can replace SteamVR and will give Oculus users a strong performance boost.
5. openvr_fsr - AMD sharpener, not compatible with opencomposite, mixed reviews. Test at your own risk.

### Choose ENB or Reshade
From MO2, run the ENB \ Reshade program:

![image](https://github.com/Kvitekvist/FUS/blob/main/images/enb.png?raw=true)

Then Click "OK" if you get a message saying something about "Failed to check for update". This is ok.

![image](https://i.ibb.co/P5mpMfH/enb2.jpg)

Then navigate to the Presets menu by pressing the symbol in the top left (the three lines). The menu should look like this:

![image](https://i.ibb.co/YkFSZJ1/enb3.jpg)

Now here, you can choose from a list of different ENB/Reshade profiles. There are 3 difference performance indicators in their names. Low means low performance cost, Medium means medium performance cost and High means high performance cost. 
If any preset was marked as on, then turn them off, then turn on the selection of your choice. By default, The first option is checked. Uncheck this and then check any of the other options that you would like to test.

The best option for low performance impact but high visual gains including a sharp image is the **VRVision** reshade option. 

**IMPORTANT:** If you want to use the Sensorium ENB you need to change the ini file of the AW_Cangar patch and set the tonemapper to 0. Probably also a good idea for the other ENBs although they don't explicitly demand it. Don't forget to switch it back on when choosing a Reshade again.

![image](https://github.com/Kvitekvist/FUS/blob/main/images/enb%20selection.png?raw=true)


## Updating

If this Modlist receives an update please check the changelog before doing anything. Always backup your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.

Again, **do check the description/changelog of the update** to get the necessary info.


### Removing the Modlist

You can just remove the MO2 folder and be done with it. SKSE and ENB files will still be in your game folder. The easiest way to remove these, unless you know what files that is, is to do a clean install of Skyrim VR again. See [Clean Skyrim](#clean-skyrim)

# How to start up FUS

Head over to the installation folder and locate an executable named "ModOrganizer.exe" and launch it. Once its launched there will be a dropdown box on the top right and a big "Run" button next to it. Ensure it is set to "Play SkyrimVR" by selecting it in the dropdown box and then hitting the "Run" button. 

**This has to be done each time you want to play Skyrim VR!** 

You cannot start Skyrim VR from Steam, always use MO2. Best make a shortcut and put it on the desktop. There's a button for this right next to the "Run" button :)

![image](https://github.com/Kvitekvist/FUS/blob/main/images/launch.png?raw=true)

## Ingame Settings

First of all, we highly recommend not using any supersampling, neither in Steam/Oculus, nor ingame. Set everything to 100%. Supersampling is a very inefficient way of anti-aliasing and given the hunger for performance in Skyrim VR you most likely will drop into reprojection when you try using it. 

Then start with the game settings:
- Disable Dynamic Resolution
- Disable Foliage Shadows
- Disable Comfort Mode (black dynamic frame appearing when you move) if you think you don’t need it
- Again, supersampling slider to min (all the way left)
- Untick “Disable LOD” options and set the Tree Lod slider to max
- Distance sliders are set to: Item 20%, Actor 20%, Objects 40 %, Grass 100 % (or lower if you have framerate issues)
- Activate to your liking “Realistic Archery” and "Realistic Swimming"


# The full modlist

**Select the profile of your choice!** 

- The green parts are really the mods that we think no Skyrim VR mod list should be without.
- The blue parts contain a selection of audio/visual/architecture/armory/NPC overhauls that we think is fine to work as standalone. This is personal preference and just a selection we made and like.
- The yellow parts are our choice of gameplay improvements/changes. These deviate from vanilla and mostly make the game more interesting and challenging, or just overall improve the feeling. Obviously, these are personal preference, too.
- The optional LOD files contain DynDoLOD generated files that enhance the visuals in the distance. These cost performance but make a big difference!
- The red late load parts contain patches that we created for this mod list. Use them if you use the respective mods above. We appreciate an endorsement! :)
- Surprise: do **NOT TOUCH** the files that are marked as such. 

So, here's the full list:


![image](https://raw.githubusercontent.com/Kvitekvist/FUS/main/images/all%20mods.png)

# FAQ

- The game is really blurry. -> Should not be blurry if you enabled a sharpener (ENB/Reshade). Make sure dynamic resolution is off.
- Why is my performance so bad? -> Don't use supersampling. Just set render resolution to 100%, have TAA on ingame, dynamic resolution off, no supersampling ingame, and use a post-process sharpener like VR Vision Reshade.
- You use 3D trees plus Mirkvior? -> We are only using the plants from 3D trees.
- Doesn't Cathedral Landscape already include Blended Road? -> There are some meshes missing from Cathedral Landscape that are included in blended roads.
- Is XLodGen essential? I always only did TexGen then Dyndolod. -> Not essential, but you generate terrain LOD with xLODGen, tree and object LOD with DynDOLOD.
- I see you are using USSEP from the Nexus, but I do not see the Skyrim VR - USSEP Compatibility Patch. -> USSEP thing is baked into cleaned master mod.
- Did you address the Realm of Lorkham Unbound quest issue? I did not see Realm of Lorkhan - Unbound Quest Fix. -> Yes, unbound is merged into the list.
- My game is broken, interiors are too dark! -> You probably ran LOOT, didn't you? Well time to start over. DO NOT RUN LOOT!

# Changelog

First release, no changes yet
