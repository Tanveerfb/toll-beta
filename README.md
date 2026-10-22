# Toll — beta builds

Toll is a turn-based card battler in the Element Clash universe. This repository holds only
the game's Windows builds for beta testers; there is no source code here. Anyone with the link
can download them.

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

## Signing in

Create an account with your email or sign in with Google to keep your save (for Google the
game opens a browser tab; finish there and come back). Or play as a guest: nothing is saved
online then.

If signing in says **"A secure connection was blocked"**, your antivirus is scanning secure
connections (Avast's Web Shield does this). In Avast: **Menu → Settings → General → Exceptions
→ Add exception**, add `https://*.googleapis.com/*` and the path to your `Toll.exe`.

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
- **Your save:** your settings now; your characters and progress later.
- **Reports** you send with F1: your words, the screen, the game's version, the time, the end
  of the game's log, and a fight's seed.

Nothing is sold or shared. No ads, no tracking. **Settings → DELETE ACCOUNT** removes your
account, your save and your name at once. Reports you already sent are kept to fix the game;
open an Issue here to have them removed.

## What is in the beta

Sign-in and player names, the menus, every character's file (all twelve are yours in the
beta), practice fights (Duke vs Lyra, and a 3+1 team fight), settings, and the F1 report form.
