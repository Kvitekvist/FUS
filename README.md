# FUS - Fundamentals, Updates, and Stuff

FUS is a fundamental and modular modlist for Skyrim VR made by Kvitekvist and Cangar. It offers 4 profiles:

- FUS (Basic): Including the barebones for a good VR experience.
- FUS RO (Basic + Visuals): Also includes some visual improvements.
- FUS RO DAH (Basic + Visuals + Gameplay): Also includes several mods that alter gameplay, both VR-specific and general ones. User are expected to deselect mods from all optional categories, as we ship it with most optional mods enabled. This does not mean that we recommened using all overhauls.
- Cangar: Basically FUS RO DAH with my personal choice of optional mods.

NOTE: We only provide support on unmodified versions of FUS.

--------

[Join the discord](https://discord.gg/Kv6MdXY3fB) for support, chat, and sharing experiences and screenshots!

Channel uses:

general : A General lobby to hang out and have fun with FUS.

support : A channel for support questions for unmodified FUS modlists of the most current version.

unsupported-mod-discussion : If you have made any changes at all to the modlist and have questions to adding, removing or changing things.

suggestions : A channel to suggest new mods or improvements. Keep in mind, the core of FUS is to be minimalistic. Not a modlist to cover everything awesome that nexus has to offer.

bot-faq : Find useful bot commands to help with issues

general-faq : General FAQ's

quick-troubleshooting : Find some answers on common issues

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
    - [Choose controller bindings](#choose-controller-bindings)
    - [VR FPS Stabilizer](#vr-fps-stabilizer)
    - [Insects Begone](#insects-begone)
    - [Other](#other)
- [How to start up FUS](#how-to-start-up-fus)
  - [First steps in the game](#first-steps-in-the-game)
- [What's in the box?! The modlist](#whats-in-the-box-the-modlist)
  - [Noteworthy gameplay mods](#noteworthy-gameplay-mods) 
- [Performance adjustment](#performance-adjustment)
- [FAQ](#faq)
- [Troubleshooting](#troubleshooting)
- [Updating FUS](#updating-fus)
  - [Removing FUS](#removing-fus)
- [Changelog](#changelog)

--------

[Join the discord](https://discord.gg/Kv6MdXY3fB) for support, chat, and sharing experiences and screenshots!

--------

# Installation

This may look like a good amount of work but the process is fast and you just need to follow the steps :) Do not despair! Don't run away! If you feel like anything is unclear please [join the discord](https://discord.gg/Kv6MdXY3fB) and let us know! We will do our best to clear things up and add the clarification for the next user.

## First time installation, PC preparation

These steps are only needed if you install FUS for the first time. If you update the modlist, jump straight to [Updating](#updating-fus)!

Follow all steps on [this page](https://github.com/Kvitekvist/FUS/wiki/Prepare-PC-for-modlist) to prepare your PC to install FUS. This includes requirements, cleaning Skyrim, and installing Wabbajack.

## Download and installation of the FUS modlist

The installation process of the FUS list is straightforward and described [here](https://github.com/Kvitekvist/FUS/wiki/Download-and-Installation-of-the-FUS-modlist).

If you run into any issues see the [wabbajack troubleshooting page](https://github.com/Kvitekvist/FUS/wiki/Wabbajack-Troubleshooting). If the installation is successful, proceed to [Post-Installation](#post-installation).

## Post-installation

You need to open MO2 `ModOrganizer.exe` from within the FUS folder. If you had a different MO2 installed previously, do not use that one.

DO NOT RUN LOOT! Every time you run LOOT a kitten dies and we cry in the corner. The load order is exactly as it should be, do not change it. In case you changed it you can recover it with the [`Restore` button](https://github.com/Kvitekvist/FUS/blob/main/images/restore%20loadorder.png). Such a button exists for the mod order as well as the plugins order.

### Activate the essential files

[This step](https://github.com/Kvitekvist/FUS/wiki/Activate-the-Essential-Files) will add the required files for SKSE, Engine Fixes, DLL loader and other essential files that cannot be handled by MO2. It is a required step, DO NOT SKIP THIS!

### Choose ENB or Reshade

First of all, we highly recommend not using any supersampling, neither in Steam/Oculus, nor ingame. Set everything to 100%. Supersampling is a very inefficient way of anti-aliasing and given the hunger for performance in Skyrim VR you most likely will drop into reprojection when you try using it.

[Here](https://github.com/Kvitekvist/FUS/wiki/Choose-ENB-or-Reshade) we explain how you can choose and switch different pre-installed ENBs and Reshade presets easily. No need to install manually! :)

All ENB or Reshade options we provide include a sharpener which is meant to be used in combination with temporal anti-aliasing (TAA) switched on ingame.

## Select the profile of your choice

FUS is a fundamental modlist for Skyrim VR that offers 4 profiles.

+ FUS (Basic): Including the barebones for a good VR experience.
+ FUS RO (Basic + Visuals): Also includes some appearance improvements.
+ FUS RO DAH (Basic + Visuals + Gameplay): Also includes several mods that alter gameplay, both VR-specific and general ones.
+ Cangar: FUS RO DAH with my choice of optionals (almost all). Choose this if you want to follow and replay my Youtube series.

Of course you can also select your own choices from the profiles. If you want to use optional mods, it is better to use the FUS RO DAH or Cangar profiles and *deselect* mods than to use the lower profiles and selecting optional mods. This is to preserve the correct load order. If you add optional mods you should make sure that the load order to the right in MO2 has DynDOLOD and Synthesis as the last plugins.

The green parts are really the mods that we think no Skyrim VR mod list should be without.
The blue parts contain a selection of audio/visual/architecture/armory/NPC overhauls that we think is fine to work as standalone. This is personal preference and just a selection we made and like.
The yellow parts are our choice of gameplay improvements/changes. These deviate from vanilla and mostly make the game more interesting and challenging, or just overall improve the feeling. Obviously, these are personal preference, too. You are expected to go over all the optional mods and deslect all the mods that dont fit your style. **ALL MODS IN YELLOW CATEGORY ARE OPTIONAL.** For instance, if the game is too hard, then this is because you opted to use the enemy overhaul mods in category 3.2.
The optional LOD files contain DynDoLOD generated files that enhance the visuals in the distance. These cost performance but make a big difference!
The red late load parts contain patches that we created for this mod list. Use them if you use the respective mods above. 

Mod authors appreciate an endorsement! :)

Surprise: **DO NOT TOUCH** the files that are marked as such. 

### Choose controller bindings

In the green MO2 in category `Controller Bindings` we provide several bindings options. The default vanilla options are not recommended, but there are different options to select which is very much personal preference. 

Please have a look at our [detailed controller binding guide](https://github.com/Kvitekvist/FUS/wiki/Controller-bindings-guide) where you can find info about the different options and what exactly the bindings do in the game. Really, read that guide for sure, it will help you understand what's going on when you are in the game.

No matter the controller binding you use inside Skyrim, if you use the `Valve Index controllers` you need to enable the VRIK SteamVR bindings **in addition**: Navigate to your SteamVR Settings -> Devices -> Controller Settings.  Click on Manage Controller Bindings.  Select The Elder Scrolls V: SkyrimVR from the drop down list.  Click "Edit this Binding" (you may need to click the "Custom" button to make it appear).  A new window will pop up.  You may need to click Back in the top-left.  Make sure it shows your Index Controllers as the Current Controller - Change it if necessary.  A list of Community bindings should become visible.  Find and select the "VRIK Index Controller Bindings V2.1.0" in the list.  Be careful not to select the older V1.0.0 or V2.0.0 bindings by mistake, as this will not work.  Selecting the VRIK Index Controller Bindings V2.1.0 here will complete the process. This can also be done when the game was already started from inside the SteamVR settings menu in VR.

**Note:** Always remember to turn on your controllers before starting SkyrimVR, or you will encounter game-breaking bugs! This is important no matter which VR headset you use.

### VR FPS Stabilizer
AutoConfig feature is NOT compatible with OpenComposite, so FUS has disabled this part of the mod to have a version that works for all users with or without opencomposite.

This mod has a separate category. It smooths your framerate by automatically lowering some LOD distance settings when your GPU can't keep the framerate.  It doesn't perform miracles but it's pretty handy when you're sometimes fine, and sometimes fall into reprojection.

### Insects Begone

We want to make this list as inclusive as we can so we ship an option to remove insects (spiders and chaurus). You can find three optional mods at the end of the blue section. *Only choose one of them!* FYI: We decided not to remove the webs because this breaks some NPCs.

**NOTE:** *If you want to use these you absolutely have to rerun Synthesis and make sure the Synthesis.esp is at the bottom of the plugins section at the right hand side of MO2!* Otherwise the water will be broken, or you don't fully remove all insects and their stuff. Check [this guide](https://github.com/Kvitekvist/FUS/wiki/Settings-for-tools-(LODs-and-Synthesis)) at the bottom for more info.

### Other

One additional thing you might want to change is `Auto Sneak and Jump`, this mod will make it so your sneaking is automatically determined by your head height. If this mod is enabled, playing seated will mean you sneak all the time, so disable this mod if you want to play seated. Additionally you might want to adjust the sneak height in the ini of the mod (right click > show files in explorer) if you feel like sneak doesn't work how you want it. We disabled the auto jump because we don't like it too much but you can of course also enable it again.

Another mod you might or might not like is `Mute the Music` which, surprise, makes the game not play most music. Some tavern songs are still played but in general most music is gone. This is enabled only in the `Cangar` profile for immersion reasons. Safe to enable/disable anytime.

Lastly, `Magic Improvements for Skyrim VR` has an option to change the magic cast angle. We have set it to show magic out of the palm, not like the default pistol shooting style, but if you prefer the latter, you can open the mod files (right click, show in explorer), and set the `MagicRotationYaw` angle to 0.

We also have plently of additional optional gameplay mods that we discuss in the [noteworthy mods](#noteworthy-gameplay-mods) section.

If you want to use optional mods, it is better to use the FUS RO DAH or Cangar profiles and *deselect* mods than to use the lower profiles and selecting optional mods. This is to preserve the correct load order. If you add optional mods you should make sure that the load order to the right in MO2 has DynDOLOD and Synthesis as the last plugins.

# How to start up FUS

**Note:** Always remember to turn on your controllers before starting SkyrimVR, or you will encounter game-breaking bugs! This is important no matter which VR headset you use.

Head over to the installation folder and locate the executable named `ModOrganizer.exe` and launch it. If you already had MO2 installed, you cannot use your own MO2 version, you have to use the one provided by FUS. Once its launched there will be a dropdown box on the top right and a big `Run` button next to it. Ensure it is set to `Play FUS (SKSE)` by selecting it in the dropdown box and then hitting the `Run` button. 

**This has to be done each time you want to play Skyrim VR!** 

You cannot start Skyrim VR from Steam, always use MO2. Best make a shortcut and put it on the desktop. There's a button for this right next to the `Run` button :)

**IMPORTANT:** Skyrim VR is very particular about controllers. Make absolutely sure Steam VR and your controllers are switched on *before* starting the game!

![image](https://github.com/Kvitekvist/FUS/blob/main/images/play%20fus.png?raw=true)

## First steps in the game

This step also has a video guide on how to get started ingame when using FUS: https://youtu.be/AslbbLDj1e8

When starting the game with FUS you will find yourself in the Realm of Lorkhan, not in the standard intro of Skyrim. Realm of Lorkhan replaces the intro and adds some variety to starting a character (see the [RoL mod page](https://www.nexusmods.com/skyrimspecialedition/mods/18223) for details). You teleport into the world using the crystals, but beware, it is one-way in the `Cangar` profile! The intro is very bugged in VR. We recommend you just watch the [intro on YouTube](https://youtu.be/vsRA5BG3N8E?t=61), and then start a new character. Or start Skyrim from Steam (which means it is without mods), play the intro, then once you leave Helgen, quit the game and start a new game with FUS and pretend its the old one. But don't try to run the intro with the modded game. Its just more stable this way.

The main quest is started by either running through the Bleak Falls Barrow dungeon, or by talking to Jarl Balgruuf in Whiterun.

When you created your character and are in the game you should calibrate [VRIK](https://www.nexusmods.com/skyrimspecialedition/mods/23416) by using the `VRIK Calibration Power` while standing on a flat surface ingame. Then be sure to check the `Mod Configuration` settings in the game and set stuff up how you want it. These mods are probably something you want to check (see their mod pages for more info):

* [Strange Runes](https://www.nexusmods.com/skyrimspecialedition/mods/19456): Here you should disable the dual casting runes as this conflicts with Magic Improvements for Skyrim VR.
* [VRIK](https://www.nexusmods.com/skyrimspecialedition/mods/23416): Here you can fine-tune the calibration (i.e. longer arms/smaller hands, etc, I strongly recommend testing the hand sizes of 0.5 or 2 at least once for shits and giggles. Trust me, just do it.)
* [Weapon Throw VR](https://www.nexusmods.com/skyrimspecialedition/mods/31374): This mod comes with many presets and is very strong by default. If you want to use it take your time to adjust everything to your liking. There is a preset made by me, this makes weapon throw impactful but costly, so they kind of replace power attacks for me.
* [Spell Wheel VR](https://www.nexusmods.com/skyrimspecialedition/mods/47630): Here you can adjust what you see in the spell selection wheel, and you can also change which button summons the wheel.
* [Simply Balanced](https://www.nexusmods.com/skyrimspecialedition/mods/15541): Very detailed options to adjust balance and difficulty of the game. We recommend adjusting both archery and melee damage to 50% because in VR you are much faster than in vanilla for both these combat types (even with a quiver mod like we provide it)
* SkyUI VR: Here you can disable the "Active Effects", which are otherwise floating in your field of view.
* [Strike Obstruction Systems](https://www.nexusmods.com/skyrimspecialedition/mods/53050): By default, a timed block triggers sparks visual effects, but Skyrim being Skyrim these are bugged sometimes. If you don't see sparks when you do timed blocks, but you hear the timed block sound and there is a short slow motion, you can change these to "Flash" for both 1st and 3rd person view to get a different visual effect. You can also disable the slomo effect by disabling "Blockstop".
* [Frozen Electrocuted Combustion](https://www.nexusmods.com/skyrimspecialedition/mods/3532): FEC comes with an extended death cam which is annoying and recommended to be switched off if you use the mod.
* [Be Seated VR](https://www.nexusmods.com/skyrimspecialedition/mods/16613): If you use the mod, you can disable the sitting prompts and the horse support if you don't plan to sit on a real physical chair.
* [Mage VR](https://www.nexusmods.com/skyrimspecialedition/mods/21297): You can spawn the Mage VR backpack here if you use the mod.
* [Simple Realistic Archery](https://www.nexusmods.com/skyrimspecialedition/mods/28524): You can add stamina cost and time penalty for archery.

# What's in the box?! The modlist

We ship all the little bits and pieces that fix things, improve the basic quality of life, and naturally we include all the cool VR specific mods that bring the game to the level of a modern VR game. Most notably that is VRIK giving you a body, HIGGS VR giving you gravity gloves and weapon physics collisions (not with enemy weapons unfortunately), Spell Wheel VR giving you a spell and other stuff selection wheel like Blade and Sorcery, Weapon Throw VR to - well - throw your weapons, and many more! But also other necessities like USSEP, SkyUI VR, True 3D sound, Engine Fixes VR, SkyVRaan (enabling fake water reflections). Of course, we also have a basic selection for overhauls of trees, architecture, weather, lighting, characters, objects, weapons, armors. And lastly, we offer a small selection of gameplay mods that increase the difficulty a bit, make the game more interesting, improve some stuff here and there. 

We also ship all major ENB or Reshade presets that are very easy for you to enable or disable with a click instead of manual copy action.

We do not feature quest additions, nor added regions or dungeons. However, the list is extremely lightweight and compatibility should not be much of a problem, so you can add them yourself if you like.

Here you can check out our [complete mod list](https://github.com/Kvitekvist/FUS/wiki/The-full-modlist).

## Noteworthy gameplay mods

All `VR Gameplay Mods` are important, and you should also check out the `Optional VR Gameplay Mods` and the `Gameplay Overhauls` in addition and select your choices. Definitely check out the mod pages for details about the mods! In this section we don't discuss visual mods (blue section) since these do not alter gameplay, but you can check them out in our [complete mod list](https://github.com/Kvitekvist/FUS/wiki/The-full-modlist).

If you want to use optional mods, it is better to use the FUS RO DAH or Cangar profiles and *deselect* mods than to use the lower profiles and selecting optional mods. This is to preserve the correct load order. If you add optional mods you should make sure that the load order to the right in MO2 has DynDOLOD and Synthesis as the last plugins.

### VR Gameplay Mods

Green section

* [HIGGS](https://www.nexusmods.com/skyrimspecialedition/mods/43930/) - Hand collision, object grabbing, and gravity gloves-style mechanics for Skyrim VR, all-around must-have mod! I show some of its features in [this video](https://youtu.be/MiD-yuXqDsE). Now also includes two-handing weapons, physical weapon collisions, and an automatic fix for the physics engine.
* [VRIK Player Avatar](https://www.nexusmods.com/skyrimspecialedition/mods/23416) - Gives you a body, weapon holsters, gestures for magic and shouts, and finger animations for oculus and index users. Watch this [setup guide video](https://www.youtube.com/watch?v=TvtEiV3V_gM) to get the most out of it. Run the "VRIK Calibration" power to calibrate the body height and VR scale (in that order).
* [Spell Wheel VR](https://www.nexusmods.com/skyrimspecialedition/mods/47630) - Selection wheel mod for Skyrim VR. It allows you to select spells, weapons, shields, arrows, potions, poisons, food, torch and more without going into a menu very quickly by the press of a button or button combinations to spawn the wheel and hold your hand over the item and letting go of the button. It's equipped automatically. Also shows health, stamina, magicka, enchantment, and needs bars on your wrist (configurable).
* [Swap Drop and Hold](https://www.nexusmods.com/skyrimspecialedition/mods/49425/) - Add some extra VR interactivity by adding spells for equipping weapons you're holding using HIGGs, dropping weapons you have equipped, or swapping weapons between your left and right hands. Assign the spells to VRIK gestures to have it work immersively.
* [Weapon Throw VR](https://www.nexusmods.com/skyrimspecialedition/mods/31374) - You can throw weapons now and they return like Thor's Hammer! I also made a [video](https://www.youtube.com/watch?v=YJlE_xYIiN8) about it and an [update video](https://www.youtube.com/watch?v=a0jIU548Ask) about returning weapons. It is very strong by default so a setup using the Mod Configuration is recommended.
* [Magic Improvements for Skyrim VR](https://www.nexusmods.com/skyrimspecialedition/mods/55751) -  Vastly improved dual casting, spell effect size scales based on magicka percentage, and additional options for aiming spells in VR. By default the spells are cast from your palms now, if you want to shoot them like a pistol, set the angles in the MIS VR ini file to 0.
* [No Stagger Mod](https://www.nexusmods.com/skyrimspecialedition/mods/16335) - Stagger is shite in VR so this mod disables it.
* [Simple Realistic Archery](https://www.nexusmods.com/skyrimspecialedition/mods/28524) - Changes archery so you have to get an arrow from your quiver at the back, can easily use different arrows.
* [Locational Damage VR](https://www.nexusmods.com/skyrimspecialedition/mods/26447) - Headshots do extra damage! Tune up the difficulty and git gud scrub.

### Optional VR Gameplay Mods

Green section

* [Mage VR](https://www.nexusmods.com/skyrimspecialedition/mods/21297) - This mod uses an overlay to let you draw glyphs to cast and equip spells. It also has a very immersive hand-pose magic feature and (invisible) holsters (which are disabled by default because VRIK has holsters, too). But the best thing is the new backpack inventory and immersive looting feature, which lets you loot via drag and drop and without pausing the game. Requires the game to be run via SteamVR (not compatible with OpenComposite). Watch [this video](https://youtu.be/ThWB_TLcMbM) to see the mod and learn how to use it.
* [Navigate VR](https://www.nexusmods.com/skyrimspecialedition/mods/47174) - This mod brings immersive navigation to VR with a functional compass, and equipable maps that may be holstered. In [this video](https://www.youtube.com/watch?v=dj3sqpI-IUg) I show the functions.
* [Drop on Death](https://www.nexusmods.com/skyrimspecialedition/mods/48363) - Makes NPCs drop their items on death. 
* [Physical Dodge VR](https://www.nexusmods.com/skyrimspecialedition/mods/58605) - This mod allows you to initiate a slow time effect with visual feedback (white haze) with a few invincibility-frames by physically moving your body in VR! Three methods to trigger dodging are included to accommodate any size playspace. 
* [Be Seated](https://www.nexusmods.com/skyrimspecialedition/mods/16613) - Do you want to drink a virtual mug of ale or eat a home cooked meal in one of Skyrims taverns? Have the ability to sit anywhere you choose while trekking through the wilderness? Perhapes you dream of a more immsersive sleep system which allows you to actually use beds? Be Seated can now provide these functions and more! 

### Optional Gameplay Mods 

Yellow section

* [Vokrii](https://www.nexusmods.com/skyrimspecialedition/mods/26176) - Vokrii is a lightweight "vanilla-plus" perk overhaul that improves build diversity, but respects the vanilla vision and balance. It is lightweight and uses clean scripting. 
* [Blade and Blunt](https://www.nexusmods.com/skyrimspecialedition/mods/34549?tab=description) - Combat overhaul to make the game more interesting, yellow gameplay section.
* [Enhanced Enemies](https://www.nexusmods.com/skyrimspecialedition/mods/35133) - Ups the enemy levels in dungeons to be more close to the player's level.
* [Skyrim Revamped - Complete Enemy Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/14598) - Enemy Overhaul focusing on enemy variation and hard boss battles. No shame in lowering the game difficulty settings with this enabled, it makes the combats harder and more interesting.
* [Strike Obstruction Systems - Combat Blocking Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/53050) - Blocking can now mitigate damage from blocked Spells, Shouts, Enchants, and Poisons. Timed Blocks slow time and provide greater mitigation, redirect parried arrows & spells, and inflict various debuffs. All features configurable via MCM. 
* [MArc - Muken's Arcane Archery](https://www.nexusmods.com/skyrimspecialedition/mods/30404) - An arcane archer is a hybrid archer/caster class, who combines their archery skills with conjuration and destruction spells. They can shoot arcane and elemental arrows of five different types that they summon with their own magicka, modify them with 16 different "sigil" effect spells, and engrave them with spells they know. 
* [Spellsiphon](https://www.nexusmods.com/skyrimspecialedition/mods/26627) - Optional magic gameplay mod (yellow section), very intuitive and cool once you get the hang of it, can also be used in conjunction with archery and melee playstyles. You can watch this little [introduction and tutorial video](https://www.youtube.com/watch?v=mkG4PoMCwaM) to see what it does in general. It also has an ingame tutorial that explains every step.
* [Apocalypse](https://www.nexusmods.com/skyrimspecialedition/mods/1090), [Mysticism](https://www.nexusmods.com/skyrimspecialedition/mods/27839), and [Triumvirate](https://www.nexusmods.com/skyrimspecialedition/mods/39170) - Add new spells to the game. Select the appropriate patches, too.
* [Spellforge](https://www.nexusmods.com/skyrimspecialedition/mods/46482) - Tired of crowded spell vendors? Want to filter your spell selection by level, school and sub-type (e.g. Fire)? Want to feel like a powerful mage making their own spells in a torrent of arcane flames and unleashed power? Stop eating tomes and instead try out a more immersive, configurable and fun way to expand your spell book. 
* [Conduit](https://www.nexusmods.com/skyrimspecialedition/mods/58023) - When holding a weapon in one hand and a spell in the other, you are able to temporarily "conduct" the spell through that weapon. Different categories of spells make the weapon do different things. Activate the mod in the MCM or by reading the book.
* [Realistic AI Detection](https://www.nexusmods.com/skyrimspecialedition/mods/2345) - This is a recalibration of Skyrim's detection formula, which improves the balanced and realism of sneaking. Enemies will have enhanced sight and hearing abilities, and will search longer when alerted. Three versions are available.
* [Swearing Mudcrabs](https://www.nexusmods.com/skyrimspecialedition/mods/1951) - You didn't know you needed this, [but you do](https://www.youtube.com/watch?v=uSHvPJD_558).

Here you can check out our [complete mod list](https://github.com/Kvitekvist/FUS/wiki/The-full-modlist).

# Performance adjustment

In general, FUS default performance should be good. Depending on your system, you might need to adjust it to improve it, or you might have enough headroom to crank up some settings.

We wrote a [detailed guide](https://github.com/Kvitekvist/FUS/wiki/Performance-adjustment) on how to understand and adjust your ingame performance.

# FAQ

* I want to play seated but then I constantly sneak, changing the settings does nothing! -> Yes, we have a mod overriding that. If you want to play seated, disable `Auto Sneak and Jump` in the green section. This is safe to do in an existing save.

* The game is really blurry. -> Should not be blurry if you enabled a sharpener (ENB/Reshade). Make sure dynamic resolution is off!

* Why is my performance so bad? -> See [above](#performance-adjustment).

* You use 3D trees plus Happy Little Trees? -> We are only using the plants from 3D trees.

* I see you are using USSEP from the Nexus, but I do not see the Skyrim VR - USSEP Compatibility Patch. -> USSEP thing is baked into cleaned master mod.

* Did you address the Realm of Lorkham Unbound quest issue? I did not see Realm of Lorkhan - Unbound Quest Fix. -> Yes, unbound is merged into the list.

* I see some patches that are disabled, or I miss a patch entirely that should be there. -> All patches that are in the list, even when disabled, are merged into the conflict resolution patch. Very likely there is everything you need, but if you think a really important patch is entirely missing, tell us. 

* The LOOT tool missing! -> LOOT is removed because running it will break the modlist.

* I added / changed some mods. What are your settings for rerunning DynDoLOD and Synthesis? -> You can find them [in the wiki](https://github.com/Kvitekvist/FUS/wiki/Settings-for-tools-(LODs-and-Synthesis)).


# Troubleshooting

The [Discord bot](https://discord.com/channels/874974449403826197/916605844261572609) has a list of handy commands with instructions on how to overcome common problems.  If none of these resolve your issue, the Discord has a [support channel](https://discord.com/channels/874974449403826197/874974569373528104) for questions about unmodified FUS modlists of the most current version.


# Updating FUS

If this Modlist receives an update please check the changelog before doing anything. Always backup your saves or start a new game after updating.

**Wabbajack will reset your VRIK settings when updating!** You can save them by backing up the three ini files in the VRIK/SKSE/Plugins folder and putting them back in after you updated.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your downloads folder will not be touched!

You can prevent this deletion by manually renaming the mod to include the "[NoDelete] " flag (inlcuding the space!), e.g. if you installed "OBIS", it then needs to be renamed to "[NoDelete] OBIS" and it will not be removed during updating. You will still have to adjust the load order again after updating!

Other than this, updating is like installing. You only have to make sure that you select the same path and tick the `overwrite` button.

Again, **do check the description/changelog of the update** to get the necessary info.


## Removing FUS

You can just remove the MO2 folder and be done with it. SKSE and ENB files will still be in your game folder. The easiest way to remove these, unless you know what files that is, is to remove them with the tool they were installed with (see [activate essential files](https://github.com/Kvitekvist/FUS/wiki/Activate-the-Essential-Files)), or if you want to be absolutely sure, just do a clean install of Skyrim VR again (see [clean Skyrim](https://github.com/Kvitekvist/FUS/wiki/Prepare-PC-for-modlist#clean-skyrim)).

# Changelog

You can find all changes of each version on the [release page](https://github.com/Kvitekvist/FUS/releases)!
