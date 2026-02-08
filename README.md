# 🎮 RetSOL GBA v3.0 - Universal Handheld
A high-compatibility, low-latency Game Boy Advance core optimized for mobile browsers and portable gaming handhelds.

## 🚀 Key Features
* **Zero-BIOS Engine**: High-level emulation allows for instant booting without external BIOS files.
* **Handheld UI**: Touch-ready grid menu designed for 4:3 and 16:9 portable screens.
* **Persistent States**: Save and Load game progress directly to browser LocalStorage.
* **Sharp Scaling**: Optimized pixel-rendering to prevent blur on high-density displays.

## 🕹️ Setup
1. **Launch**: Open this page on your handheld's browser.
2. **Inject**: Tap `🎮 LOAD GBA GAME` to pick a `.gba` file from your device.
3. **Save/Load**: Use the `💾 QUICK SAVE` button to store your current frame. Use `📂 QUICK LOAD` to resume instantly.

---

## 🛠️ Technical Overview
| Spec | Detail |
| :--- | :--- |
| **Core** | gbajs2 (Stable) |
| **Output** | WebGL Canvas |
| **Saves** | LocalStorage (JSON Encoded) |
| **Controls** | Web Gamepad API |

[Back to Hub](https://retsolgaming.github.io/RetSOL-Hub/)
