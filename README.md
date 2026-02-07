# 🕹️ RetSOL GBA: Yellow Recharged Edition

**The Ultimate Cloud-Injected GBA Experience for Play Solana (PSG1).**

RetSOL v5.5 is a specialized, web-based Game Boy Advance emulator designed specifically to bypass the strict file-system security of handheld gaming devices. Instead of relying on local file pickers that often "grey out" ROMs, RetSOL v5.5 uses **Direct-Raw Injection** to stream games directly from your GitHub repository into the emulator's engine.

---

## 🚀 Key Features

* **⚡ Direct-Raw Boot**: Bypasses the PSG1 file picker entirely by fetching `yellowrecharged.gba` directly from the GitHub main branch.
* **🔊 Audio-Kickstart**: Automatically unlocks the browser's AudioContext to prevent the common "Black Screen" hang found in web emulators.
* **🎨 Synthwave UI**: Neon-soaked yellow and pink aesthetic tuned specifically for the PSG1's high-contrast display.
* **🏠 Hub Integration**: Seamless navigation back to the RetSOL Gaming Hub.

---

## 🛠️ Installation & Setup

To play your legal backup of **Yellow Recharged**, follow these exact steps:

1.  **Repository Alignment**: Ensure your `index.html` and `yellowrecharged.gba` are in the **same folder** on your `main` branch.
2.  **Raw Link Configuration**: The `index.html` is pre-configured to look for the file at your RetsolGaming repository path.
3.  **Deployment**: 
    * Commit both files to the **main** branch.
    * Wait for the **GitHub Actions** tab to show a green checkmark (usually takes 1-3 minutes).
4.  **Play**: Open the site on
