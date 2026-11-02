# InfinityCast ♾️ (v2.0.0)

A high-performance, ultra-low-latency Android screen mirroring and PC keymapping engine. InfinityCast bridges the gap between your mobile device and your PC, offering flawless multi-touch gaming, pristine hardware-level audio routing, and a deeply customizable control suite—all without the performance overhead of traditional Android emulators.

---

## ✨ Core Features

* **⚡ Zero-Latency Video Pipeline**  
  Experience buttery-smooth, high-fidelity screen mirroring powered by hardware-accelerated GPU decoding (D3D11VA) and CPU fallback. Built-in aspect-ratio-aware letterboxing preserves exact phone dimensions with zero distortion.

* **🎯 Pixel-Perfect Touch & Multi-Touch Injection**  
  Direct kernel/socket touch injection provides native-level responsiveness. An advanced coordinate translation matrix strips black bars so touches on PC land with 100% pixel accuracy on the phone.

* **🎮 Complete Gaming Keymapping Suite (8 Node Types)**  
  - **Tap**: Instant single-touch binding for any keyboard key.
  - **WASD Joystick**: Smooth 8-directional virtual movement stick *(when omitted, W/A/S/D act as standard keys or script triggers)*.
  - **Left Click Fire**: Specialized shooting node with optional pull-down recoil mitigation.
  - **Freelook (360° Mouse Camera)**: FPS camera control with anti-boundary ratcheting and sensitivity fine-tuning.
  - **Macro (Auto-Clicker)**: Rapid-fire multi-click with custom speed and count.
  - **Script & Target**: Automated multi-touch sequences, timed delays, and loop toggles.
  - **Scroll Wheel**: Maps mouse wheel up/down into directional swipe gestures.

* **🔊 Pristine Hardware Audio Routing & Auto-Mute**  
  Streams crystal-clear, uncompressed internal system audio directly to your PC headphones or speakers. The physical phone speaker is automatically silenced during screen mirroring to prevent echoes and battery drain.

* **🎬 Synchronized MP4 Video & Audio Recording**  
  One-click recording captures H.264 video synchronized with 44.1kHz AAC stereo audio into a standard MP4 file with zero delay. Also supports instant native-resolution screenshots.

* **👁️ High-Contrast Keymap HUD & Alt+X Toggle**  
  High-visibility on-screen button badges with dark pill backgrounds keep key assignments readable over any bright in-game scene. Press **Alt + X** at any moment during gameplay to hide or show the HUD overlays.

---

## 🚀 Download & Installation

1. Navigate to the **[Releases](https://github.com/niraj-hate-dev/InfinityCast/releases)** tab on GitHub.
2. Download `InfinityCast_v2.0.zip` and extract the contents to your PC.
3. Inside the extracted folder, you will find:
   - **`Android_Mobile/InfinityCast.apk`**: Install on your Android phone.
   - **`Windows_PC/InfinityCast.exe`**: Portable PC application (no installation wizard required).

---

## 🎮 How to Connect

1. Enable **Developer Options** on your phone (tap **Build Number** 7 times in Android Settings).
2. Enable **USB Debugging** inside Developer Options.
3. Connect your phone to your PC via a USB data cable.
4. Launch `InfinityCast.exe` on your PC.
5. When prompted on your phone, check *"Always allow from this computer"* and tap **Allow**.
6. Tap **"Start Now"** on the screen projection prompt. InfinityCast connects and mirrors instantly!

> **Auto-Reconnect:** If your USB cable is accidentally unplugged during gameplay, simply plug it back in—your session will automatically resume without restarting the app!

---

## ⚡ Keyboard Shortcuts Quick Reference

| Shortcut | Action |
|:---|:---|
| **`Alt + X`** | Toggle on-screen Keymap HUD (Show / Hide buttons during gameplay) |
| **`Right Click`** | Toggle Freelook Aim Lock (Lock / unlock mouse for 360° camera) |
| **`Ctrl + X`** | Toggle Mouse Capture in Mirror Mode (Full phone navigation) |
| **`F11`** | Toggle Borderless Fullscreen display |
| **`Arrow Keys`** | Live Freelook sensitivity adjustments while aiming |

---

## 📸 Screenshots

**1. Main InfinityCast PC Window**  
<img width="959" height="502" alt="image" src="https://github.com/user-attachments/assets/8413a8a3-96db-4a7b-96c7-1405b4c87cce" />

**2. InfinityCast Keymapper Editor**  
<img width="953" height="487" alt="image" src="https://github.com/user-attachments/assets/c19b7584-f366-433c-a1b6-c7c68d9824e5" />

**3. Main InfinityCast Android App**  
<img width="1080" height="2200" alt="image" src="https://github.com/user-attachments/assets/a5511e0d-aea3-4a1e-bb3e-382a2350c6fc" />
