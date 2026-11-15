<table align="center" width="100%">
  <tr>
    <td align="center"><h3>🇬🇧<br><a href="README.md">English</a></h3></td>
    <td align="center"><h3>🇨🇿<br><a href="README_CZ.md">Česky</a></h3></td>
    <td align="center"><h3>🇷🇺<br><a href="README_RU.md">Русский</a></h3></td>
  </tr>
</table>

---

# Combat Pillows (Bulánci): Enhanced Edition

[![Platform](https://img.shields.io/badge/platform-Windows%2010%20%7C%2011-blue.svg)](https://github.com/Puzozhitel/combat-pillows)
[![License](https://img.shields.io/badge/license-Freeware%20%7C%20Community-green.svg)](https://github.com/Puzozhitel/combat-pillows)
[![Languages](https://img.shields.io/badge/languages-Czech%20%7C%20English%20%7C%20Russian-orange.svg)](https://github.com/Puzozhitel/combat-pillows)
[![Multiplayer](https://img.shields.io/badge/multiplayer-Online%20%7C%20LAN%20%7C%20Steam%20Remote%20Play-red.svg)](https://github.com/Puzozhitel/combat-pillows)

**Combat Pillows (Bulánci): Enhanced Edition** is the definitive, community-driven preservation and modernization project for the legendary 2001 top-down action shooter by **SleepTeam**, based on the latest available classic release.

This edition reverse-engineers and enhances the original Win32 engine to provide seamless compatibility with modern PCs, global online multiplayer over the Internet, high-resolution display scaling, unlimited user-created maps, and a native in-game auto-updater — while preserving 100% of the authentic physics, art style, and classic gameplay.

---

## ✨ Key Features

* 🌐 **Global Online Multiplayer:** Play over the Internet with friends worldwide without third-party VPN tools (Hamachi/Radmin) or manual port forwarding. Powered by integrated UPnP automatic port-mapping and an optional Master Server Browser.
* 🎮 **Steam Remote Play Together:** Native integration allowing you to stream local multiplayer & deathmatch sessions to your Steam friends with a single invite.
* 🖥️ **Modern Windows & Display Support:** Fully optimized for Windows 10 and Windows 11 via custom `cnc-ddraw` integration. Supports arbitrary display resolutions (1080p, 1440p, 4K, ultrawide), integer scaling, smooth 60 FPS rendering, windowed/borderless modes, and optional CRT/xBRZ shaders.
* 🗺️ **All Maps Unlocked & Custom Map Support:** All original campaign and deathmatch levels are unlocked from the start. Engine memory limits have been patched to support unlimited custom user-created maps (.eap files).
* 🔄 **Built-In Auto-Updater:** Checks for updates seamlessly via the GitHub Releases API (both automatic non-blocking startup check and manual check in the Exit dialog). Downloads and applies updates safely while backing up your previous executable.
* 📜 **Restored Content & Typographic Polish:** Restored poetic splash ticker (classic Czech poetry in the menu), crisp pixel-perfect 1px HD font rendering, fixed timing stutters, and corrected aspect ratios.
* 🌍 **Three Built-in Language Editions:**
  * 🇨🇿 **Bulánci** (Original Czech)
  * 🇬🇧 **Combat Pillows** (English)
  * 🇷🇺 **Боевые Подушки** (Russian)
* 🐛 **Engine Bug Fixes:** Eliminated legacy DirectDraw crashes, fixed Alt+Tab behavior, resolved sound buffer stuttering, and removed legacy memory clamp limitations.
* 📦 **100% Portable:** Zero external dependencies, installers, or registry modifications. Just download the executable and play anywhere.

---

## 📥 Quick Start

1. Go to the [**Releases**](https://github.com/Puzozhitel/combat-pillows/releases) page.
2. Download the single executable file for your preferred language:
   * `Bulanci-<version>.exe` — Czech edition
   * `CombatPillows-EN-<version>.exe` — English edition
   * `CombatPillows-RU-<version>.exe` — Russian edition
3. Run the downloaded executable directly. No installation or extraction required.

---

## 🕹️ Multiplayer Guide

### 1. Online Multiplayer (Direct IP / UPnP)
1. The **Host** starts a multiplayer game in the main menu.
2. The integrated companion automatically opens the necessary network port via **UPnP** and displays the external IP address to share with friends.
3. Other players choose **Multiplayer -> Connect**, enter the Host's IP, and join the match.

### 2. Steam Remote Play Together
1. Add the game to Steam as a non-Steam game (or keep `steam_appid.txt` present).
2. Launch the game, open the Steam Overlay (`Shift+Tab`), right-click any friend, and click **Remote Play Together**.
3. Play split-screen / hot-seat multiplayer over the Internet with only one copy of the game needed!

---

## 🗺️ Custom Maps

To add custom maps:
1. Place your `.eap` files into the same folder where your game executable is located.
2. The game will automatically detect and list all custom maps without overwriting the original levels.

---

## ⚙️ Display & Video Settings

You can customize video rendering and scaling by opening `ddraw.ini` in any text editor:
* **Windowed / Fullscreen:** Change `fullscreen=true` or `windowed=true`.
* **Shaders:** Enable CRT scanlines or smoothing shaders in the `[Shaders]` section.
* **Aspect Ratio:** Preset to integer scaling to preserve crisp retro pixel art.

---

## ⚖️ Disclaimer & Credits

* **Original Game:** Created by **SleepTeam** (2001). All original intellectual property, sounds, and sprite art belong to their respective creators.
* **Enhanced Edition:** A non-commercial, open-source community preservation initiative dedicated to keeping classic 2D retro games playable on modern operating systems.
