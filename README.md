<div align="center">

<img src="assets/images/hulagu.ico" alt="HuLagU Logo" width="220"/>

# HuLagU — Gaming Network Optimizer

**Reduce your ping. Dominate your game.**

[![Version](https://img.shields.io/badge/version-1.0.8.2-blue?style=flat-square)](https://github.com/HuLagU/HuLagU)
[![Platform](https://img.shields.io/badge/platform-Windows-0078D6?style=flat-square&logo=windows)](https://github.com/HuLagU/HuLagU)
[![License](https://img.shields.io/badge/license-Proprietary-red?style=flat-square)](https://github.com/HuLagU/HuLagU)

[**فارسی**](README.fa.md) | **English**

---

<img src="docs/screenshots/main_window.png" alt="HuLagU Main Window" width="320"/>

</div>

---

## What is HuLagU?

HuLagU is a Windows desktop application that optimizes your network connection specifically for gaming. It routes your game traffic through high-performance servers to reduce latency, lower packet loss, and stabilize your ping — giving you a competitive edge in online multiplayer games.

---

## Screenshots

<div align="center">

| Login | Main Window | Game Selection |
|:-----:|:-----------:|:--------------:|
| <img src="docs/screenshots/login.png" alt="Login Screen" width="240"/> | <img src="docs/screenshots/main_window.png" alt="Main Window" width="240"/> | <img src="docs/screenshots/game_selection.png" alt="Game Selection" width="240"/> |

</div>

---

## Key Features

- **Smart Game Detection** — Automatically finds your installed games so you don't have to configure anything manually.
- **One-Click Connect** — Press the power button to instantly route your game traffic through optimized servers.
- **40+ Supported Games** — Works with CS2, Valorant, Dota 2, PUBG, Fortnite, Apex Legends, Marvel Rivals, and many more.
- **Launcher Support** — Compatible with Steam, Epic Games, Battle.net, EA App, Ubisoft Connect, and others.
- **Real-Time Status** — Visual connection indicator shows your current state at a glance.
- **Region Selection** — Choose the server region closest to your game servers for the lowest latency.
- **DNS Mode** — Included DNS optimization for additional connection improvements.
- **Persian Language Support** — Full Farsi UI for Persian-speaking users.

---

## Supported Games

<div align="center">

| | | | | | |
|:---:|:---:|:---:|:---:|:---:|:---:|
| Counter-Strike 2 | Valorant | Dota 2 | PUBG | Fortnite | Apex Legends |
| Marvel Rivals | Warzone | Overwatch 2 | League of Legends | Rocket League | Rainbow Six Siege |
| World of Warcraft | Dead by Daylight | The Finals | FACEIT | GTA V | Warframe |
| Helldivers 2 | Mortal Kombat 1 | EA Sports FC 25 | F1 24 | FiveM | Battlefield 1 |
| Battlefield V | Red Dead Redemption 2 | Lost Ark | Once Human | Hunt: Showdown | ARK |
| Phasmophobia | Street Fighter 6 | Outlast Trials | ETS2 | For Honor | *+ more* |

</div>

---

## System Requirements

| Requirement | Minimum |
|---|---|
| OS | Windows 10 / Windows 11 (64-bit) |
| RAM | 2 GB |
| Disk Space | 150 MB |
| Network | Active internet connection |
| Account | HuLagU account (free registration) |

---

## Installation

1. Download the latest installer from the [GitHub Releases page](https://github.com/AmirHossein143/HuLagU/releases/download/best_release/HuLagU_Setup.exe) or the [Telegram channel](https://t.me/hulaguservice).
2. Run `HuLagU_Setup.exe`.
3. Follow the installation wizard.
4. Launch HuLagU, sign in with your account, and click **Connect**.

> **Note:** Some antivirus programs may flag the installer. This is a false positive — see the [Antivirus section](#antivirus--security) below.

---

## How It Works

1. **Login** — Sign in with your HuLagU account credentials.
2. **Select Game** — HuLagU auto-detects your installed games. Choose the one you want to play.
3. **Choose Region** — Select the server region that gives you the best connection to your game's servers.
4. **Connect** — Hit the power button. HuLagU routes your game traffic through an optimized tunnel via WireSock (a WireGuard-based client).
5. **Play** — Launch your game and enjoy lower, more stable ping.

---

## Antivirus & Security

HuLagU may be flagged by some antivirus software because it:

- Scans your file system to locate game installations.
- Creates and manages network tunnels (via WireSock / WireGuard).
- Modifies network routing rules while connected.

These are expected behaviors for any gaming network optimizer. HuLagU does **not**:

- Collect personal data beyond what is required for your account.
- Access files unrelated to gaming.
- Modify system files outside of network configuration.
- Monitor your browsing activity.

We use industry-standard WireGuard encryption for all tunnel traffic.

### Adding HuLagU to antivirus exceptions

**Windows Defender:**
`Windows Security → Virus & threat protection → Manage settings → Add or remove exclusions → Add the HuLagU installation folder`

**Other antivirus programs:**
Look for an "Exceptions" or "Exclusions" section in your antivirus settings and add the HuLagU installation folder (default: `C:\Program Files\HuLagU`).

---

## Built With

| Technology | Role |
|---|---|
| **Python 3** | Core application language |
| **PySide6 (Qt)** | Desktop GUI framework |
| **WireSock / WireGuard** | Encrypted network tunneling |
| **Flask** | Backend REST API |
| **PyInstaller** | Packaging to standalone executable |
| **Inno Setup** | Windows installer creation |

---

## Support

- **Telegram Support:** [@HuLagUsupport](https://t.me/HuLagUsupport)
- **Telegram Channel:** [@hulaguservice](https://t.me/hulaguservice)
- **Telegram Bot:** [@HuLagUbot](https://t.me/HuLagUbot)
- **Discord:** [Join our server](https://discord.gg/HuLagU)

---

## Adding Your Screenshots

To display the screenshots in this README, save your images to the `docs/screenshots/` folder with these exact names:

| File | Content |
|---|---|
| `docs/screenshots/login.png` | Login screen |
| `docs/screenshots/main_window.png` | Main application window |
| `docs/screenshots/game_selection.png` | Game selection dialog |

Then push the files to your repository — the images will appear automatically in the README above.

---

<div align="center">

*Conquer your ping, Vanquish your enemies!*

</div>
