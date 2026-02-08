# 🎮 RetSOL GBA v10.0 - Lite Engine

Welcome to the **RetSOL Lite** Game Boy Advance emulator. This version is stripped of all "Cloud Lag" and heavy network requests to provide the smoothest possible experience on handheld browsers like the **PSG1**.

## 🚀 Why this version?
* **Zero-Network Latency**: No more waiting for GitHub to "publish" your files.
* **Ultra-Low RAM**: Uses a specialized WASM-based engine (IodineGBA) for high performance.
* **CRT Scanlines**: Real-time visual filter for that authentic retro glow.
* **Privacy**: Your games are loaded locally; nothing is uploaded to a server.

---

## 🕹️ How to Play
1.  **Launch**: Open this page in your PSG1 browser.
2.  **Select Game**: Click the `🎮 OPEN GBA FOLDER` button.
3.  **Inject**: Choose any `.gba` file from your device's internal storage or SD card.
4.  **Audio**: If the game doesn't make sound immediately, tap the screen once to "Unlock" the browser's audio engine.

## 📺 Features & Controls
* **CRT Toggle**: Tap the `📺 CRT` button to turn scanlines on or off. This uses zero extra CPU power.
* **Pause/Resume**: Use the physical buttons or on-screen menu to halt the engine.
* **Universal Compatibility**: Works on any device that supports a modern browser.

---

## 🛠️ Technical Specs
| Feature | Implementation |
| :--- | :--- |
| **Engine** | IodineGBA (WASM-Lite) |
| **Rendering** | Pixel-Perfect Canvas |
| **Memory** | <128MB RAM footprint |
| **Audio** | WebAudio API (Synchronous) |

**Developed for the RetSOL Gaming Hub.**
[Back to Hub](https://retsolgaming.github.io/RetSOL-Hub/)
