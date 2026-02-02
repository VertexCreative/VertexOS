# VERTEX OS 5.0 | Professional Edition 💼

![Version](https://img.shields.io/badge/VERSION-5.0.0_PRO-007AFF?style=for-the-badge)
![Status](https://img.shields.io/badge/STATUS-ENTERPRISE_READY-000000?style=for-the-badge)
![License](https://img.shields.io/badge/LICENSE-MIT-ffffff?style=for-the-badge)

## 📂 Overview

**Vertex OS 5.0** is the ultimate iteration of the Vertex Creative web operating system. Moving beyond visual aesthetics, this version introduces **functional state logic**, a system-wide notification engine, and a "Mica" material design language inspired by professional desktop environments.

> **CEO Note:** "We removed the 'junior developer' feel. Every button clicks, every toggle works, and every interaction provides system feedback." — *Fahad Malik, Founder*

---

## ✨ Pro Features (v5.0)

### 💠 Visual Intelligence
* **Mica Material:** Advanced glassmorphism using `backdrop-filter: blur(50px)` for a deep, premium feel.
* **Dynamic Desktop:** The wallpaper reacts to UI states (scaling and blurring when menus are active).
* **Toast Engine:** A built-in notification system that alerts users when hardware (Wi-Fi/Bluetooth) states change.

### ⚙️ Functional Shell
* **Real Search:** Type in the Start Menu to filter installed apps instantly.
* **Quick Settings:** Functional Wi-Fi and Bluetooth toggles that simulate connection states.
* **Context Menu:** Custom right-click menu for system refresh and fullscreen modes.
* **Taskbar Logic:** Clicking an active app icon minimizes or restores the window, mirroring real OS behavior.

### 🪟 Window Management
* **State Memory:** Windows remember their previous size/position when restoring from minimize.
* **Focus Engine:** Active windows glow and rise to the top Z-index.
* **Drag Physics:** Smooth, constraint-aware window movement.

---

## 📦 The App Suite

Vertex OS 5.0 includes the complete **Vertex Creative Toolset**:

| App Icon | App Name | Description |
| :---: | :--- | :--- |
| 🛡️ | **PassForge** | Entropy-based password security engine. |
| ⬛ | **QR-X** | Vector QR code generator. |
| 🎨 | **Lumix Pro** | Chromatic color palette studio. |
| ⌨️ | **Type-X** | WPM productivity accelerator. |
| 🎯 | **RefleX** | Esports reaction time trainer. |
| 🌌 | **Gravitas** | Particle physics sandbox. |
| 🎞️ | **Kinetix** | CSS animation motion studio. |
| 🧠 | **SeQ-X** | Cognitive pattern memory trainer. |

---

## 🛠️ Installation & Architecture

**⚠️ CRITICAL SETUP INSTRUCTIONS:**
This system uses `<iframe>` architecture. Due to browser security policies (CORS), it **must** be run on a server.

### 1. Folder Structure
Ensure your directory matches this **exact** layout:

```text
/VertexOS
  ├── index.html        (The Main OS Kernel)
  ├── README.md
  └── app/              <-- NOTE: Folder name is singular "app"
       ├── passforge.html
       ├── qrx.html
       ├── lumixpro.html
       ├── typex.html
       ├── reflex.html
       ├── gravitas.html
       ├── kinetix.html
       └── seqx.html
