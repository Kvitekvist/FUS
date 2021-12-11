# FUS - Fundamentals, Updates, and Stuff

FUS is a fundamental modlist for Skyrim VR made by Kvitekvist and Cangar. It offers 4 profiles:

- FUS (Basic): Including the barebones for a good VR experience.
- FUS RO (Basic + Visuals): Also includes some visual improvements.
- FUS RO DAH (Basic + Visuals + Gameplay): Also includes several mods that alter gameplay, both VR-specific and general ones.
- Cangar: Basically FUS RO DAH with my personal choice of optional mods.

--------

[Join the discord](https://discord.gg/Kv6MdXY3fB) for support, chat, and sharing experiences and screenshots!

--------

Unlike most wabbajack modlist, FUS is very modular. It is meant to be used by people who either want to get Skyrim VR running with a generally vanilla-lore-friendly overhaul and never come back (in that case use the FUS RO - blue visuals - or the FUS RO DAH - yellow gameplay, if you like fun - profiles), or by people who want to start their own totally personal modlist but don't want to bother with the basic stuff (in that case use the FUS - green basics, the actual essentials for Skyrim VR).

So in this list, only the FUS profile is meant to be absolutely essential. The rest is what we personally find to be a nice minimalistic setup that users can either just use or butcher at their taste and level of competence ;)

The list is made to be extremely performant while retaining a maximal level of visual quality, and we provide different setups of quality vs performance within the list. Cangar can play it on a laptop with a mobile 1070 with a Valve Index, but you can also make use of a 3080 in a desktop PC, depending on the setup you choose.

I would like to point out the fourth profile: "Cangar", which is going to be the exact profile I use for my own playthrough. When I play, I will make it a new Youtube video series on my channel and all my save game files will be made available here on Git. This means you can decide to either just watch me play, or you can literally replay parts yourselves with the exact same setup! 

The entire modlist can be found at the bottom of this page. Mod authors appreciate an endorsement! :)

You need about 45gb free disk space.

FUS does not support pirated versions of the game. Do not attempt to install it if you did not buy the game legally, it will not work. Do not come asking for help.

--------

