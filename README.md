# MChip-Monitor (Silicon Widgets) 🐱🖥️

![Platform](https://img.shields.io/badge/Platform-macOS%2012%2B-lightgrey)
![Architecture](https://img.shields.io/badge/Architecture-Apple%20Silicon%20(M1%2FM2%2FM3)-blue)
![License](https://img.shields.io/badge/License-Free-green)
[![Downloads](https://img.shields.io/github/downloads/lovepc605/MChip-Monitor-App/total?style=flat-square&logo=github&color=blue)](https://github.com/lovepc605/MChip-Monitor-App/releases)

MChip-Monitor (Silicon Widgets) is a beautiful, healing, and highly functional **Desktop Pet + System Component Monitor** built exclusively for macOS running on Apple Silicon (arm64). It brings your system stats to life with interactive pets, modular widgets, and a rich, customizable UI.

### Sign and Upload to Apple (Notarize) on 2026.04.01

---

## 📸 Preview

![MChip Monitor Overview](MChip-Monitor%20v1.5.3.jpg)

### 🎥 Watch it in Action

![MChip Monitor Demo](MChip%20Monitor%20v1.5.3.gif)

You can also watch the full resolution demo here:  
**🔗 [MChip-Monitor Demo Video](MChip-Monitor.mp4)**

---

## ✨ Key Features

### 🐾 Healing Desktop Pet System
Why look at cold, boring numbers when you can have a desktop pet that reacts to your Mac's performance? 
- Your pet sleeps when the CPU is idle (< 20%).
- Works hard when usage goes up (21% - 69%).
- Sweats and warns you when under extreme load (> 90%).
- *Click the pet for a friendly chat bubble with real-time system stats!*

### 📊 Comprehensive System Monitoring
Keep track of everything, beautifully integrated into your desktop.
- **CPU & GPU**: Usage tracking with historical line charts and detailed hardware spec inspection.
- **Memory (RAM)**: Real-time pressure, Wired/Active/Inactive distribution, and usage charts.
- **Thermometer Widget**: Vertical standalone thermometer visualizing CPU & Battery temperatures (°C/°F) with dynamic color warnings (> 80°C).
- **Network Stats**: Dual-line charts showing live Download (Green) and Upload (Red) speeds, Wi-Fi SSID, and connection quality.

### 🧩 Modular Widget Architecture
Tailor your desktop exactly how you want it. Widgets are draggable, resizable (400px to 800px), and automatically remember where you placed them across multiple displays.
1. **System Utilization Widget**: The core CPU/GPU/RAM/Network dashboard.
2. **User Actions Widget**: Development shortcuts at your fingertips.
   - **Tools**: One-click update for Homebrew, npm, and pip.
   - **Cleanup**: Instantly reclaim disk space by clearing Xcode DerivedData, Caches, DeviceSupport, IDE caches, etc.
   - **Network**: Quick VPN toggle and speed tests.
3. **Thermometer Widget**: A beautifully designed vertical temperature gauge.
4. **Disk Analyzer Widget**: Smartly categorizes your entire drive (Images, Videos, LLM Models, Git Repos, Archives) and lists the Top 10 largest files to help you find space hogs.

### 🎨 Beautiful Themes & UI Customization
Match your monitor to your mood. Change themes dynamically via the settings menu.
- **Supported Themes**: Cyberpunk, Matrix, Medieval Castle, Imperial Dynasty, Win95/Win2000 Retro, and more!
- Adjust opacity, background colors, and arrangement styles (Vertical, Horizontal, or Grid).

### 🚀 Auto-Updates via Sparkle
MChip-Monitor natively integrates with the Sparkle framework. You will seamlessly get automatic background updates pulling from GitHub Releases.

---

## ⚙️ System Requirements

- **Processor**: Apple Silicon Only (M1, M1 Pro/Max/Ultra, M2, M3 series).
- **OS**: macOS 12 Monterey or newer (optimized for macOS 14 Sonoma widget placements).

---

## 📥 Installation

1. Go to the [Releases page](../../releases) to download the latest version.
2. Or download the latest archive directly:
3. Extract the `.zip` file.
4. Drag `MChip-Monitor.app` into your **Applications** folder.
5. Launch the app and follow the setup wizard to grant the requested permissions (Network, Disk access).

---

## 🛠️ Developer / Contribute

MChip-Monitor is built purely using Swift/SwiftUI and Metal APIs exclusively for Apple Silicon architectures. To run or compile locally:
1. Clone the repository.
2. Open the project in Xcode (Ensure your target is set to `arm64`).
3. Build and Run on a local machine. *Note: You cannot run this on an Intel-based Mac simulator.*

For more architectural details and design specifications, refer to the `Doc/` folder in the repository!

---

> *"Making system monitoring a healing and fun experience, rather than just staring at cold numbers."* 🐱💻
