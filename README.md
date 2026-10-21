# Toll — beta builds

Toll is a turn-based card battler in the Element Clash universe. This private repository holds
only the game's Windows builds for beta testers; there is no source code here.

## Download and play

1. Open **[Releases](../../releases)** and download the newest `Toll-<version>.zip`.
2. Unzip it anywhere (your Desktop is fine).
3. Double-click **`Toll.exe`**.

Windows may show **"Windows protected your PC"**, because the game is not code-signed yet.
Click **More info**, then **Run anyway**. Some antivirus programs flag unsigned games the same
way; it is safe to allow it.

To update, download the newest zip and replace the old `Toll.exe`.

## System requirements

| | Minimum |
| --- | --- |
| OS | Windows 10 or 11, 64-bit |
| CPU | 64-bit Intel or AMD with SSE4.2 (roughly 2012 or newer) |
| Graphics | Vulkan support: Intel HD Graphics 500 series or newer, NVIDIA GeForce 600 series or newer, AMD Radeon HD 7000 series or newer, with current drivers |
| Memory | 4 GB RAM |
| Storage | 200 MB |
| Display | 1280 x 720 or larger (the window scales) |

No powerful graphics card is needed: the game is 2D. If it closes at once or shows a graphics
error, update your graphics drivers first, then tell us your laptop or graphics card model.

## Reporting a bug

Open an **[Issue](../../issues)** with what you did, what happened, and a screenshot if you
can. The game's log helps too: `%APPDATA%\Godot\app_userdata\Toll\logs\godot.log` (paste that
path into the File Explorer address bar).

## What is in the beta

The menus, the character files, and practice fights (Duke vs Lyra, and a 3+1 team fight).
Accounts and saving are not in yet; they come in a later build.
