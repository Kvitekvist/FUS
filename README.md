# FUS

- [FUS](#fus)
  - [Installation](#installation)
    - [Pre-Installation](#pre-installation)
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
        - [Problems with Wabbajack](#problems-with-wabbajack)
  - [Post-Installation](#post-installation)
   - [Copy Game Folder Files](#copy-game-folder-files)
  - [How to start up FUS](#how-to-start-up-fus)
  - [Updating](#updating)
  - [Noteworthy Mods](#noteworthy-mods)
  - [Removing the Modlist](#removing-the-modlist)
  - [Changelog](#changelog)

## FUS

FUS is a modlist for Skyrim VR that offers 3 profiles.
Basic: Including the barebones for a good VR experience
Basic + Visuals: Also includes some visual improvements
Basic + Visuals + Gameplay: Also includes several mods that alter gameplay, both VR spesific and general ones.

## Installation

### Pre-Installation

These steps are only needed if you install this Modlist for the first time. If you update the Modlist, jump straight to [Updating](#updating).

#### Installing Microsoft Visual C++ Redistributable Package

I doubt you need to do this since you likely already have this installed. The package is required for MO2 and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

#### Steam Config

##### Disable the Steam Overlay

The Steam Overlay can cause issues with ENB and is recommended to be turned off.

Open the Properties window (right click the game in your Library->Properties), navigate to the _General_ tab and un-tick the _Enable the Steam Overlay while in-game_ checkbox.

#### Set the Game language to English

Just do it. This entire Modlist is in English and 99% of glall mods you will find are also in Enish. I highly recommend playing the game in English and **I will not give support to people with a non-English game**. Wabbajack does not support SkyrimVR files in other languages either. Wabbajack will fail file validation for other languages.

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

Now, create a new folder on the root of your gaming drive. For me, this is the C drive. Name it "FUS"
![image](https://i.ibb.co/V9JdtQT/C-drive-folder.png)

The download and installation process can take a very long time depending on your system specs. Wabbajack will calculate the amount of threads it will use at the start of the installation. To have the highest amount of threads and thus the fastest speed, it is advised to have the working folder on an SSD. I Highly recommend getting Nexus premium membership to automate the download process.

1. Open Wabbajack
![image](https://i.ibb.co/JK3rdZc/Browse-modlist.png)

2. Download FUS from here:

3. Once the download of the wabbajack file is done, run the file and set the Installation folder the folder you just created. The downloads path should automatically fill in the installation path.

4. Click the Go/Begin button
5. Wait for Wabbajack to finish
6. If you run into any issues see the next section. If the installation is successful, proceed to [Post-Installation](#post-installation).

##### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off so you loose no progress.

**Could not download x**:

If a mod updated and the old files got deleted, it is impossible to download them. In this case just wait till I update the Modlist.

**x is not a whitelisted download**:

This can happen when I update the modlist. Check if a new update is available and wait if there is none.

**Wabbajack could not find my game folder**:

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Pre-Installation](#pre-installation) step.

**Windows is reporting that a virus has been detected**:

Windows 10 has started to auto quarantine the usvfs_proxy_x86.exe file from the latest version of Mod Organizer 2 saying a threat was detected . This is a known false postive confirmed by the MO2 Devs. You can fix this by adding an exemption for MO2 Folder to your Antivirus. Example for windows defender can be found [here](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

## Post-Installation

### Activate the Essential Files

First, run the program named Essentials Files from Mod Organizer 2.
This step will add the required files for SKSE, Engine Fixes, DLL loader and other essential files that cannot be handled by MO2.

![image](https://i.ibb.co/KrvCB09/essentials1.jpg)

Then Click "OK" if you get a message saying something about Failed to check for update. This is ok.

![image](https://i.ibb.co/P5mpMfH/enb2.jpg)

Then navigate to the Presets menu by pressing the symbol in the top left (the three lines). The menu should look like this:

![image](https://i.ibb.co/YkFSZJ1/enb3.jpg)

1. You must activate the the "00 Essential Files" option. All others are optional.
2. "00 3D Audio" ads 3D audio \ surround to SkyrimVR. Really good, but you might get a bit more performance without.
3. SteamVR - This is on by default.
4. opencompoisite - This can replace SteamVR and will give Oculus users a massive performance boost.
5. openvr_fsr - AMD sharpener, not compatible with opencomposite

### Choose ENB or Shader
From MO2, run the ENB \ Reshade program:

![image](https://i.ibb.co/9YSbjZG/enb1.jpg)

Then Click "OK" if you get a message saying something about Failed to check for update. This is ok.

![image](https://i.ibb.co/P5mpMfH/enb2.jpg)

Then navigate to the Presets menu by pressing the symbol in the top left (the three lines). The menu should look like this:

![image](https://i.ibb.co/YkFSZJ1/enb3.jpg)

Now here, you can choose from a list of different ENB profiles. There are 3 difference performance indicators in their names. Low means low performance cost, Medium means medium performance cost and High means high performance cost. 
If any preset was marked as on, then turn them off, then toggle on the button of your choice. By default, The first option is checked. Uncheck this and then check any of the other options that you would like to test.

![image](https://i.ibb.co/FH866MN/enb4.jpg)


## How to start up FUS

Head over to the installation folder and locate an executable named `ModOrganizer.exe` and launch it. Once its launched there will be a dropdown box on the top right and a big run button next to it. Ensure it is set to SKSE by selecting it in the dropdown box and then hitting the run button.
![image](https://i.ibb.co/BT63QKP/Run-SKSE.png)

## Updating

If this Modlist receives an update please check the Changelog before doing anything. Always backup your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.

## Noteworthy Mods


### Removing the Modlist

You can just remove the MO2 folder and be done with it. SKSE and ENB files will still be in your game folder. The easiest way to remove these, unless you know what files that is, is to do a clean install of Skyrim VR again. See [Clean Skyrim](#clean-skyrim)


