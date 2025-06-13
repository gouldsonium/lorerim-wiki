---
layout: default
title: Read Me
nav_order: 2
---

# LoreRim - A Modern Action RPG

![Image]({{ site.baseurl }}/assets/logos/greybeards.png)

Wabbajack Modlist Installer by **biggie_boss**.

<table stlyle="border: none;">
<tr>
<td><a href="https://www.nexusmods.com/skyrimspecialedition/mods/112590">Nexus Page</a></td>
<td><a href="https://github.com/wabbajack-tools/wabbajack/releases">Download on Wabbajack</a></td>	
<td><a href="https://loadorderlibrary.com/lists/lorerim">Load Order Library</a></td>
<td><a href="https://discord.gg/Tb5ETzBYjd"><img alt="Discord" src="https://cdn.logojoy.com/wp-content/uploads/20210422095037/discord-mascot.png" width="64px" ></a></td>
</tr>
</table>

## Preamble

**LoreRim** is complete overhaul of Skyrim Anniversary Edition, designed to modernize the visuals and combat of the game while also staying true to lore and bringing back gameplay mechanics from previous games. This modlist is heavily focused on immersion, role-playing and progression.

The main gameplay overhaul in LoreRim is Requiem. Requiem completely delevels the world of Skyrim and encourages careful preperation before combat. Attack - Modern Combat Overhaul provides a basis to revamp third person combat and new animations are included for both first and third person combined with a stance system, allowing players to choose their favorite animation style.

There are multiple EnaiRim mods included to help counter Requiem's default harshness. Growl, Sacrilege, Wintersun Faiths and Apocalypse Magic are all at your disposal.

This list is challenging but it is up to you, the player, to overcome those challenges and become the Dragonborn of Legend. Each level, you will get stronger than the level before. 

## System Requirements

### Disclaimer

Owing to the need to clean master files and certain errors with Wabbajack, LoreRim only supports **English Steam** versions of Skyrim Anniversary Edition. **GOG and other Languages are not supported**. The specific version used is 1.5.97 with the creation club content from 1.6.1170.

{: .warning}
> **WARNING**
>
>LORERIM REQUIRES THE FULL PAID UPDATE TO SKYRIM ANNIVERSARY EDITION. IT IS NOT/WILL NOT BE MADE COMPATIBLE WITH THE NON PAID UPDATE OR OLDER VERSIONS

***

Only, Windows 10 and 11 work with Wabbajack fully. LTSC, special variants, lightened editions or any other modified variant **WILL NOT WORK**. Your windows version **must be 21H2 or newer** to run both Wabbajack and LoreRim.

Running the list from Hard Disk Drives or external drives is **STRONGLY ADVISED AGAINST**. A lot of content is swapped at game run time and, as a result, fast storage and RAM are needed.

### Recommended System Requirements

LoreRim requires a mid-tier modern system to run to its fullest potential. The recommended specs given below are based on utilizing the ENB in the list. For community shaders, you can subtract a little bit from them. Users have reported being able to run on hardware slightly lower than this, however your mileage may vary.

| Component    | Recommended for 1440p (2K Non-Ultrawide) Default Profile| 
|:--------------:|:-------------:|
| CPU | 10th Generation i7 Desktop Version or better/equivalent
| Ram | 32GB DDR4 Ram  + 40GB Pagefile 
| Storage | SATA SSD or higher
| GPU | RTX 3070 Desktop Version or better/equivalent

| Component    | Recommended for 1440p (2K Non-Ultrawide) Ultra Profile| 
|:--------------:|:-------------:|
| CPU | 12th Generation i7 Desktop Version or better/equivalent
| Ram | 32GB DDR4 Ram  + 40GB Pagefile 
| Storage | M.2 SSD
| GPU | RTX 4070 Desktop Version or better/equivalent

**Space Required:**: 300GB Download Size ~350GB install Size ~650GB Total

