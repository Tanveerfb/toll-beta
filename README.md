# Toll — beta builds

Toll is a turn-based card battler in the Element Clash universe. This repository holds only
the game's Windows builds for beta testers; there is no source code here. Anyone with the link
can download them.

## Download and play

1. Open **[Releases](../../releases)** and download the newest `Toll-<version>.zip`.
2. Unzip it anywhere (your Desktop is fine; avoid a Temp folder).
3. Double-click **`Launcher.exe`**, then **PLAY**.

You download a zip only once. From 0.3.0 on, the launcher checks for a new build each time you
open it, downloads and installs it, then lets you play. Open the game through `Launcher.exe`;
a `Toll.exe` opened on an old build sends you to the launcher. **Coming from 0.2.0 or 0.1.0?**
Download the newest zip once by hand and unzip it over your old folder; your account and save
carry over.

Windows may show **"Windows protected your PC"**, because the game is not code-signed yet.
Click **More info**, then **Run anyway** (for `Launcher.exe` and `Toll.exe` the first time).
Some antivirus programs flag unsigned games the same way, especially one that downloads
updates; it is safe to allow it. In Avast: **Menu → Settings → General → Exceptions → Add
exception**, and add the folder you unzipped Toll into.

## System requirements

| | Minimum |
| --- | --- |
| OS | Windows 10 or 11, 64-bit |
| CPU | 64-bit Intel or AMD with SSE4.2 (roughly 2012 or newer) |
| Graphics | Vulkan support: Intel HD Graphics 500 series or newer, NVIDIA GeForce 600 series or newer, AMD Radeon HD 7000 series or newer, with current drivers |
| Memory | 4 GB RAM |
| Storage | 1 GB free (the game takes about 300 MB; an update needs room for a while) |
| Display | 1280 x 720 or larger (the window scales) |

No powerful graphics card is needed: the game is 2D. If it closes at once or shows a graphics
error, update your graphics drivers first, then tell us your laptop or graphics card model.

## Signing in

Create an account with your email or sign in with Google to keep your save (for Google the
game opens a browser tab; finish there and come back). Or play as a guest: nothing is saved
online then.

If signing in says **"A secure connection was blocked"**, your antivirus is scanning secure
connections (Avast's Web Shield does this). In Avast: **Menu → Settings → General → Exceptions
→ Add exception**, add `https://*.googleapis.com/*`, `https://*.github.com/*` (the launcher's
updates) and the folder you unzipped Toll into.

## Discord

Patch notes, known issues and the beta chat live on the **Toll: Element Clash** server:
**https://discord.gg/b2XK2Tc2WF**

## Reporting a bug or an idea

Press **F1** anywhere in the game: pick BUG, SUGGESTION or REQUEST, write what happened, and
send. It brings along the screen, the version and the end of the game's log, so we can find
the problem. You can also open an **[Issue](../../issues)** here.

## Privacy

What Toll keeps:

- **Your account:** your email address (and your Google name, if you sign in with Google),
  kept by Firebase, Google's service, so you can sign in.
- **Your player name**, so other players see it and no one else can take it.
- **Your save:** your settings, your characters and their levels, your gold, bag, mail and
  teams.
- **Reports** you send with F1: your words, the screen, the game's version, the time, the end
  of the game's log, and a fight's seed.

On your computer only: the logs of your last 20 fights. If Discord is open, it shows
"Playing Toll" on your profile and nothing else.

Nothing is sold or shared. No ads, no tracking. **Settings → DELETE ACCOUNT** removes your
account, your save and your name at once. Reports you already sent are kept to fix the game;
open an Issue here to have them removed.

## What is in the beta

Sign-in and player names, the menus, every character's file (all twelve are yours in the
beta), practice fights, settings, and the F1 report form. Since 0.2.0: character levels and the
six-level ultimate ladder, your roster saved to your account, and tags on every file. Since
0.3.0: the launcher and its updates, Growth (feed study books to level a character to 20),
gold, the bag and its chests, mail with a welcome gift, up to five saved teams with team
practice fights, saved fight logs, keyboard controls, and Discord status.
