# Poosic's Game Hub

Friend kits for the game servers on Julian's machine. Grab a kit, unzip, double-click the **Join** / **Play** file.
Servers start on demand. Use `/up <game>` in Discord (needs that game's role from the role picker).

| Game | Kit | What you need |
|---|---|---|
| **Doom** (co-op) | [PoosicsDoom.zip](../../releases/tag/doom-1.0) | Nothing. Free engine (Odamex) + free game data (Freedoom). |
| **Quake** (co-op) | [PoosicsQuake.zip](../../releases/tag/quake-1.0) | Nothing. Free engine (Ironwail) + free game data (LibreQuake). |
| **OpenArena** (deathmatch, bots fill in) | [PoosicsArena.zip](../../releases/tag/arena-1.0) | Nothing. A free Quake III-style shooter on the ioquake3 engine. |
| **GameCube / Wii party games** (Mario Party 4-9, Mario Kart, Melee…) | [PoosicsDolphin.zip](../../releases/tag/dolphin-1.0) | **Your own copies of the games** — none are included. Dolphin netplay; Julian posts a host code in Discord. |

The join scripts look up the current server address when you launch them, so an address change never means
re-downloading a kit.

## Games you bring your own copy of
No kit needed: these run your normal Steam game and connect to Julian's dedicated server. Start the server with
`/up <game>` first. **The address and passwords are posted in Discord, never here.**

| Game | Port | How to join |
|---|---|---|
| **Left 4 Dead 2** | 27030 | Console (`~`) → `connect <address>:27030`, then `password <pw>` |
| **Valheim** | 2456 | Join Game → Join IP → `<address>:2456`, then the password. Not in the public list. |
| **Factorio** (base game) | 34197 | Multiplayer → Connect to address → `<address>:34197`, then the game password |
| **Don't Starve Together** | 10999 | Browse Games → search "Poosics" (tick "show password-protected") |

## Silent Hill co-op (bring your own game)

| Game | What you need | How to join |
|---|---|---|
| **Silent Hill 1** (real co-op, 2-4 players as Harry + Lisa) | [Silent Hill: United v0.0.5](https://github.com/Depmify/Silent-Hill-United-Public/releases/tag/v0.0.5) + your own Silent Hill 1 (USA) `.bin` in `Data\ROM\` | Run `Launcher.exe` → MULTIPLAYER GAME → ONLINE → join Poosic's room (marked `Wait`). No IP needed. |
| **Silent Hill 2 (2024)** (ghost mode: you see each other + chat, you don't share enemies/items/story) | Your own SH2 (2024) + [GhostCoop 0.1.0-alpha](https://www.nexusmods.com/site/mods/2119) (free Nexus account, leave the zip in Downloads) + **[PoosicsSH2.zip](../../releases/tag/sh2-1.0)** | Run `Set up Silent Hill 2 Co-op.bat` once, then the **Join Poosic's Silent Hill 2** Desktop shortcut (copies the address for you) → Mode: **Client** → paste IP → Launch. |

Everyone needs the **same version** of the mod as Poosic, or you won't see each other.
For SH2, set the game to **Borderless / Windowed Fullscreen** (Options → Display), or the ghost overlay stays hidden behind the game. Overlay hotkeys are F1–F11 (F11 = shared whiteboard). Game files are never shared here.

More games are coming. Julian's bot announces each one in Discord.

## Licenses
Everything in the kits is free to share: Odamex is GPL-2.0 (<https://github.com/odamex/odamex>), Freedoom is
BSD-licensed (<https://freedoom.github.io>), Ironwail and ioquake3 are GPL-2.0, LibreQuake and OpenArena are
free content, Dolphin is GPL-2.0+ (<https://dolphin-emu.org>). License files are inside each kit.