{: .warning}
> **WARNING**
> 
> Setting up pagefile is a required step, see how to setup a page file [here](https://www.tomshardware.com/news/how-to-manage-virtual-memory-pagefile-windows-10,36929.html)

**NOTE**: AMD RX 580 and older cards are **not supported**.

## Installation

Installing LoreRim is relatively easy and, if you have Nexus Premium, will be a simple waiting game. If you are updating the modlist, you can safely skip to the [updating section](#updating).

### Pre-Installation

Prior to installing LoreRim, please complete the following steps.


1. Install [Visual C++ x64](https://aka.ms/vs/17/release/vc_redist.x64.exe) & [.Net Runtime v8 desktop x64](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-8.0.17-windows-x64-installer)
2. Change Skyrim so it does not [automatically update](https://help.steampowered.com/en/faqs/view/71AB-698D-57EB-178C#disable).
3. Fully uninstall Skyrim by deleting the folder and the Skyrim Special edition folder inside \Documents\My Games\.
4. Fully disable OneDrive and any other programs which hook into user file areas.
5. Reinstall Skyrim into a location that is not Program files. Somewhere like `C:\Games` is a good location. If you only have one drive, look into LostDragonist's [SteamLibrary tool](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide).
6. Start the game once and let it do the graphics check. Do not worry about the settings as it will be replaced during installation.
7. Launch the game to the main menu and allow it to download the paid addon files. **DO NOT VERIFY YOUR GAME FILES**. If you are having trouble with installing Creation Club content checkout our [missing downloads guide](/support/missing-downloads/)
8. Remove/Disable any 3rd party antivirus such as MalwareBytes or Webroot. These **will** mess with the installation and, in the case of the latter, causes more problems than it solves.
9. I recommend temporarily disabling Windows Defender during the download process if you get a false positive for DyndoLOD. DyndoLOD is safe, it is NOT a Trojan. Either that, or add an exception to the download path.

***

### Wabbajack Installation

#### Installing Wabbajack

Once you have completed pre-installation, download the [latest version of Wabbajack]((https://github.com/wabbajack-tools/wabbajack/releases)) and place it in a folder such as `C:\Games\Wabbajack`. Do not place it in program files, on your desktop or in your downloads folder. I recommend placing it on an SSD as it will work quicker on there.

{: .important}
**NOTE**: LoreRim will **always** require the latest version of Wabbajack **UNLESS IT IS SPECIFICALLY STATED HERE**.

**Installation Video:**

<div class="youtube-container">
  <iframe style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" 
    src="https://www.youtube.com/embed/nApuOZWp12c?si=LCdF66V9P1cpFXF0" 
    title="YouTube video player" 
    frameborder="0" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
    referrerpolicy="strict-origin-when-cross-origin" 
    allowfullscreen>
  </iframe>
</div>

#### Downloading and Installing LoreRim

Downloading and installing LoreRim can take a while depending on your internet connection and computer. To install LoreRim, complete the following steps.

1. Open Wabbajack and click on browse modlists.
2. Press the download button on LoreRim and wait for it to download.
3. Set the installation folder to be somewhere like C:\LoreRim. **Do not install it to your desktop or downloads folder.**
4. The download location does not need to be on a SSD but it makes installing a bit faster.
5. Press the play button to begin.
6. Go and pet your nearest fluffy animal whilst Wabbajack does its thing. Alternatively read through this readme again.
7. If the installation is successful, jump for joy and move onto [post installation](#post-installation). If the installation is unsuccessful, follow what is below.

***

##### Problems with installation

It is possible that you may encounter an error with Wabbajack when installing. Some common issues are listed below.

- Could not download x:
	- Big files can fail to download due to connection issues. You can either run Wabbajack again or download the file manually. If you decide to manually download it, make sure to place it in the same place as the other downloads.
    - **Make sure you have downloaded all the Paid AE update content!**

- x is not a whitelisted download:

	 - This will happen when I update the modlist. Please check if there is a new update or wait until you see a release ping.

- Wabbajack could not find my game folder:

	- Either buy the game or go back to the [Pre-Installation](#pre-installation) step.

- Antivirus reports a virus:
	- You did not follow the steps in [Pre-Installation](#pre-installation). Go back and follow it.
	- Again as listed in the previous steps: I recommend temporarily disabling Windows Defender during the download process if you get a false positive for DyndoLOD. DyndoLOD is safe, it is NOT a Trojan. Either that, or add an exception to the download path.
	- If you have followed it then you can fix this by [adding an exclusion for Mod Organizer in Windows Defender](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

## Post-Installation

<div class="youtube-container">
  <iframe style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" 
    src="https://www.youtube.com/embed/6aRAmskgGVo?si=FGo5vdPvBhyHakkR" 
    title="YouTube video player" 
    frameborder="0" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
    referrerpolicy="strict-origin-when-cross-origin" 
    allowfullscreen>
  </iframe>
</div>

### Stock Game & Root Builder

LoreRim utilizes a Wabbajack technology called Stock Game. What this essentially does is create a copy of your Skyrim installation within the installation location of the list. This enables greater compatibility with other mod-lists.

LoreRim also utilizes Root Builder alongside Stock Game to enable easier management of hooks such as ENB, Reshade and Engine Fixes. Please see our guide to [Root Builder](https://github.com/The-Animonculory/Modding-Resources/blob/main/Root%20Builder%20for%20Skyrim%20AE.md) for more details.
***

### XMP/EXPO/RAM OVERCLOCKING:

Skyrim is an old game and very memory sensitive. I DO NOT RECOMMEND enabling XMP/EXPO or overclocking your RAM while playing it. You can check if XMP/EXPO is enabled in your motherboard's BIOS settings.

### OPTIONAL MODS - ULTRAWIDE SUPPORT & PERFORMANCE:

LoreRim comes with several list customization options. There is ultrawide support under the "Widescreen Support" section of Mod Organizer 2. There are several ENB presets to choose from ONLY CLICK ONE OPTION AT A TIME.

### PROFILES:

Using the drop down menu at the top of MO2 you can select from one of 2 profiles.

- Ultra: Full 3d Tree LODs, grass LODs, Nature of the Wild Lands as the default tree mod, heavier ENB.

- Default: 2D Tree LODs, no grass LODs, Happy Little Trees as teh default tree mod, lighter ENB.

{: .important}
Saves are NOT compatible between profiles. They each use different mods that cannot be removed mid-playthrough.

**NOTE**: Screenshots save to `Overwrite\Stock Game`.

### Starting up the list
Open the installation folder and double-click on the program called `ModOrganizer.exe`. 

Make sure the dropdown box on the right is set to `LoreRim` and press the `Run` button.

### In-game MCM options

LoreRim has no required MCM options to be selected; however, you can load the smoothcam preset if you wish to do so.

You are welcome to change any others to achieve your desired setup.

### Starting the Game & Important Information

After creating your character, everything will be automated. You will be prompted to choose your starting skills, birthsign, traits and starting location.

Birthsigns are permanent. Each birthsign becomes stronger when you max a certain skill or skills. These replace vanilla standing stones.

You can pick 3 major and 5 minor skills. Major skills give +10 skill bonuses and determine your starting gear. Minor skills give +5 skill bonus.

You can pick up to 2 traits. There is a way to eventually unlock a 3rd trait later in the game.

You can either exit through the main door or pick a starting location by talking to the dragon. You can begin the attack on Helgen by renting the best room at Helgen's inn.

{: .warning}
MAKE SURE TO OPEN UP YOUR INVENTORY TO INITIALIZE REQUIREM STARTUP.

### Default Hotkeys

For INI related controls, please see https://ck.uesp.net/wiki/Input_Script

Pressing F11 opens up a controller map.

All controls are changed either in the in-game settings, MCM menus or in the "LoreRim MCM and INI Settings" mod.

### Gameplay Tips / Unlocking Cool Mechanics

You can unlock the ability to dodge in first and third person in the evasion tree.

You can unlock starting Dynamic Dodge Shots with bows also in the Evasion Tree.

You can unlock use of a secondary dagger (pulling out a dagger when using your bow) in the One Handed perk tree.

### Known Bugs/Crashes

"Crashing" on loading can occur on any modlist and is not recommended for modded Skyrim. Instead, I highly encourage utalizing the built-in death alternative mod. This prevents needing to reload on death.

Wheeler can cause crashes when assigning self-made potions/poisons/etc and using your last one. If this happens, press home to open dmenu and navigate to wheeler and "reset all wheels".
 
## Updating the modlist

Before updating, please check the changelog and back up your saves. You may need to start a new game after certain updates.

Updating is like installing the list. Simply make sure your paths are the same and tick the `overwrite existing modlist` button. **Note**: Any mods you have added will be deleted when updating.

## Removing the Modlist
Simply delete the folder, and you have uninstalled it.

## Credits and Thanks

- _YOU_ for reading this.
- Shazdeh for SOOOOO many things in LoreRim. Absolute legend.
- Patman & JPSteele for LoreRim's Bestiary addon.
- Althro & Ylikollikas for answering all my questions.
- Bingus, Curly & Aljo for creating Ascensio - upon which the first version of LoreRim was built.
- DiscloApproved for revamping LoreRim's NPCs.
- Abandoned by Arkay & Camboi for inspiring me to create a Requiem-based modlist.
- Halgari and everyone on the WJ Team - Wabbajack is awesome and so are you.
