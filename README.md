# 💿 RetSOL PSX v5.1 - BETA

The high-performance PlayStation 1 (PSX) portal for the Play Solana (PSG1). This emulator uses a specialized iframe-injection method to bypass handheld browser security blocks, allowing for full hardware-accelerated 3D rendering.

## 🚀 Features
* **Zero-Config Engine**: Powered by the stable `lrusso` core with built-in BIOS.
* **Handheld Focus**: Includes an emergency touch-fix script to ensure the PSG1 browser maintains focus on the game frame.
* **Auto-Gamepad Support**: Detects physical controllers and PSG1 inputs automatically upon iframe focus.
* **Secure Sandbox**: Runs in a protected container to prevent browser crashes during high-resource gameplay.

---

## 🕹️ How to Use
1. **Initialize**: Launch this page on your PSG1.
2. **Focus Engine**: Tap the game screen area once. This "wakes up" the emulator and connects your physical buttons.
3. **Load ISO**: Use the engine's internal "Load File" icon to select your `.iso`, `.bin`, or `.cue` files from your device.
4. **Reboot**: If the frame freezes, use the pink **REBOOT ENGINE** button at the bottom to clear the cache and restart the system.

## 📺 Performance Tips
* **Memory Management**: For the best frame rates, close all other tabs in the PSG1 browser before starting.
* **Audio Context**: If the sound is crackling, tap the reboot button—this resets the WebAudio handshake.

---

## 🛠️ System Architecture
| Component | Status |
| :--- | :--- |
| **Core Engine** | lrusso-PSX (WASM Optimized) |
| **Iframe Layer** | Enabled (Secure Context) |
| **Touch-Mapping** | v5.1 Focus-Fix Integrated |
| **BIOS** | Pre-loaded / Embedded |

**Developed for the RetSOL Gaming Hub.** [Back to Hub](https://retsolgaming.github.io/RetSOL-Hub/)
