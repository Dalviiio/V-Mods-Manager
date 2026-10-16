# V Mods Manager

A mod manager for **GTA V on PC (Legacy and Enhanced)**, made for script mods: Script Hook V, ASI plugins,
ScriptHookVDotNet scripts, trainers like Menyoo.

**Your game stays vanilla.** Mods are placed in the game folder only while you play with them, and removed as soon
as the game closes. When you launch without mods, there is nothing to clean up by hand.

This repository only holds the releases. Download the installer from the
[latest release](https://github.com/Dalviiio/V-Mods-Manager/releases/latest).

## What it does

- **Drop a mod archive** (zip, rar, 7z) or a folder: the manager finds where each file goes and keeps the mod in its
  own library, never straight in the game.
- **Scans every mod** for suspicious signs before you can enable it (downloaders, hidden programs, data-theft paths,
  packed code...), with a plain-language report. It can also ask Microsoft Defender to scan the mod.
- **Plays with your mods, then puts everything back**: every change is recorded before it is made, replaced files are
  backed up, and the game folder is restored when the game closes, even after a crash or a power cut.
- **Launch vanilla** for GTA Online: checks the game folder first and moves out any mod file found, even ones you
  installed by hand.
- **Legacy and Enhanced**, each with its own mods and settings.
- **Frameworks page**: Script Hook V, ScriptHookVDotNet, NativeUI, LemonUI, iFruitAddon2, Menyoo, Simple Trainer, with
  their latest versions (only if you allow the manager to check online).
- **Mod settings editor** for `.ini`, `.xml` and `.json` files, with search and colors.
- **Game versions**: keep the previous GTA V version after an update, to keep playing with mods until Script Hook V
  supports the new one (optional).
- **Session reports**: the game's logs of your last modded sessions are kept, problems found in them are shown, and
  after a game crash you can make a report to share on the Discord.
- **Desktop shortcuts** "V Legacy" and "V Enhanced" to play modded in one click.
- **Signed updates**: the manager tells you when a new version is out and only installs an installer signed by its
  author.

## Install

1. Download `VModsManager-Setup-X.Y.Z.exe` from the [latest release](https://github.com/Dalviiio/V-Mods-Manager/releases/latest).
2. Run it. No administrator rights are needed: the manager installs in your user folder.
3. Windows may show **"Windows protected your PC"** (SmartScreen): the installer is not signed with a paid Microsoft
   certificate. Click **More info**, then **Run anyway**.
4. Choose your shortcuts and whether to keep previous game versions, then start the manager and pick your game folder.

Downloaded mod archives can be dropped in the **Mods to import** folder created next to the manager.

**Requirements:** Windows 10 or 11 (64-bit), GTA V Legacy or Enhanced (Steam, Epic Games or Rockstar Games Launcher).

## Updates

The manager can check this repository for a new version when it starts (it asks you first). The installer it
downloads is refused unless its signature matches the author's key. It never updates while the game runs or mods are
in the game folder.

## Good to know

- **Mods are for Story Mode only.** Using mods in GTA Online can get your account banned. Use **Launch vanilla** before
  playing online.
- Mods are made by other people and run inside the game with your rights: only use mods from sources you trust. The
  scan helps you decide, it is not a guarantee.
- No telemetry: nothing is sent unless you ask for it (online checks you allow, reports you choose to send).
- The `mods/` folder of OpenIV, `.rpf` files and the game's own files are never touched.

## Help and feedback

Join the **[V Mods Manager Discord](https://discord.gg/FanVqwFZR6)** to ask for help, report a bug or share a crash
report.

## Legal

By installing V Mods Manager you accept its [terms of use](TERMS-OF-USE.txt)
(shown by the installer and in the manager, Settings > About).

V Mods Manager is an independent project by Dalviiio. It is not made, endorsed or supported by Rockstar Games or
Take-Two Interactive. "Grand Theft Auto", "GTA" and related names and logos are trademarks of their respective owners.
