# VERTEX OS 5.2 | Enterprise Architect Edition 🏛️

![Version](https://img.shields.io/badge/VERSION-5.2.0_ENT-007AFF?style=for-the-badge)
![Status](https://img.shields.io/badge/STATUS-PRODUCTION-000000?style=for-the-badge)
![License](https://img.shields.io/badge/LICENSE-MIT-ffffff?style=for-the-badge)

## 📂 Executive Summary

**Vertex OS 5.2** is a professional-grade web operating system designed by **Vertex Creative**. It simulates a full desktop environment within the browser using advanced DOM manipulation and `iframe` architecture.

This edition features a **centralized kernel configuration**, allowing for instant rebranding (Logos, Usernames) and includes intelligent state management for window restoration, minimization, and visitor detection.

---

## ✨ Enterprise Features

### 💠 Intelligent Branding Engine
* **Central Config:** A single code block controls the Organization Name, Logo, and User Identity.
* **Auto-Adaptive Graphics:** The system automatically processes your raw logo URL, converting it into a **Squircle** for the Bootloader and a **Perfect Circle** for the User Profile.
* **Visitor Protocol:** The system distinguishes between the "System Owner" (displayed in About) and the "Current Session" (displayed as Guest User).

### ⚙️ The "Mica" Shell
* **Glassmorphism 2.0:** Deep blur effects (`backdrop-filter: blur(40px)`) on all system panels.
* **Window State Logic:** Windows correctly save their state. Clicking a Taskbar icon toggles between **Focus**, **Minimize**, and **Restore** (fixing previous Z-index layering issues).
* **Notification Engine:** A non-intrusive "Toast" system alerts users to hardware changes (Wi-Fi/Bluetooth toggles) and system events.

### 🚀 Application Suite
Includes the full **Vertex Creative Toolset** (Serverless Architecture):

| App | Name | File Path | Function |
| :---: | :--- | :--- | :--- |
| 🛡️ | **PassForge** | `app/passforge.html` | High-entropy password security. |
| ⬛ | **QR-X** | `app/qrx.html` | Vector QR generation. |
| 🎨 | **Lumix Pro** | `app/lumixpro.html` | Chromatic palette studio. |
| ⌨️ | **Type-X** | `app/typex.html` | WPM productivity trainer. |
| 🎯 | **RefleX** | `app/reflex.html` | Esports reaction engine. |
| 🌌 | **Gravitas** | `app/gravitas.html` | Particle physics sandbox. |
| 🎞️ | **Kinetix** | `app/kinetix.html` | CSS motion generator. |
| 🧠 | **SeQ-X** | `app/seqx.html` | Cognitive pattern trainer. |

---

## 🛠️ Deployment & Architecture

**⚠️ CRITICAL REQUIREMENT:**
This system relies on cross-origin `<iframe>` loading. You **cannot** simply double-click `index.html`. You must atleast use a local server.

### 1. File Structure Strategy
Ensure your directory matches this **exact** layout to prevent 404 errors:

```text
/VertexOS
  ├── index.html          (The Master Kernel)
  ├── README.md           (Documentation)
  └── app/                <-- NOTE: Folder name is singular "app"
       ├── passforge.html
       ├── qrx.html
       ├── lumixpro.html  <-- NOTE: Filename is "lumixpro.html"
       ├── typex.html
       ├── reflex.html
       ├── gravitas.html
       ├── kinetix.html
       └── seqx.html