- [FUS](#fus---fundamentals-updates-and-stuff)
- [Installation](#installation)
  - [First time installation, PC preparation](#first-time-installation-pc-preparation)
  - [Download and installation of the FUS modlist](#download-and-installation-of-the-fus-modlist)
  - [Post-installation](#post-installation)
    - [Activate the essential files](#activate-the-essential-files)
    - [Choose ENB or Reshade](#choose-enb-or-reshade)
  - [Select the profile of your choice](#select-the-profile-of-your-choice)
    - [Choose controller options](#choose-controller-options)
    - [Other](#other)
- [How to start up FUS](#how-to-start-up-fus)
  - [First steps in the game](#first-steps-in-the-game)
- [What's in the box?! The modlist](#whats-in-the-box-the-modlist)
- [Performance adjustment](#performance-adjustment)
- [FAQ and troubleshooting](#faq-and-troubleshooting)
- [Updating FUS](#updating-fus)
  - [Removing FUS](#removing-fus)
- [Changelog](#changelog)

--------

[Join the discord](https://discord.gg/Kv6MdXY3fB) for support, chat, and sharing experiences and screenshots!

--------

# Installation

This may look like a good amount of work but the process is fast and you just need to follow the steps :) Do not despair! Don't run away! If you feel like anything is unclear please [join the discord](https://discord.gg/Kv6MdXY3fB) and let us know! We will do our best to clear things up and add the clarification for the next user.

## First time installation, PC preparation

These steps are only needed if you install FUS for the first time. If you update the modlist, jump straight to [Updating](#updating)!

Follow all steps on [this page](https://github.com/Kvitekvist/FUS/wiki/Prepare-PC-for-modlist) to prepare your PC to install FUS. This includes requirements, cleaning Skyrim, and installing Wabbajack.

## Download and installation of the FUS modlist

The installation process of the FUS list is straightforward and described [here](https://github.com/Kvitekvist/FUS/wiki/Download-and-Installation-of-the-FUS-modlist).

If you run into any issues see the [wabbajack troubleshooting page](https://github.com/Kvitekvist/FUS/wiki/Wabbajack-Troubleshooting). If the installation is successful, proceed to [Post-Installation](#post-installation).

## Post-installation

You need to open MO2 `ModOrganizer.exe` from within the FUS folder. If you had a different MO2 installed previously, do not use that one.

DO NOT RUN LOOT! Everytime you run LOOT a kitten dies and we cry in the corner. The load order is exactly as it should be, do not change it. In case you changed it you can recover it with the [`Restore` button](https://github.com/Kvitekvist/FUS/blob/main/images/restore%20loadorder.png). Such a button exists for the mod order as well as the plugins order.

### Activate the essential files

[This step](https://github.com/Kvitekvist/FUS/wiki/Activate-the-Essential-Files) will add the required files for SKSE, Engine Fixes, DLL loader and other essential files that cannot be handled by MO2. It is a required step, DO NOT SKIP THIS!

### Choose ENB or Reshade

First of all, we highly recommend not using any supersampling, neither in Steam/Oculus, nor ingame. Set everything to 100%. Supersampling is a very inefficient way of anti-aliasing and given the hunger for performance in Skyrim VR you most likely will drop into reprojection when you try using it.

[Here](https://github.com/Kvitekvist/FUS/wiki/Choose-ENB-or-Reshade) we explain how you can choose and switch different pre-installed ENBs and Reshade presets easily. No need to install manually! :)

All ENB or Reshade options we provide include a sharpener which is meant to be used in combination with temporal ani-aliasing (TAA) switched on ingame.

## Select the profile of your choice

FUS is a fundamental modlist for Skyrim VR that offers 4 profiles.

+ FUS (Basic): Including the barebones for a good VR experience.
+ FUS RO (Basic + Visuals): Also includes some appearance improvements.
+ FUS RO DAH (Basic + Visuals + Gameplay): Also includes several mods that alter gameplay, both VR-specific and general ones.
+ Cangar: FUS RO DAH with my choice of optionals (almost all). Choose this if you want to follow and replay my Youtube series.

Of course you can also select your own choices from the profiles.
The green parts are really the mods that we think no Skyrim VR mod list should be without.
The blue parts contain a selection of audio/visual/architecture/armory/NPC overhauls that we think is fine to work as standalone. This is personal preference and just a selection we made and like.
The yellow parts are our choice of gameplay improvements/changes. These deviate from vanilla and mostly make the game more interesting and challenging, or just overall improve the feeling. Obviously, these are personal preference, too.
The optional LOD files contain DynDoLOD generated files that enhance the visuals in the distance. These cost performance but make a big difference!
The red late load parts contain patches that we created for this mod list. Use them if you use the respective mods above. 

Mod authors appreciate an endorsement! :)

Surprise: **DO NOT TOUCH** the files that are marked as such. 

### Choose controller options

In MO2 in category `1.7 - Optional VR Gameplay Mods` there is a mod called `VRIK Rift-Index-WMR Controller Bindings`. Enable this if you want to use the VRIK controller bindings (recommended). In that case you need to also enable the bindings in SteamVR controller settings after starting the game! Please see the [VRIK mod page](https://www.nexusmods.com/skyrimspecialedition/mods/23416) for explanations about the controller bindings.

In [this guide](https://docs.google.com/document/d/15OU6kbtt-jNQ8sL8d-URMuNa-r1-kKJbJHt0dHE-VpU) I explain the controller mappings in more detail so you can change to whatever you wish if you want.

### Other

One additional thing you might want to change is `Auto Sneak and Jump`, this mod will make it so your sneaking is automatically determined by your head height. If this mod is enabled, playing seated will mean you sneak all the time, so disable this mod if you want to play seated. Additionally you might want to adjust the sneak height in the ini of the mod (right click > show files in explorer) if you feel like sneak doesn't work how you want it. We disabled the auto jump because we don't like it too much but you can of course also enable it again.

# How to start up FUS

Head over to the installation folder and locate the executable named `ModOrganizer.exe` and launch it. Once its launched there will be a dropdown box on the top right and a big `Run` button next to it. Ensure it is set to `Play FUS (SKSE)` by selecting it in the dropdown box and then hitting the `Run` button. 

**This has to be done each time you want to play Skyrim VR!** 

You cannot start Skyrim VR from Steam, always use MO2. Best make a shortcut and put it on the desktop. There's a button for this right next to the `Run` button :)

**IMPORTANT:** Skyrim VR is very particular about controllers. Make absoutely sure Steam VR and your controllers are switched on *before* starting the game!

![image](https://github.com/Kvitekvist/FUS/blob/main/images/play%20fus.png?raw=true)

## First steps in the game

When starting the game with FUS you will find yourself in the Realm of Lorkhan, not in the standard intro of Skyrim. Realm of Lorkhan replaces the intro and adds some variety to starting a character (see the [RoL mod page](https://www.nexusmods.com/skyrimspecialedition/mods/18223) for details). You teleport into the world using the crystals, but beware, it is one-way! The intro is very bugged in VR. We recommend you just watch the [intro on YouTube](https://youtu.be/vsRA5BG3N8E?t=61), and then start a new character. Or start Skyrim from Steam, play the intro, then once you leave Helgen, quit the game and start a new game with FUS and pretend its the old one. But don't try to run the intro with the modded game. Its just more stable this way.

# What's in the box?! The modlist

We ship all the little bits and pieces that fix things, improve the basic quality of life, and naturally we include all the cool VR specific mods that bring the game to the level of a modern VR game. Most notably that is VRIK giving you a body, HIGGS VR giving you gravity gloves and weapon physics collitions (not with enemy weapons unfortunately), Spell Wheel VR giving you a spell and other stuff selection wheel like Blade and Sorcery, Weapon Throw VR to - well - throw your weapons, and many more! But also other necessities like USSEP, SkyUI VR, True 3D sound, Engine Fixes VR, SkyVRaan (enabling fake water reflections). Of course, we also have a basic selection for overhauls of trees, architecture, weather, lighting, characters, objects, weapons, armors. And lastly, we offer a small selection of gameplay mods that increase the difficulty a bit, make the game more interesting, improve some stuff here and there. 

We also ship all major ENB or Reshade presets that are very easy for you to enable or disable with a click instead of manual copy action.

We do not feature quest additions, nor added regions or dungeons. However, the list is extremely lightweight and compatibility should not be much of a problem, so you can add them yourself if you like.

If you want to read more details, check out our [complete mod list and our comments on the important mods](https://github.com/Kvitekvist/FUS/wiki/The-full-modlist).

# Performance adjustment

In general, FUS default performance should be good. Depending on your system, you might need to adjust it to improve it, or you might have enough headroom to crank up some settings.

We wrote a [detailed guide](https://github.com/Kvitekvist/FUS/wiki/Performance-adjustment) on how to understand and adjust your ingame performance.

# FAQ and troubleshooting

* The game is really blurry. -> Should not be blurry if you enabled a sharpener (ENB/Reshade). Make sure dynamic resolution is off!

* Why is my performance so bad? -> See [above](#performance-adjustment).

* My game is broken, interiors are too dark! -> You probably ran LOOT, didn't you? Press the [`Restore` button](https://github.com/Kvitekvist/FUS/blob/main/images/restore%20loadorder.png) in the plugins section (right) of MO2 to restore the intended load order for your profile.

* You use 3D trees plus Myrkvior? -> We are only using the plants from 3D trees.

* Is XLodGen essential? I always only did TexGen then Dyndolod. -> Not essential, but you generate terrain LOD with xLODGen, tree and object LOD with DynDOLOD.

* I see you are using USSEP from the Nexus, but I do not see the Skyrim VR - USSEP Compatibility Patch. -> USSEP thing is baked into cleaned master mod.

* Did you address the Realm of Lorkham Unbound quest issue? I did not see Realm of Lorkhan - Unbound Quest Fix. -> Yes, unbound is merged into the list.

* I see some patches that are disabled, or I miss a patch entirely that should be there. -> All patches that are in the list, even when disabled, are merged into the conflict resolution patch. Very likely there is everything you need, but if you think a really important patch is entirely missing, tell us. 

* The LOOT tool missing! -> LOOT is removed because running it will break the modlist.

* I added / changed some mods. What are your settings for rerunning DynDoLOD and Synthesis? -> You can find them [in the wiki](https://github.com/Kvitekvist/FUS/wiki/Settings-for-tools-(LODs-and-Synthesis)).


# Updating FUS

If this Modlist receives an update please check the changelog before doing anything. Always backup your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your downloads folder will not be touched!

You can prevent this deletion by manually renaming the mod to include the "[NoDelete] " flag (inlcuding the space!), e.g. if you installed "OBIS", it then needs to be renamed to "[NoDelete] OBIS" and it will not be removed during updating. You will still have to adjust the load order again after updating!

Other than this, updating is like installing. You only have to make sure that you select the same path and tick the `overwrite` button.

Again, **do check the description/changelog of the update** to get the necessary info.


## Removing FUS

You can just remove the MO2 folder and be done with it. SKSE and ENB files will still be in your game folder. The easiest way to remove these, unless you know what files that is, is to remove them with the tool they were installed with (see [activate essential files](https://github.com/Kvitekvist/FUS/wiki/Activate-the-Essential-Files)), or if you want to be absolutely sure, just do a clean install of Skyrim VR again (see [clean Skyrim](https://github.com/Kvitekvist/FUS/wiki/Prepare-PC-for-modlist#clean-skyrim)).

# Changelog

You can find all changes of each version on the [release page](https://github.com/Kvitekvist/FUS/releases)!
