<div align="center">

![banner](./images/banner.jpg)

</div>

A guide on how to **install mods** in **Fallout 4** on PC. We've also included step-by-step instructions for using [Vortex](https://www.nexusmods.com/about/vortex/), the recommended mod manager by [Nexus Mods](https://www.nexusmods.com/fallout4), and how to install mods manually if preferred.

This guide is focused on **Windows users**, but Linux users running Fallout 4 through **Steam Proton** and **Wine** should also find most instructions adaptable!

## Table Of Contents
* [Requirements](#requirements)
* [Game Version Notes](#game-version-notes)
    * [Running Mods On Linux (Proton/Lutris)](#running-mods-on-linux-protonlutris)
* [Backup Your Game Files!](#backup-your-game-files)
* [Installing Vortex Mod Manager](#installing-vortex-mod-manager)
* [Where To Download Mods](#where-to-download-mods)
* [Installing Mods Through Vortex](#installing-mods-through-vortex)
* [Manual Mod Installation (Advanced)](#manual-mod-installation-advanced)
* [LOOT - Load Order Optimization Tool](#loot-load-order-optimization-tool)
* [Script Extenders (F4SE)](#script-extenders-f4se)
* [Conclusion](#conclusion)
* [See Also](#see-also)

## Requirements
* Fallout 4 installed via Steam or an other PC platform
* A free [Nexus Mods](https://www.nexusmods.com/fallout4) account (optional, but recommended)
* [7-Zip](https://www.7-zip.org/) or equivalent archive manager
* A basic understanding of browsing and copying folders and files on Windows

## Game Version Notes
Fallout 4 only has one official PC version, but mod compatibility *may* differ slightly depending on your installed DLCs or patches.

* The Steam version is fully supported by Vortex and modding tools.
* The Epic Games version may work with mods, but some tools (like F4SE) may not fully support it.

### Running Mods On Linux (Proton/Lutris)
Fallout 4 is rated **Gold** on [ProtonDB](https://www.protondb.com/app/377160) which is good. Most mods work, but modding tools like F4SE or LOOT may require Protontricks or manual workarounds.

## Backup Your Game Files!
Before installing any mods, we strongly recommend **backing up your game** and save data! This ensures you have a fallback solution in the case mod(s) cause your game to crash or corrupt your game installation.

To back up your data, please perform the following steps.

* Copy your Fallout 4 install folder (path included below).
    * `C:\Program Files (x86)\Steam\steamapps\common\Fallout 4`
* Backup your save files (path included below).
    * `Documents\My Games\Fallout4\Saves`

## Installing Vortex Mod Manager
[Vortex](https://www.nexusmods.com/about/vortex/) is the official mod manager from Nexus Mods and the easiest way to install and manage Fallout 4 mods.

To download, run, and configure Vortex, please perform the following stpes.

1. Download Vortex from [here](https://www.nexusmods.com/site/mods/1?tab=files).
    * Unless if you're a premium user, you will need to choose the **slow download** option.
2. Run the installer.
    * **Windows**: Ensure you have [.NET Desktop Runtime 6](https://aka.ms/dotnet/6.0/windowsdesktop-runtime-win-x64.exe) installed!
    * Vortex may prompt and guide you on fixing issues.
3. Now go to the **Games**  tab.
4. Either find Fallout 4 from the **Unmanaged** list of games or search for it in the search box at the top.
5. Click the **Manage** button located in the middle of the Fallout 4 game card.
6. This will attempt to add support for the game.
    * If Vortex has issues finding the game's location, follow the below steps:
        1. Go to the **Games** tab through Vortex.
        2. Find the game card under the **Managed** list.
        3. Click the **three dots** button located to the top-right of the card.
        4. Click **Manually Set Location**.
        5. Select the location of your game install.
    * Ensure you see the game's section in the left sidebar. If not, click the **Activate** button under the game card.

Vortex should now be configured and installed for modding Fallout 4!

## Where To Download Mods
The main source for Fallout 4 mods is [Nexus Mods](https://www.nexusmods.com/fallout4).

There are other less popular websites listed below.

* [LoversLab](https://www.loverslab.com/) (warning! Includes NSFW content)
* [ModDB](https://www.moddb.com/games/fallout-4)

**TIP** - Always read the full mod description and user comments. Some mods require prerequisites, patches, or special installation steps.

## Installing Mods Through Vortex
1. Ensure you're logged into your Nexus Mods account through Vortex.
    * You can click the **Login** button at the top-right of the application if not.
3. Go to the mod's page you want to install on Nexus Mods' website.
4. If Vortex is supported, you'll see a **Vortex** button next to the **Manual** button on the right side. Click this button.
    * If you don't see a Vortex button, it means the mod is **not supported** through Vortex and you'll need to **manually install** the mod (instructions included below).
5. Choose what download type you want (e.g., slow download).
6. The file should open in Vortex automatically and start downloading.
    * Go to the **Downloads** tab through Vortex to check the progress!
7. The mod should be automatically installed.
    * You can go to the **Mods** tab under the Fallout 4 section in the left sidebar to confirm if the mod is loaded.
    * You can remove mods by clicking the **Remove** button located on the right side of the mod item.

Launch Fallout 4 and confirm the mod is working!

## Manual Mod Installation (Advanced)
For those who want more control or are installing mods not compatible with Vortex, these are the general steps for manually installing mods in Fallout 4.

1. Download the mod manually from Nexus Mods.
2. Extract the archive using [7-Zip](https://www.7-zip.org/) or another archive manager.
3. Copy the files into your Fallout 4 `Data` folder listed below.
    * `C:\Program Files (x86)\Steam\steamapps\common\Fallout 4\Data`
4. Enable the plugin (if any) via the following steps.
    * `Documents\My Games\Fallout4\Fallout4Prefs.ini`
        * Add: `bEnableFileSelection=1` under `[Launcher]`
    * And ensure plugins are listed in `plugins.txt`

You should now be able to launch Fallout 4 and try out your new mods!

## LOOT (Load Order Optimization Tool)
Some mods must be loaded in a specific order to work correctly. [LOOT](https://loot.github.io/) can help sort your load order automatically!

To download and use LOOT, please perform the following steps.

1. Download LOOT from [here](https://loot.github.io/).
2. Install and launch it.
3. Click **Sort Plugins**.
4. Apply any suggested changes.

**NOTE** - You can integrate LOOT directly with Vortex.

## Script Extenders (F4SE)
Some mods rely on the **Fallout 4 Script Extender (F4SE)** to function.

To download and use F4SE, please perform the following steps.

1. Download F4SE from [here](https://f4se.silverlock.org/).
2. Extract the files.
3. Copy the following files to your main Fallout 4 directory.
    * `f4se_loader.exe`
    * `f4se_*.dll` files
4. Always launch the game using the `f4se_loader.exe` executable instead of `Fallout4.exe`.

You can also configure Vortex to launch via F4SE by doing the following.
* Go to Vortex > Dashboard > Add tool > Target `f4se_loader.exe`

**NOTE** - If Fallout 4 updates, you may need to re-download F4SE for compatibility.

## Conclusion
That's about it! By now, you should have a basic understanding of downloading and installing Fallout 4 mods using mod managers such as Vortex and manually.

Mods often times greatly enhances the Fallout 4 gameplay experience or adds a bunch of randomness to the gameplay.

## See Also
* [Nexus Mods - Fallout 4](https://www.nexusmods.com/fallout4)
* [F4SE - Script Extender](https://f4se.silverlock.org/)
* [Vortex Mod Manager Guide](https://wiki.nexusmods.com/index.php/Vortex)
* [LOOT - Load Order Optimizer](https://loot.github.io/)
* [Fallout 4 Modding Subreddit](https://www.reddit.com/r/FalloutMods/)

This guide will be updated and improved on over time. If you see any improvements that can be made, please feel free to reach out!