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

FUS is a fundamental modlist for Skyrim VR that offers 3 profiles.

FUS (Basic): Including the barebones for a good VR experience.\
FUS RO (Basic + Visuals): Also includes some visual improvements.\
FUS RO DAH (Basic + Visuals + Gameplay): Also includes several mods that alter gameplay, both VR-specific and general ones.

This modlist is meant to be used by people who either want to start their own totally personal modlist but dont want to bother with the basic stuff (in that case use the FUS - green basics), or by people who want to have an as fast as possible mod list installation to get Skyrim VR running with a generally vanilla-lore-friendly overhaul and never come back (in that case use the FUS RO - blue visuals - or the FUS RO DAH - yellow gameplay - profiles in addition if you like fun). Taken together in this list, only the FUS profile is meant to be essential. The rest is what we find to be a nice minimalistic setup that users can either just use or butcher at their taste ;)

The entire modlist can be found at the bottom of this page.

This Readme is work in progress at the moment! If you have comments, send a message to [Cangar](https://www.reddit.com/user/Cangar).

## Installation

This may look like a good amount of work but the process is fast and you just need to follow the steps :)\
Do not despair! Don't run away! If you feel like anything is unclear please drop a message to [Cangar](https://www.reddit.com/user/Cangar). I will do my best to clear things up and add the clarification for the next user.

### First time installation, PC preparation

These steps are only needed if you install this Modlist for the first time. If you update the Modlist, jump straight to [Updating](#updating)!

Follow all steps on [this page](https://github.com/Kvitekvist/FUS/wiki/Prepare-PC-for-modlist) to prepare your PC to install FUS. This includes requirements, cleaning Skyrim, and installing Wabbajack.

### Download and Installing the FUS modlist

The installation process of the FUS list is straightforward and described [here](https://github.com/Kvitekvist/FUS/wiki/Download-and-Installing-the-FUS-modlist).

If you run into any issues see the the [wabbajack troubleshooting page](https://github.com/Kvitekvist/FUS/wiki/Problems-with-Wabbajack). If the installation is successful, proceed to [Post-Installation](#post-installation).

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


![image](https://github.com/Kvitekvist/FUS/blob/main/images/all%20mods3.png?raw=true)

# FAQ

- The game is really blurry. -> Should not be blurry if you enabled a sharpener (ENB/Reshade). Make sure dynamic resolution is off.
- Why is my performance so bad? -> Don't use supersampling. Just set render resolution to 100%, have TAA on ingame, dynamic resolution off, no supersampling ingame, and use a post-process sharpener like VR Vision Reshade.
- You use 3D trees plus Mirkvior? -> We are only using the plants from 3D trees.
- Doesn't Cathedral Landscape already include Blended Road? -> There are some meshes missing from Cathedral Landscape that are included in blended roads.
- Is XLodGen essential? I always only did TexGen then Dyndolod. -> Not essential, but you generate terrain LOD with xLODGen, tree and object LOD with DynDOLOD.
- I see you are using USSEP from the Nexus, but I do not see the Skyrim VR - USSEP Compatibility Patch. -> USSEP thing is baked into cleaned master mod.
- Did you address the Realm of Lorkham Unbound quest issue? I did not see Realm of Lorkhan - Unbound Quest Fix. -> Yes, unbound is merged into the list.
- My game is broken, interiors are too dark! -> You probably ran LOOT, didn't you? Press the "restore" button to restore the intended load order for your profile.
- Some tools like LOOT and DynDoLOD are missing! -> We have decided not to include most of the tools we use when developing the modlist. This is not because we don't want to share how we do things, in fact you can read all the settings in this readme. We have excluded the tools because if a tool is updated the list may go down which is a typical DynDoLOD issue. LOOT is removed because running it will break the modlist. 
- I added / changed some mods. What are your settings for DynDoLOD and Synthesis? -> You can find them in the "images" folder.

# Changelog

## Version 1.0.3

HOTFIX!

### Fixes
+ Replaced Strange runes for LE with the correct VR version

## Version 1.0.2

New save required!

### Mods added

+ Populated Forts Towers Places Remastered Edition
+ Populated Dungeons Caves Ruins Legendary
+ Bethesda logo remover (fixes the overlaying logo when in the starting game menu)

### Fixes

+ Unintended “Skyrim Revamped Loot and Encounter Zones” plugin from OMEGA AIO was removed (made the game way too difficult)

### Mods removed

+ OMEGA AIO


### Other

+ Changed player name to “Adventurer”
+ Moved SOSCBO to melee gameplay (yellow)
+ Updated dummy plugins
+ Make new backup of mod order
+ Make new backup of plugin order
+ Added version header into MO2

New version here: https://github.com/Kvitekvist/FUS/releases/tag/1.0.2

## Version 1.0.1

### Mods added

+ True Storms
+ DummyPlugins (one for each profile, meaning if mods are disabled these plugins will stay and preserve the loadorder)
+ Strange Runes as optional mod
+ Obsidian Mountain Fog
+ FUS_TrueStorm_Patch (also uploaded to Nexus)


### Fixes

+ Profiles are renamed to "FUS", "FUS RO", and "FUS RO DAH"
+ Basic and Basic + Visual profiles are now included. I messed up so WJ only included the main profile FUS RO DAH.
+ Fixed load order of several mods (Synthesis and a few others)
+ Mod Category 3 (orange ones) are all marked as optional mods. Add the ones you want, you do not need all. But see if you also need any of the patches.
+ Added a "restore" backup of mod order and load order, in case you mess it up. Now you can click on the restore button in MO2, to restore the list back to default sorting.
+ Iron starting gear is removed from character creation.

### Mods removed

- Spellforge - Vokrii patch (there was no patch for this)

### Important note about Load Order
You can activate or deactivate any mod marked as optional. Load order will be preserved. DO NOT RUN LOOT. If you add mods yourself, sort them manually. Best general tip is to have the plugins sorted in the same order as the mods. There are exceptions, so this is a general advice.

### Tools are missing?
We have decided not to include most of the tools we use when developing the modlist. This is not because we don't want to share how we do things. In fact we added all this in the readme above. We have excluded the tools because if a tool hosted on GIT is updated the list goes down which is a typical Dyndolod issue. LOOT is removed because running it will break the modlist. 

We are also continuously working on improving the readme!

New version here:https://github.com/Kvitekvist/FUS/releases/tag/1.0.1
