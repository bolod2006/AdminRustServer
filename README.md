<div align="center">

<img src="docs/images/logo.png" alt="Rust Admin Server" width="120"/>

# 🎮 Rust Admin Server

**Modern RCON administration panel for Rust game servers**

[![Platform](https://img.shields.io/badge/Platform-Windows-0078D4?logo=windows&logoColor=white)](https://www.microsoft.com/windows)
[![.NET](https://img.shields.io/badge/.NET-8.0-512BD4?logo=dotnet&logoColor=white)](https://dotnet.microsoft.com/)
[![WPF](https://img.shields.io/badge/UI-WPF-0078D4?logo=windows&logoColor=white)](https://learn.microsoft.com/en-us/dotnet/desktop/wpf/)
[![License](https://img.shields.io/badge/License-Proprietary-red.svg)](LICENSE.md)
[![Version](https://img.shields.io/badge/Version-0.2.0-brightgreen)](https://github.com/bolod2006/RustAdminServer/releases)
[![Stars](https://img.shields.io/github/stars/bolod2006/RustAdminServer?style=social)](https://github.com/bolod2006/RustAdminServer)

<br/>

> ⚠️ **Proprietary Software** — Modification, redistribution and resale are prohibited.
> See [LICENSE.md](LICENSE.md) and [EULA.md](EULA.md) for full terms.

<br/>

<img src="docs/images/preview_main.png" alt="Preview" width="900"/>

<br/>

[📥 Download Live](https://github.com/bolod2006/RustAdminServer/releases) •
[⭐ Upgrade to Pro](https://YOUR_WEBSITE.com/pro) •
[📖 Wiki](https://github.com/bolod2006/RustAdminServer/wiki) •
[🐛 Report Bug](https://github.com/bolod2006/RustAdminServer/issues) •
[💬 Discord](https://discord.gg/YOUR_INVITE)

</div>

---

## 📋 Table of Contents

- [Editions — Live vs Pro](#-editions--live-vs-pro)
- [Features](#-features)
- [Screenshots](#-screenshots)
- [Quick Start](#-quick-start)
- [Configuration](#️-configuration)
- [Server Plugin](#-server-plugin)
- [Architecture](#️-architecture)
- [UI Design](#-ui-design)
- [Roadmap](#-roadmap)
- [License](#-license)

---

## 💎 Editions — Live vs Pro

<table>
<tr>
<td align="center" width="50%">

### 🆓 Live Edition
**Free · No registration required**

<br/>

✅ RCON connection & console\
✅ Online / Offline / Bans management\
✅ Real-time chat monitor & messaging\
✅ Live map with player positions\
✅ Ban / Kick / Kill / Mute / Sleep\
✅ GeoIP country flags\
✅ Steam profile links\
✅ VAC ban status tracking\
✅ Duplicate IP detection\
✅ Search & country filter\
✅ Player info & copy tools

<br/>

**[📥 Download Free](https://github.com/bolod2006/RustAdminServer/releases)**

</td>
<td align="center" width="50%">

### ⭐ Pro Edition
**One-time purchase · Hardware-bound license**

<br/>

Everything in Live, plus:

<br/>

🔓 Teleport to any player\
🔓 Give items to players\
🔓 Scheduled commands system\
🔓 Building & cupboard locations on map\
🔓 Advanced player analytics\
🔓 Extended player history\
🔓 Multi-server support *(coming soon)*\
🔓 Priority support\
🔓 Early access to new features

<br/>

> 🔒 License is bound to your hardware.
> Non-transferable. See [EULA.md](EULA.md).

<br/>

**[⭐ Upgrade to Pro](https://YOUR_WEBSITE.com/pro)**

</td>
</tr>
</table>

---

## ✨ Features

<table>
<tr>
<td width="50%">

### 🗺️ Live Map
- Real-time player positions on server map
- Interactive grid overlay (toggle on/off)
- Coordinate display on hover
- **⭐ Building & cupboard locations** via plugin
- Zoom & pan navigation

### 👥 Player Management
- Online / Offline / Banned player tabs
- Country flags via GeoIP
- VAC ban status via Steam API
- Duplicate IP detection & highlighting
- Search & filter by country or name

</td>
<td width="50%">

### 💻 Server Console
- Full RCON console access
- Color-coded log output
- Command history navigation
- Configurable display settings

### 💬 Chat Monitor
- Real-time chat stream
- Send messages as server
- Timestamps & player names
- Customizable appearance

</td>
</tr>
</table>

### 🛠️ Admin Actions

| Action | Description | Edition |
|--------|-------------|---------|
| 🚫 **Ban / Unban** | Ban with reason and duration | 🆓 Live |
| 👢 **Kick** | Remove player from server | 🆓 Live |
| 💀 **Kill** | Kill player in-game | 🆓 Live |
| 😴 **Sleep** | Force player to sleep state | 🆓 Live |
| 🔇 **Mute / Unmute** | Toggle chat access | 🆓 Live |
| 📋 **Copy Info** | SteamID, IP, Name | 🆓 Live |
| 🌐 **Steam Profile** | Open in browser | 🆓 Live |
| ℹ️ **Player Info** | Detailed player data | 🆓 Live |
| 📍 **Teleport** | Teleport to player | ⭐ Pro |
| 🎁 **Give Item** | Send items to player | ⭐ Pro |
| ⏰ **Scheduled Commands** | Automated timed commands | ⭐ Pro |
| 🏠 **Building Tracker** | Cupboards on map | ⭐ Pro |

---

## 📸 Screenshots

<div align="center">

### 🗺️ Server Info & Live Map
<img src="docs/images/screen_info.png" alt="Info Page" width="800"/>

<details>
<summary>📸 View more screenshots</summary>

<br/>

### 👥 Online Players
<img src="docs/images/screen_online.png" alt="Online" width="800"/>

<br/>

### 💤 Offline Players
<img src="docs/images/screen_offline.png" alt="Offline" width="800"/>

<br/>

### 🔨 Banned Players
<img src="docs/images/screen_bans.png" alt="Bans" width="800"/>

<br/>

### 💻 Console & 💬 Chat
<p>
  <img src="docs/images/screen_console.png" width="395"/>
  <img src="docs/images/screen_chat.png" width="395"/>
</p>

</details>
</div>

---

## 🚀 Quick Start

### System Requirements

| Requirement | Minimum |
|-------------|---------|
| OS | Windows 10 / 11 (x64) |
| Runtime | .NET 8.0 |
| RAM | 256 MB |
| Internet | Required for GeoIP & Steam API |

### Installation

1. Go to **[Releases](https://github.com/bolod2006/RustAdminServer/releases)**
2. Download `RustAdminServer-v0.2.0.zip`
3. Extract to any folder
4. Run `RustAdminServer.exe`
5. Go to **Setting → Config** and enter your server details

### Rust Server RCON Setup

Add to your `server.cfg`:

```bash
rcon.ip       "0.0.0.0"
rcon.port     28016
rcon.password "your_strong_password_here"
rcon.web      true
```
❓ FAQ
<details> <summary><b>Does it work without the server plugin?</b></summary> Yes. Standard RCON works without any plugins. The plugin only adds building locations on the map. </details><details> <summary><b>Is Steam API Key required?</b></summary> No, but recommended. Without it, VAC status and avatars are unavailable. </details><details> <summary><b>Is RustMaps API Key required?</b></summary> No, but recommended. Without it, the map image won't load. </details><details> <summary><b>Can I run it on multiple PCs?</b></summary> Live edition — yes, any Windows PC. Pro license is hardware-bound to one device. </details><details> <summary><b>Can I modify the software?</b></summary> No. Modification and redistribution are strictly prohibited. See LICENSE.md. </details>

<div align="center">

<br/>

### ⭐ Star this project if you find it useful!

<br/>

Made with ❤️ for Rust server administrators

<br/>

<table>
<tr>
<td align="center">
  <b>🆓 Live Edition</b><br/><br/>
  <a href="https://github.com/ZIZI/RustAdminServer/releases">
    <img src="https://img.shields.io/badge/Download-Free-43B581?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</td>
<td align="center">
  <b>⭐ Pro Edition</b><br/><br/>
  <a href="https://rustadminserver.com/pro">
    <img src="https://img.shields.io/badge/Upgrade-Pro-FFD700?style=for-the-badge&logo=star&logoColor=black"/>
  </a>
</td>
</tr>
</table>

<br/>

[![Discord](https://img.shields.io/badge/Discord-Support-5865F2?logo=discord&logoColor=white)](https://discord.gg/rustadmin)

</div>
