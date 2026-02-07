# 💿 RetSOL PSX: Cloud-Direct Edition

**High-Performance PlayStation 1 Emulation for Play Solana (PSG1).**

RetSOL PSX v5.5 is a specialized web-emulator built to bypass the "Greyed Out" file restrictions on handheld browsers. By linking directly to your hosted `.bin` or `.iso` files, this engine injects the game data directly into the system RAM, bypassing the need for a local file picker.

---

## 🚀 Key Features

* **🛰️ Direct-Link Injection**: Loads games via official GitHub Pages URLs to avoid CORS and "Network Error" blocks.
* **🎮 Handheld Optimized**: Pre-mapped controls for the PSG1 (Square, Cross, Triangle, Circle).
* **📺 Retro Aesthetic**: Neon-pink "System Secure" UI designed for high-contrast visibility on mobile screens.
* **🏠 Hub-Ready**: Built-in navigation to return to the RetSOL Gaming Hub.

---

## 🛠️ Installation & Setup

Because PS1 files are significantly larger than GBA files, follow these steps carefully:

1.  **File Management**: Upload your `.bin`, `.iso`, or `.exe` file to your repository. 
    * *Note: GitHub has a 100MB limit for standard uploads. For larger games, use Git LFS or a smaller "Compressed" bin.*
2.  **Deployment**: 
    * Ensure your game file is on the **main** branch.
    * Wait for the GitHub Actions deployment (the green checkmark).
3.  **Booting**: Open the app on your PSG1 and tap the **💿 LOAD PSX DISC** button.

---

## 🎮 Controls (PSG1 Mapping)

| PS1 Button | Keyboard Map |
| :--- | :--- |
| **D-Pad** | Arrow Keys |
| **Triangle / Circle** | D / X |
| **Cross / Square** | Z / S |
| **L1 / R1** | W / R |
| **L2 / R2** | E / T |
| **Select / Start** | C / V |

---

## ⚠️ Troubleshooting

* **Black Screen/Loading**: PS1 games take longer to "Fetch" than GBA games due to size. Give the status bar at least 30-60 seconds to process the bytes.
* **"Network Error"**: This happens if the GitHub Pages deployment isn't finished. Refresh the page and try again after 2 minutes.
* **Double-Tap**: On the PSG1, you may need to tap the screen once to "Focus" the controls before the buttons respond.

---

**Developed by RetsolGaming for the Play Solana handheld community.**
