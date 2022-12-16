# Animonculory Visual Overhaul

![image](https://raw.githubusercontent.com/The-Animonculory/Animonculory-Visual-Overhaul/main/.github/AVOLogo.webp)

Wabbajack Modlist Installer by Althro & Styyx

<table stlyle="border: none;">
<tr>
<td><img src="https://raw.githubusercontent.com/The-Animonculory/Animonculory-Visual-Overhaul/main/.github/WJIcon.png" width="64px" /></td>
<td><a href="https://github.com/wabbajack-tools/wabbajack/releases">Download on Wabbajack</a></td>	
<td><img src="https://raw.githubusercontent.com/The-Animonculory/Animonculory-Visual-Overhaul/main/.github/GitHub.png" width="72px" /></td>
<td><a href="https://discord.gg/DffHKcszfg">Support Discord</a></td>
</tr>
</table>

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

## Contents
  - [Preamble](#preamble)
  - [System Requirements](#system-requirements)
  - [Installation](#installation)
    - [Pre-Installation](#pre-installation)
    - [Wabbajack Installation](#wabbajack-installation)
      - [Installing Wabbajack](#installing-wabbajack)
      - [Downloading and Installing AVO](#downloading-and-installing-avo)
      - [Problems with installation](#problems-with-installation)
  - [Post-Installation](#post-installation)
    - [Root Builder](#root-builder)
    - [BethINI](#bethini)
    - [ENB](#enb)
  - [Playing the List](#playing-the-list)
    - [Profile selection](#profile-selection)
    - [Starting up the list](#starting-up-the-list)
    - [In Game MCM Options](#in-game-mcm-options)
    - [Starting the Game](#starting-the-game)
  - [Updating AVO](#updating-the-modlist)
  - [FAQ](#faq)
   - [Removing the modlist](#removing-the-modlist)
  - [Credits and Thanks](#credits-and-thanks)
  - [Contact](#contact)

## Preamble

Animonculory Visual Overhaul (AVO) is designed as a base for your own modlist. Featuring graphical enhancements, mandatory bug fixes and tweaks and method patching, it is the perfect base to build upon. AVO is made for Skyrim Special Edition Version 1.6.640/659 (also known as Anniversary Edition) and uses the .exe of that version as well. It uses [Solas Weathers](https://www.nexusmods.com/skyrimspecialedition/mods/49004) by default; however, it can support whichever weather mod you wish to use.

The full modlist can be viewed [here](https://loadorderlibrary.com/lists/animonculory-visual-overhaul), a selection of screenshots can be viewed [here](https://imgur.com/a/mcpBqFW) and a video showcase by DroppedIceCream can be viewed below.

[![AVO Showcase](https://img.youtube.com/vi/CXuDlNrPVoo/0.jpg)](https://www.youtube.com/watch?v=CXuDlNrPVoo)

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

## System Requirements

AVO has been tested extensively on a range of systems and using industry standard testing software to determine the required specs for the list. As such, the following specs are recommended to run the list.

| Spec Category | Minimum for 30fps | Recommended for 60fps |
|     :---:    |     :---:      |     :---:     |
| **CPU**   | 6 core/thread @ 2.3Ghz. Laptop style i9-9600t or better. | 8 Core/16 Thread CPU. 8th gen Intel core i7/3rd Gen Ryzen x800 or better |
| **Video Card**    | 6GB Vram clocked between 1290 and 1390. If you have an overcloked model with 4GB (such as a GTX 1060 laptop), you may be able to run it. A card such as the GTX 1060 would work for this. | 8+GB VRAM, but no more than 10 needed, clocked between 1400 and 1500. A card such as a GTX 1080 or 1080ti or better would be ideal.      |
| **Ram**    | 6GB DDR5 with some stuttering.      | 8-10GB DDR5 for smoothest experience. 16GB DDR4/5 advised.     |
| **With ENB**     | +15% to required resources.       | +10% to required resources.      |
| **Expected peformance**    | 35fps outdoors wiith 40+ indoors. Loading times between 20 to 30 seconds.       | 59-112fps outdoors and indoors with loading times around 10 to 15 seconds. Cap FPS to achieve smoother experience.      |
| **Expected non ENB performance**    | 40fps outdoors with 50fps indoors. Loading times between 15 and 40 seconds.      | 100+ fps both outdoors and indoors with loading times between 5 and 15 seconds.     |

Space required: Approx 141GB (Downloads included)

## Installation

Installing AVO is relatively easy and, if you have Nexus Premium, will be a simple waiting game. If you are updating the modlist, you can safely skip to the [updating section](#updating).

### Pre-Installation

Prior to installing AVO, please complete the following steps.

1. Install [Visual C++ x64](https://aka.ms/vs/16/release/vc_redist.x64.exe) & [.Net Runtime v5 desktop x64](https://dotnet.microsoft.com/download/dotnet/5.0/runtime).
2. Change Skyrim so it does not [automatically update](https://help.steampowered.com/en/faqs/view/71AB-698D-57EB-178C#disable).
3. Fully uninstall Skyrim by deleting the folder and the Skyrim Special edition folder inside \Documents\My Games\.
4. Reinstall Skyrim into a location that is not Program files. Somewhere like `C:\Games` is a good location.
5. Start the game once and let it do the graphics check. Do not worry about the settings as it will be replaced during installation.

***

### Wabbajack Installation

#### Installing Wabbajack

Once you have completed pre-installation, download the [latest version of Wabbajack]((https://github.com/wabbajack-tools/wabbajack/releases)) and place it in a folder such as `C:\Games\Wabbajack`. Do not place it in program files, on your desktop or in your downloads folder. I recommend placing it on an SSD as it will work quicker on there.

#### Downloading and Installing AVO

Downloading and installing AVO can take a while depending on your internet connection and computer. To install AVO, complete the following steps.

1. Open Wabbajack and click on browse modlists.
2. Press the download button on AVO and wait for it to download.
3. Set the installation folder to be somewhere like C:\Games\AVO. **Do not install it to your desktop or downloads folder.**
4. The download location does not need to be on a SSD but it makes installing a bit faster
5. Press the play button to begin.
6. Go and pet your nearest fluffy animal whilst Wabbajack does its thing. Alternatively read through this readme again.
7. If the installation is successful, jump for joy and move onto [post installation](#post-installation). If the installation is unsuccessful, follow what is below.

##### Problems with installation

It is possible that you may encounter an error with Wabbajack when installing. Some common issues are listed below.

- Could not download x:
	- Big files can fail to download due to connection issues. You can either run wabbajack again or download the file manually. If you decide to manually download it, make sure to place it in the same place as the other downloads.

- x is not a whitelisted download:

	 - This will happen when I update the modlist. Please check if there is a new update or wait until you see a release ping.

- Wabbajack could not find my game folder:

	- Either buy the game or go back to the [Pre-Installation](#pre-installation) step.

- Antivirus reports a virus:
	- Windows 10/11 may automatically quarantine a key file which is needed for Mod Organizer. You can fix this by [adding an exclusion for Mod Organizer in windows defender](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

## Post-Installation

### Root Builder

To enable compatability with the GOG versions of Skyrim, AVO uses a tool known as Root Builder. For more details regarding it, please view [the mod page](https://www.nexusmods.com/skyrimspecialedition/mods/31720) and our [guide to it](https://github.com/The-Animonculory/Modding-Resources/blob/main/Root%20Builder%20for%20Skyrim%20AE.md).

***

### ENB
AVO comes with Solas Weathers & ENB all ready and set up to go. If you wish to change the ENB, ensure that you are using one compatible with Solas and please follow below.

**NOTE!**: Screenshots save to `Overwrite/Root`.

#### Change the ENB

1. Download whatever ENB you wish to use.
3. Click on the `Spanner and Screwdriver` icon in MO2 and select `Root Builder`.
4. Tick the `Installer` checkbox under `Settings`.
![Rootbuilder config](https://raw.githubusercontent.com/The-Animonculory/ADT/main/.github/RootbuilderConfig.webp)
5. Add the ENB as a new mod in MO2. Rootbuilder should assign it properly.
6. Verify that Rootbuilder has installed the ENB properly. It should look similar to the picture below:
![ENB Rootbuilder Check](https://raw.githubusercontent.com/The-Animonculory/ADT/main/.github/ENBRootBuild.webp)
7. Disable Solas ENB.
8. Activate your new ENB.
9. Enjoy your new ENB.

## Playing the List

### Profile selection

**DO NOT IGNORE THIS STEP!**

Owing to the list now supporting both steam and GOG editions of the game, you **must select** the correct profile for your game copy. **WARNING!**: Failure to do so will result in your game not starting. **DO NOT IGNORE THIS STEP!**

For Steam, select `AVO [STEAM]`. For GOG, select `AVO [GOG]`.

**DO NOT IGNORE THIS STEP!**

***

### Starting up the list
Open the installation folder and double click on the program called `ModOrganizer.exe`. 

Make sure the dropdown box on the right is set to the SKSE corresponding to your game copy (`SKSE [STEAM]` or `SKSE [GOG]`) and press the `Run` button.

### In-Game MCM options
`AVO has no MCM options required, however you can load the SmoothCam preset if you wish.`

- This serves as a placeholder in case you want to use the Readme as some sort of template.

### Starting the Game

- Placeholder for your Readme. By default, AVO uses [Optional Quick Start](https://www.nexusmods.com/skyrimspecialedition/mods/63953).
	
## Adding mods to AVO

To safely add mods to AVO, please read [the guide](https://github.com/The-Animonculory/Animonculory-Visual-Overhaul/blob/main/Adding%20mods%20to%20AVO.md), which covers some of the details you need to know.

## Updating the modlist

Before updating, please check the changelog and back up your saves. You may need to start a new game after certain updates.

Updating is like installing the list. Simply make sure your paths are the same and tick the `overwrite existing modlist` button. **Note**: Any mods you have added will be deleted when updating.

## FAQ

### xEdit based tool configuration for GOG

In order to get xEdit based tools to work with the GOG edition of the game, you need to add arguments which specify where the `data`, `ini` and `plugins` are. An example of this is given below:

`-D:"C:\Games\GOG Galaxy\Games\Skyrim Anniversary Edition\Data" -I:"C:\Users\Althro\Documents\My Games\Skyrim Special Edition GOG\Skyrim.ini" -P:"C:\Games\AVO\profiles\AVO [GOG]\Plugins.txt" -IKnowWhatImDoing -PseudoESL`

### I own the AE paid addon. Is there a version I can use/how do I use it?

Please use [AVO-AE](https://github.com/The-Animonculory/Animonculory-Visual-Overhaul/blob/main/AEReadme.md) for full integration of the creation club content.

Should you not want the integration, disable the mod called `CC Config`. **NOTE**: You will need to resolve any new conflicts that appear with activating the CC content.

***

### Tweaking the Game Settings

#### BethINI

To get some more FPS, tweak the following value in the detail section in BethINI.

- `Shadow Resolution`: 2048
- `Ambient Occlusion`: Either use this or the ENB version. The ENB version is more intensive. Do not have both turned on.
- `Remove Shadows`: I really don’t recommend turning this on, but if you must, then you can.

#### ENB

AVO ships with an ENB setup that is configured to match the look of the list. If you wish to make some changes though, here are a few common tweaks. I recommend opening the console before doing edits.

##### Removing the letterbox (in general as the default ENB doesn't have that effect enabled)

1. Press [Home] to open the ENB menu.
2. In the tab called Shader Parameters, select the `ENBPOSTPASS.FX` section. It will open once you click on it.
3. Scroll down until you see letterbox and untick it.
4. Press the save configuration button.
5. Press [Home] to return to the game.

##### Turning off settings for FPS

If you are struggling for frames but want the colour correction and realism, turn off the following items.

- DetailedShadows
- ComplexFireLights
- ComplexParticleLights – Disable Big Range
- Reflection
- Complex Grass Collision
- Complex Grass

If you really cannot handle the ENB, uncheck `useEffect`. Note that this will make the list look much worse and it's not intended to be played like that.

## Removing the Modlist
Simply delete the folder, and you have uninstalled it.

## Credits and Thanks

- _YOU_ for reading this.
- The Animonculory Team.
- Noggog for Mutagen.
- Halgari and everyone the WJ Team - Wabbajack is awesome and so are you.

## Contact

Whilst I am available primarily on [my server](https://discord.gg/DffHKcszfg), please check the [issues](https://github.com/The-Animonculory/Animonculory-Visual-Overhaul/issues) tab on github first if you have any issues. DO NOT DM ME ON DISCORD.

You are welcome to [contribute](https://github.com/The-Animonculory/Animonculory-Visual-Overhaul/blob/main/Contributing.md) to the list, however please check the [changelog](https://github.com/The-Animonculory/Animonculory-Visual-Overhaul/blob/main/Changelog.md) before you do.

## The Animonculory Team
- Althro - Leader & Head of Development
- Styyx - Senior Management Team & Dev Team
- Chef/Para0x - Senior Management Team & Dev Team
- The Spaniard -Senior Management Team & Documentation
- GuitarBarbarian - Senior Management Team
- Annakins - Dev Team, Testing, Graphics & Documentation
- Astro - Dev Team & Testing
- DestinySlayer - Dev Team & Community Engagement
