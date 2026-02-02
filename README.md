# VERTEX OS 4.0 | Aero Edition 💠

![Version](https://img.shields.io/badge/VERSION-4.0.0_AERO-3b82f6?style=for-the-badge)
![Status](https://img.shields.io/badge/STATUS-STABLE-00ff41?style=for-the-badge)
![License](https://img.shields.io/badge/LICENSE-MIT-ffffff?style=for-the-badge)

## 📂 Overview

**Vertex OS 4.0** is a next-generation web-based operating system designed by **Vertex Creative**. It bridges the gap between desktop and web by implementing a full window management system, taskbar logic, and a high-end "Aero" aesthetic inspired by Windows 11 and One UI.

> **Design Philosophy:** "Glass, Light, and Motion." Every element features real-time acrylic blur (`backdrop-filter`), squircle iconography, and fluid 60FPS animations.

---

## ✨ System Features

### 🖥️ Desktop Environment
* **Mica Effect:** Real-time glassmorphism on windows, taskbars, and menus.
* **Dynamic Wallpaper:** Background scales and blurs when menus are active (Depth Effect).
* **Fluid Animations:** All transitions utilize `cubic-bezier` curves for ultra-smooth motion.

### 🪟 Window Manager
* **Multi-Tasking:** Open multiple apps simultaneously.
* **Controls:** Minimize, Maximize, and Close logic with state memory.
* **Focus Engine:** Clicking a window brings it to the Z-index foreground.
* **Drag & Drop:** Physics-based window movement.

### 🚀 Shell Interface
* **Center Taskbar:** Floating dock with dynamic active indicators.
* **Start Menu:** Blurred app drawer with "Pinned Apps" and search.
* **Control Center:** iOS/One UI style quick settings for Wi-Fi, Bluetooth, and Brightness.

---

## 📦 The App Ecosystem

Vertex OS comes pre-installed with the **Nexus Suite**, a collection of serverless professional tools:

| App Name | Description | Category |
| :--- | :--- | :--- |
| **PassForge** | Military-grade password generator with entropy visualization. | Security |
| **QR-X** | High-density QR code generator with vector export. | Utility |
| **Lumix Pro** | Chromatic intelligence engine for color palette generation. | Design |
| **Type-X** | Gamified WPM typing accelerator and test. | Productivity |
| **RefleX** | Esports-grade aim and reaction time trainer. | Gaming |
| **Gravitas** | Particle physics sandbox with Newtonian gravity logic. | Simulation |
| **Kinetix** | GUI-based CSS keyframe animation generator. | Dev Tool |

---

## 🛠️ Installation & Setup

### Folder Structure
Ensure your directory looks exactly like this:
```text
/VertexOS
  ├── index.html        (The Main OS File)
  ├── README.md
  └── apps/             (Subfolder containing all tools)
       ├── passforge.html
       ├── qrx.html
       ├── lumix.html
       ├── typex.html
       ├── reflex.html
       ├── gravitas.html
       └── kinetix.html
