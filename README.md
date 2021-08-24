# FUS

- [FUS](#fus---fundamentals-updates-and-stuff)
  - [Installation](#installation)
    - [First time installation, PC preparation](#first-time-installation-pc-preparation)
    - [Download and installation of the FUS modlist](#download-and-installation-of-the-fus-modlist)
  - [Post-installation](#post-installation)
    - [Activate the essential files](#activate-the-essential-files)
    - [Choose ENB or Reshade](#choose-enb-or-reshade)
    - [Select the profile of your choice](#select-the-profile-of-your-choice)
- [How to start up FUS](#how-to-start-up-fus)
- [The full modlist](#the-full-modlist)
- [FAQ and troubleshooting](#faq-and-troubleshooting)
- [Updating FUS](#updating-fus)
  - [Removing FUS](#removing-fus)
- [Changelog](#changelog)

## FUS - Fundamentals, Updates, and Stuff

FUS is a fundamental modlist for Skyrim VR that offers 3 profiles.

FUS (Basic): Including the barebones for a good VR experience.\
FUS RO (Basic + Visuals): Also includes some visual improvements.\
FUS RO DAH (Basic + Visuals + Gameplay): Also includes several mods that alter gameplay, both VR-specific and general ones.

This modlist is meant to be used by people who either want to start their own totally personal modlist but dont want to bother with the basic stuff (in that case use the FUS - green basics), or by people who want to have an as fast as possible mod list installation to get Skyrim VR running with a generally vanilla-lore-friendly overhaul and never come back (in that case use the FUS RO - blue visuals - or the FUS RO DAH - yellow gameplay - profiles in addition if you like fun). Taken together in this list, only the FUS profile is meant to be essential. The rest is what we find to be a nice minimalistic setup that users can either just use or butcher at their taste ;)

The entire modlist can be found at the bottom of this page. Mod authors appreciate an endorsement! :)

You need about 60gb free disk space.

--------

[Join the discord](https://discord.gg/Kv6MdXY3fB) for support, chat, and sharing experiences and screenshots!

--------

## Installation

This may look like a good amount of work but the process is fast and you just need to follow the steps :) Do not despair! Don't run away! If you feel like anything is unclear please [join the discord](https://discord.gg/Kv6MdXY3fB) and let us know! We will do our best to clear things up and add the clarification for the next user.

### First time installation, PC preparation

These steps are only needed if you install this Modlist for the first time. If you update the Modlist, jump straight to [Updating](#updating)!

Follow all steps on [this page](https://github.com/Kvitekvist/FUS/wiki/Prepare-PC-for-modlist) to prepare your PC to install FUS. This includes requirements, cleaning Skyrim, and installing Wabbajack.

### Download and installation of the FUS modlist

The installation process of the FUS list is straightforward and described [here](https://github.com/Kvitekvist/FUS/wiki/Download-and-Installation-of-the-FUS-modlist).

If you run into any issues see the [wabbajack troubleshooting page](https://github.com/Kvitekvist/FUS/wiki/Wabbajack-Troubleshooting). If the installation is successful, proceed to [Post-Installation](#post-installation).

## Post-installation

You need to open MO2 ("ModOrganizer.exe") from within the FUS folder. If you had a different MO2 installed previously, do not use that one.

DO NOT RUN LOOT! Everytime you run LOOT a kitten dies and we cry in the corner. The load order is exactly as it should be, do not change it. In case you changed it you can recover it with the ["restore" button](https://github.com/Kvitekvist/FUS/blob/main/images/restore%20loadorder.png).

### Activate the essential files

[This step](https://github.com/Kvitekvist/FUS/wiki/Activate-the-Essential-Files) will add the required files for SKSE, Engine Fixes, DLL loader and other essential files that cannot be handled by MO2. It is a required step, DO NOT SKIP THIS!

### Choose ENB or Reshade

First of all, we highly recommend not using any supersampling, neither in Steam/Oculus, nor ingame. Set everything to 100%. Supersampling is a very inefficient way of anti-aliasing and given the hunger for performance in Skyrim VR you most likely will drop into reprojection when you try using it.

[Here](https://github.com/Kvitekvist/FUS/wiki/Choose-ENB-or-Reshade) we explain how you can choose and switch different pre-installed ENBs and Reshade presets easily. No need to install manually! :)

All ENB or Reshade options we provide include a sharpener which is meant to be used in combination with temporal ani-aliasing (TAA) switched on ingame.

### Select the profile of your choice

FUS is a fundamental modlist for Skyrim VR that offers 3 profiles.

+ FUS (Basic): Including the barebones for a good VR experience.
+ FUS RO (Basic + Visuals): Also includes some appearance improvements.
+ FUS RO DAH (Basic + Visuals + Gameplay): Also includes several mods that alter gameplay, both VR-specific and general ones.

Of course you can also select your own choices from the profiles.
The green parts are really the mods that we think no Skyrim VR mod list should be without.
The blue parts contain a selection of audio/visual/architecture/armory/NPC overhauls that we think is fine to work as standalone. This is personal preference and just a selection we made and like.
The yellow parts are our choice of gameplay improvements/changes. These deviate from vanilla and mostly make the game more interesting and challenging, or just overall improve the feeling. Obviously, these are personal preference, too.
The optional LOD files contain DynDoLOD generated files that enhance the visuals in the distance. These cost performance but make a big difference!
The red late load parts contain patches that we created for this mod list. Use them if you use the respective mods above. 

Mod authors appreciate an endorsement! :)

Surprise: **DO NOT TOUCH** the files that are marked as such. 

# How to start up FUS

Head over to the installation folder and locate the executable named "ModOrganizer.exe" and launch it. Once its launched there will be a dropdown box on the top right and a big "Run" button next to it. Ensure it is set to "Play SkyrimVR" by selecting it in the dropdown box and then hitting the "Run" button. 

**This has to be done each time you want to play Skyrim VR!** 

You cannot start Skyrim VR from Steam, always use MO2. Best make a shortcut and put it on the desktop. There's a button for this right next to the "Run" button :)

**IMPORTANT:** Skyrim VR is very particular about controllers. Make absoutely sure Steam VR and your controllers are switched on *before* starting the game!

![image](https://github.com/Kvitekvist/FUS/blob/main/images/play%20fus.png?raw=true)

# The full modlist

The complete mod list and our comments on them can be found [here](https://github.com/Kvitekvist/FUS/wiki/The-full-modlist).

# FAQ and troubleshooting

- The game is really blurry. -> Should not be blurry if you enabled a sharpener (ENB/Reshade). Make sure dynamic resolution is off.
- Why is my performance so bad? -> Don't use supersampling. Just set render resolution to 100%, have TAA on ingame, dynamic resolution off, no supersampling ingame, and use a post-process sharpener like VR Vision Reshade.
- You use 3D trees plus Myrkvior? -> We are only using the plants from 3D trees.
- Doesn't Cathedral Landscape already include Blended Road? -> There are some meshes missing from Cathedral Landscape that are included in blended roads.
- Is XLodGen essential? I always only did TexGen then Dyndolod. -> Not essential, but you generate terrain LOD with xLODGen, tree and object LOD with DynDOLOD.
- I see you are using USSEP from the Nexus, but I do not see the Skyrim VR - USSEP Compatibility Patch. -> USSEP thing is baked into cleaned master mod.
- Did you address the Realm of Lorkham Unbound quest issue? I did not see Realm of Lorkhan - Unbound Quest Fix. -> Yes, unbound is merged into the list.
- My game is broken, interiors are too dark! -> You probably ran LOOT, didn't you? Press the ["restore" button](https://github.com/Kvitekvist/FUS/blob/main/images/restore%20loadorder.png) to restore the intended load order for your profile.
- Some tools like LOOT and DynDoLOD are missing! -> We have decided not to include most of the tools we use when developing the modlist. This is not because we don't want to share how we do things, in fact you can read all the settings in this readme. We have excluded the tools because if a tool is updated the list may go down which is a typical DynDoLOD issue. LOOT is removed because running it will break the modlist. 
- I added / changed some mods. What are your settings for DynDoLOD and Synthesis? -> You can find them [in the wiki](https://github.com/Kvitekvist/FUS/wiki/LOD-Settings).

# Updating FUS

If this Modlist receives an update please check the changelog before doing anything. Always backup your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.

Again, **do check the description/changelog of the update** to get the necessary info.


## Removing FUS

You can just remove the MO2 folder and be done with it. SKSE and ENB files will still be in your game folder. The easiest way to remove these, unless you know what files that is, is to do a clean install of Skyrim VR again. See [Clean Skyrim](#clean-skyrim)

# Changelog

You can find all changes of each version in the [changelog](https://github.com/Kvitekvist/FUS/wiki/Changelog). The latest release can always be found on the [release page](https://github.com/Kvitekvist/FUS/releases)!
