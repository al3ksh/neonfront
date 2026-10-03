<p align="center">
  <img src="media/main-menu.png" alt="NeonFront main menu" width="100%">
</p>

<h1 align="center">NeonFront</h1>

<p align="center">
  <b>Train. Win. Repeat.</b><br>
  A fast, hero-based arena shooter for Windows. Practise solo, then fight with friends over LAN.
</p>

<p align="center">
  <a href="../../releases/latest/download/NeonFront-Launcher.exe"><img src="https://img.shields.io/badge/DOWNLOAD-Launcher%20for%20Windows-ff6120?style=for-the-badge&logo=windows&logoColor=white" alt="Download the launcher"></a>
</p>

<p align="center">
  <a href="../../releases/latest"><img src="https://img.shields.io/github/v/release/al3ksh/neonfront?style=flat-square&label=latest&color=ff6120" alt="Latest release"></a>
  <img src="https://img.shields.io/badge/platform-Windows%2064--bit-0b1620?style=flat-square" alt="Windows 64-bit">
  <img src="https://img.shields.io/badge/multiplayer-up%20to%208%20players-0b1620?style=flat-square" alt="Up to 8 players">
</p>

---

## Pick your operator

<img src="media/operator-2.png" alt="Operator selection" width="100%">

Four heroes. Each one has a weapon, two abilities and an ultimate.

| Operator | Role | Weapon | E | Q | X (Ultimate) |
|---|---|---|---|---|---|
| **Assault** | Frontline / Sustain | Rifle | Healing field | Helix rocket | Tactical visor |
| **Scout** | Mobility / Flank | Dual SMGs | Dash | Speed boost | Time warp |
| **Sniper** | Precision / Range | Sniper rifle | Scope | Grappling hook | Invisibility |
| **Medic** | Support / Survival | Syringe gun | Healing spray | Resurrect / self-rez | Ubercharge |

## Fight

<img src="media/arena-complex.png" alt="Gameplay in the arena" width="100%">

- **Team Deathmatch, Free-for-All and Control.** In Control, teams capture points and hold them to score.
- **Four maps.** The largest is **Foundry**, a 140 m industrial yard with:
  - sniper nests you reach by ladder or by a parkour route;
  - crouch-only pipes and culverts;
  - a warehouse and a container yard.
- **Server bots.** Bots fill empty slots and move around the map on their own.
- **Killcam.** See the kill replayed from your killer's point of view.
- **Minimap and pings.** Teammates always show on the minimap. Enemies you have spotted stay marked for a few seconds. Hold **G** or the middle mouse button to open the ping wheel, or double-tap it to mark an enemy.
- **Match timer.** The host sets the match length in the lobby.
- **Smooth online play.** The server keeps hits fair and the game stays smooth even with some ping.

<img src="media/foundry-nest.png" alt="Foundry, seen from the sniper nest" width="100%">

## Train

<img src="media/hud-active.png" alt="Training hangar" width="100%">

The **Training Campus** works fully offline:

- **Aim Trainer:** 60-second precision and tracking runs, with personal bests.
- **Target Lab:** test damage and abilities on dummies.
- **Bot Arena:** fight three live bots, with adjustable difficulty.
- **Movement Course:** eight timed checkpoints of sprinting and jumping.

## Play

1. Download **[NeonFront-Launcher.exe](../../releases/latest/download/NeonFront-Launcher.exe)**.
2. Run it. The launcher installs the game to `%LOCALAPPDATA%\NeonFront` and keeps both itself and the game up to date. Then press **PLAY**.
3. To play with friends, one player runs `neonfront_server.exe` from the game folder. It uses port **7777**. Everyone then enters that player's address under **Multiplayer**, creates or joins a lobby, and readies up.

The other release files (`manifest.json` and `NeonFront-<version>-win64.zip`) are for the launcher. You don't need to download them.

### Default controls

| Key | Action |
|---|---|
| W A S D | Move |
| Shift | Sprint |
| Space | Jump |
| Ctrl | Crouch |
| Left mouse | Fire |
| R | Reload |
| E / Q | Abilities |
| X | Ultimate |
| G / Middle mouse | Ping |
| Tab | Scoreboard |
| Esc | Pause menu |

You can rebind every key in **Settings → Keybinds**.

---

<p align="center">
  <sub>This repository only hosts releases. © NeonFront, all rights reserved. See <a href="LICENSE">LICENSE</a>.</sub>
</p>
