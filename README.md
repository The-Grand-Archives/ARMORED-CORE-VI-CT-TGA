# ARMORED CORE VI Cheat Table

![Cheat Table Version](https://img.shields.io/github/v/release/The-Grand-Archives/ARMORED-CORE-VI-CT-TGA?include_prereleases&label=Cheat%20Table&sort=semver&logo=github)
![Downloads](https://img.shields.io/github/downloads/The-Grand-Archives/ARMORED-CORE-VI-CT-TGA/total?label=Downloads&logo=github)
[![Discord](https://img.shields.io/discord/334557263203401729?label=Discord&logo=discord)](https://dsc.gg/the-grand-archives)  
ARMORED CORE VI FIRES OF RUBICON Cheat Engine table maintained by The Grand Archives. 

## Discord

Our community, make sure to read the rules carefully.  
[The Grand Archives](https://dsc.gg/the-grand-archives)  

If it doesn't work, try this [alternative invite](https://discord.gg/2RTW6BFgeX)

## Latest Release

[![Download](https://img.shields.io/badge/dynamic/json.svg?label=download&url=https://api.github.com/repos/The-Grand-Archives/ARMORED-CORE-VI-CT-TGA/releases/latest&query=$.assets[0].name&style=for-the-badge)](https://github.com/The-Grand-Archives/ARMORED-CORE-VI-CT-TGA/releases/latest)  
[Changelog](/CHANGELOG.md)

### Requirements

Cheat Engine: [7.5](https://github.com/cheat-engine/cheat-engine/releases)  
Game: Executable v1.06 / App Ver. 60

## How to use

### Info

This table is not meant to be used online and you will most likely be banned if you attempt to do so.

### Cheat Table (Windows)

1. Download and install Cheat Engine either from [Github](https://github.com/cheat-engine/cheat-engine/releases) or from its [website](https://cheatengine.org/)
2. Download the [Cheat Table](https://github.com/inuNorii/Armored-Core-VI/releases)
3. Unpack the .CT file anywhere, a recommendation would be your **My Cheat Tables** folder (e.g. `%USERPROFILE%\Documents\My Cheat Tables`)
4. Disable EasyAntiCheat and run the game, see [Disabling EasyAntiCheat](#disabling-easyanticheat)
5. Load the .CT file directly via double-click or selecting it and pressing enter, or launch Cheat Engine and load the .CT file via File->Load or by clicking on the folder icon
6. Activate the "Open" script by ticking its box

### Cheat Table (Linux)

I expect you to already have Steam, Wine, Proton, and the game installed

1. Launch the game at least once via Steam to have your wine prefix set up
2. Install [protonhax](https://github.com/jcnils/protonhax) (On Arch you should grab [protonhax-git](https://aur.archlinux.org/packages/protonhax-git))
3. Download and install the **Windows** version of Cheat Engine from [Github](https://github.com/cheat-engine/cheat-engine/releases) or from its [website](https://cheatengine.org/) using **Wine**
4. Download the [Cheat Table](https://github.com/The-Grand-Archives/ARMORED-CORE-VI-CT-TGA/releases)
5. Unpack the .CT file anywhere, a recommendation would be somewhere you can easily find within the wine prefix created for the game (e.g. `~/.steam/steam/steamapps/compatdata/1888160/pfx/drive_c/`)
6. In Steam, set the game's launch options to `protonhax init %command%`
7. Run the game via Steam ([Disabling EasyAntiCheat](#disabling-easyanticheat) is optional)
8. Run Cheat Engine via `protonhax run 1888160 /path/to/Cheat\ Engine.exe` in your terminal of choice or put it in a shell script (replace `/path/to/` with your actual path to where you installed CE)
9. Load the .CT file via File->Load or by clicking on the folder icon
10. Activate the "Open" script by ticking its box

### Disabling EasyAntiCheat

#### Method 1 - Recommended

1. Unpack `steam_appid.txt` from the [latest release](https://github.com/The-Grand-Archives/ARMORED-CORE-VI-CT-TGA/releases/latest)
2. Locate your ARMORED CORE VI folder (e.g. `C:\Program Files\Steam\steamapps\common\ARMORED CORE VI FIRES OF RUBICON\Game` or `~/.steam/steam/steamapps/common/ARMORED CORE VI FIRES OF RUBICON/Game/`)
3. Move `steam_appid.txt` into the same folder as your ARMORED CORE VI executable (`armoredcore6.exe`)
4.
   - Windows: Run the game via `armoredcore6.exe`
   - Linux: Add `armoredcore6.exe` as a non-steam app and run that

#### Method 2 - Legacy

1. Locate your ARMORED CORE VI folder (e.g. `C:\Program Files\Steam\steamapps\common\ARMORED CORE VI FIRES OF RUBICON\Game` or `~/.steam/steam/steamapps/common/ARMORED CORE VI FIRES OF RUBICON/Game/`)
2. Rename `start_protected_game.exe` to something else (e.g. `start_protected_game.exe.bak`)
3. Rename `armoredcore6.exe` to `start_protected_game.exe`
4. Run the game via Steam or `start_protected_game.exe`

## Credits

The Grand Archives | Reason
------------- | ---------------------
Ametalon | Table contributions (DS3)
[LukeYui](https://github.com/LukeYui) | AddItem function, char flags
[Dasaav](https://github.com/Dasaav-dsv) | Table contributions (DS3/ER)
[inuNorii](https://github.com/inuNorii) | Porting, maintaining, research
[tremwil](https://github.com/tremwil/) | FD4Singleton finder and more

Github | Reason
------------- | ---------------------

Other | Reason
------------- | ---------------------
