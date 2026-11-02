# InfinityCast ♾️ (v2.0.0)

[![Release](https://img.shields.io/badge/Release-v2.0.0-blue.svg)](https://github.com/niraj-hate-dev/InfinityCast/releases)
[![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Android-green.svg)](https://github.com/niraj-hate-dev/InfinityCast)

**InfinityCast** is an ultra-low-latency Android-to-PC screen mirroring, desktop remote control, and competitive mobile gaming engine. It connects your Android device to your Windows PC over a high-speed USB pipeline, offering native-level multi-touch control and a deeply customizable keymapping suite—**all without the performance overhead or lag of traditional Android emulators.**

---

## 📌 What is InfinityCast Used For?

1. **🔴 100% Free Live Streaming (Zero Cost for Mobile Streamers)**:  
   Stream mobile games directly to **YouTube, Twitch, Facebook Gaming, or Kick** through **OBS Studio, Streamlabs, or Prism Live Studio** without buying expensive capture cards (like Elgato) or paying for costly subscription software. Simply add the InfinityCast window into OBS via *Window Capture* for ultra-smooth 60 FPS streaming—completely free, with **zero watermarks and no time limits!**
2. **🎮 Competitive Mobile Gaming on PC**: Play mobile games (BGMI, PUBG Mobile, Free Fire, Call of Duty Mobile, Genshin Impact) using your PC's physical keyboard and mouse with 360° camera freelook, zero recoil drift, and customizable macros.
3. **⚡ Lag-Free Screen Mirroring**: Mirror your phone's display in real-time at up to 60+ FPS with ultra-low latency for presentations, demonstrations, or watching content on a big screen.
4. **🖥️ Full Desktop Remote Control (Mirror Mode)**: Use your PC keyboard to type in messaging apps, fill forms, and browse apps using your physical mouse cursor.
5. **🎬 Gameplay Recording & Screenshots**: Record high-definition gameplay video directly to an `.mp4` file or take instant native-resolution screenshots without third-party software.

---

## 🌟 What's New in Version 2.0.0 (Old vs. New)

| Feature / Area | 🔴 Version 1.0.0 (Legacy) | 🟢 Version 2.0.0 (Current) |
|:---|:---|:---|
| **Phone Remote Control** | Only basic gaming keys supported | **Native Mirror Mode**: Full PC keyboard typing & mouse capture (`Ctrl + X`) |
| **Automation & Rapid Click** | None (only single tap per press) | **Macro Node**: Configurable high-speed auto-clicker for single-fire weapons |
| **Multi-Touch Combos** | None | **Script & Target**: Multi-touch sequences with millisecond timers & loops |
| **Mouse Wheel Input** | Ignored by keymapper | **Scroll Node**: Mouse scroll wheel converted into directional touch swipe gestures |
| **Long-Range Aiming** | Standard video display only | **Precision Zoom**: Built-in zoom crosshair for sniping and close inspections |
| **Updates & Versioning** | Manual checking | **In-App Update Checker**: One-click check inside About window to GitHub tags |
| **In-Game HUD Overlays** | Buttons always visible on screen | **`Alt + X` Hotkey**: Instantly hide/show buttons on the fly during matches |
| **Node Visibility** | Faint, hard to see on bright skies/maps | **High-Contrast Design**: Bold borders & dark contrast pill text badges |
| **Touch Precision** | Touches were slightly offset on wide screens | **Pixel-Perfect Translation**: Exact coordinate mapping with letterboxing support |
| **WASD Flexibility** | W, A, S, D blocked other bindings | **Conditional WASD**: W/A/S/D act as standard keys/scripts if joystick is omitted |
| **User Documentation** | Basic 4 sections | **Interactive User Guide**: 6 detailed sections with hotkey tables and pro tips |

---

## 🎮 Complete Feature Overview

### 1. ⚡ High-Performance Zero-Latency Video Engine
- **Hardware-Accelerated Streaming**: Smooth, high-fidelity screen mirroring with dynamic decoding.
- **Aspect-Ratio-Aware Letterboxing**: Adapts cleanly to any phone screen aspect ratio so gameplay never stretches or distorts.
- **Configurable Quality**: Supports up to 60 FPS streaming for buttery-smooth responsiveness.

### 2. 🎯 Precision Multi-Touch & 8 Keymapping Node Types
Built directly into the visual drawer editor:
- **`TAP` (Single Key)**: Maps any keyboard key to an instant screen touch point.
- **`JOYSTICK_WASD` (Virtual Stick)**: Smooth 8-directional analog movement stick with configurable radius. *(If removed, W/A/S/D automatically revert to normal keys or script triggers)*.
- **`LEFT_CLICK_FIRE` (Shooting Trigger)**: Binds mouse Left-Click to shooting with built-in pull-down recoil mitigation.
- **`AIM_PAN / FREELOOK` (360° Mouse Camera)**: Seamless FPS mouse look with anti-boundary ratcheting so your camera never locks at the edge of the screen.
- **`FREELOOK_V2` (High-Visibility FPS Controller)**: Vivid camera controller with on-the-fly arrow key sensitivity tuning.
- **`MACRO` (Auto-Clicker)**: Rapid-fire tapping for semi-auto rifles or spam clicks. Right-click to adjust repeat count and interval (ms).
- **`SCRIPT & SCRIPT_TARGET` (Automation Combo)**: Multi-touch combos (e.g., weapon switch + crouch + shoot) with custom delays and loop support.
- **`SCROLL` (Mouse Wheel Swipe)**: Maps mouse wheel up and down to smooth vertical touch swipes for browsing menus and weapon wheels.

### 3. 🖥️ Mirror Mode (PC Desktop Control)
- Toggle mouse capture with **`Ctrl + X`** to operate your phone exactly like a computer.
- Type in messaging apps, fill forms, or browse with your physical PC keyboard and mouse.

### 4. 🎬 MP4 Screen Recording & Screenshots
- **One-Click Recording**: Record your gameplay directly into a clean `.mp4` video file.
- **Native-Resolution Screenshot**: Takes full-resolution screenshots saved directly to your chosen folder.

### 5. 👁️ High-Contrast Keymap HUD & Alt+X Toggle
- High-visibility semi-transparent buttons with dark background pills behind key letters keep buttons readable over any game environment.
- Press **`Alt + X`** at any moment during gameplay to hide all buttons for a clean screen, and press **`Alt + X`** again to bring them back.

### 6. 🔌 Bulletproof Auto-Reconnect
- If your USB cable is accidentally unplugged during a match, simply plug it back in—InfinityCast automatically reconnects and resumes your session immediately.

---

## 🚀 Download & Installation

In the **[GitHub Releases](https://github.com/niraj-hate-dev/InfinityCast/releases)** page, you will find two files:

### 📱 1. Android Phone Setup
1. Download **`InfinityCast.apk`**.
2. Transfer and install the APK on your Android phone (Android 10 or higher).
3. Open the app and grant the requested permissions.

### 💻 2. Windows PC Setup
1. Download **`Windows_PC.zip`**.
2. Right-click `Windows_PC.zip` and select **Extract All**.
3. Open the extracted `Windows_PC` folder.
4. Double-click **`InfinityCast.exe`** to launch the software.  
   *(Completely portable—no installation wizard required! Everything you need is bundled inside).*

---

## 🎮 How to Connect (Step-by-Step)

1. **Enable Developer Options on your phone**:
   - Go to phone **Settings > About Phone**.
   - Tap **Build Number** 7 times until you see *"You are now a developer!"*.
2. **Enable USB Debugging**:
   - Open **Settings > System > Developer Options**.
   - Toggle **USB Debugging** to **ON**.
3. **Connect to PC**:
   - Connect your phone to your PC using a reliable USB data cable.
4. **Launch InfinityCast**:
   - Double-click `InfinityCast.exe` on your PC.
5. **Authorize Connection**:
   - A prompt will appear on your phone screen: *"Allow USB debugging?"*.
   - Check **"Always allow from this computer"** and tap **Allow**.
6. **Start Casting**:
   - Tap **"Start Now"** on the Android screen projection prompt.
   - Your phone display will instantly appear on your PC!

---

## ⚡ Keyboard Shortcuts Quick Reference

| Shortcut | Mode | Description |
|:---|:---:|:---|
| **`Alt + X`** | Global / In-Game | **Toggle Keymap HUD**: Instantly show or hide floating button overlays |
| **`Right Click`** | Freelook Mode | **Lock / Unlock Mouse**: Captures mouse cursor for 360° camera rotation |
| **`Ctrl + X`** | Mirror Mode | **Capture / Release Mouse**: Switch between desktop cursor and phone control |
| **`F11`** | Global | **Toggle Fullscreen**: Switch between windowed and borderless fullscreen |
| **`Arrow Up / Down`** | Aim Lock Active | **Y-Axis Sensitivity**: Increase or decrease camera vertical sensitivity |
| **`Arrow Left / Right`** | Aim Lock Active | **X-Axis Sensitivity**: Increase or decrease camera horizontal sensitivity |

---

## 🛠️ Keymapping Editor Guide

1. Click **Editor** in the left sidebar to open the drawer.
2. **Placing Nodes**: Drag any widget from the drawer onto the game screen.
3. **Binding Keys**: Click on a placed node and press any keyboard key to bind it.
4. **Configuring Nodes**: Right-click on a node to open its configuration menu:
   - *Tap*: Adjust radius size.
   - *Macro*: Configure click speed interval (ms) and max clicks.
   - *Script*: Edit touch sequence coordinates, delays, and loop mode.
   - *Freelook*: Tune independent horizontal and vertical sensitivities.
5. **Deleting Nodes**: Click the small **X** icon in the corner of any selected node.
6. **Saving**: Click **Save Map** to apply changes and close the editor.

---

## 🔧 Troubleshooting & FAQ

#### ❓ Phone not detected by InfinityCast?
- Ensure your cable supports **data transfer**, not just charging.
- Verify that **USB Debugging** is turned ON in Developer Options.
- Try toggling USB connection mode from *Charging Only* to *File Transfer / MTP*.

#### ❓ Touches are not registering in games?
- Ensure the **InfinityCast Accessibility Service** is enabled in phone **Settings > Accessibility > Installed Apps > InfinityCast**.
- For Xiaomi/POCO/Redmi devices: Enable **"USB Debugging (Security settings)"** in Developer Options.

---

## 📸 Screenshots

**1. Main InfinityCast PC Window**  
<img width="959" height="502" alt="image" src="https://github.com/user-attachments/assets/8413a8a3-96db-4a7b-96c7-1405b4c87cce" />

**2. InfinityCast Keymapper Editor**  
<img width="953" height="487" alt="image" src="https://github.com/user-attachments/assets/c19b7584-f366-433c-a1b6-c7c68d9824e5" />

**3. Main InfinityCast Android App**  
<img width="1080" height="2200" alt="image" src="https://github.com/user-attachments/assets/a5511e0d-aea3-4a1e-bb3e-382a2350c6fc" />
