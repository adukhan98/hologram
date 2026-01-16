# ✧ HOLOGRAM ✧

### [Neural Interface v1.0]

A high-performance, single-file interactive particle system that bridges the gap between reality and the cyberpunk meta-verse. Using **Three.js** for WebGL rendering and **MediaPipe Hands** for computer vision, Hologram turns your physical gestures into digital magic.

---

## ⚡ Visual Aesthetics
*   **Immersive AR**: Your webcam feed becomes the background, darkened and processed to integrate you into the interface.
*   **Cyberpunk Core**: Neon cyan HUDs, scanline overlays, and animated grid systems.
*   **Particle Physics**: 12,000 glowing particles with additive blending and snappy linear interpolation physics.

---

## 🖐️ Gesture Commands

### Left Hand: The Command Controller
Capture the interface by extending specific finger counts:
*   ☝️ **1 Finger**: Morph particles into `"Hello"` (Neon Blue)
*   ✌️ **2 Fingers**: Morph particles into `"This"` (Neon Yellow)
*   🤟 **3 Fingers**: Morph particles into `"Is"` (Neon Pink)
*   🖖 **4 Fingers**: Morph particles into `"Magic"` (Neon Green)
*   🖐️ **5 Fingers**: **CATCH MODE** — Prepare for the ultimate formation.

### Right Hand: The Physics Interactor
Interact with the digital field:
*   ✊ **Pointing/Fist**: Scatter text particles with a strong XY repulsion force.
*   🖐️ **Open Hand**: **NEBULA MODE** — Dissolve the text into a chaotic star field with water-ripple disturbances.

### 🌀 The Ultimate Combo
**Both Hands Open simultaneously**: Activates **Ultimate Mode**. All particles are instantly drawn into your left palm to form a rotating, high-energy **3D Basketball** with procedural seam logic and bouncing physics.

---

## 🛠️ Technology Stack
*   **Engine**: Three.js (WebGL)
*   **Vision**: Google MediaPipe Hands
*   **Typography**: Google Fonts (Orbitron)
*   **Structure**: Vanilla HTML5 / ES6 Modules

---

## 🚀 Quick Start
Hologram is entirely self-contained in a single file. No installation required.

1.  Clone the repository:
    ```bash
    git clone https://github.com/adukhan98/hologram.git
    ```
2.  Navigate to the folder and start a local server (required for MediaPipe and Camera access):
    ```bash
    # Using Python
    python3 -m http.server 8080
    ```
3.  Open `http://localhost:8080` in Chrome and grant camera permissions.

---

## ⛓️ Performance Tuning
The system is optimized for **60FPS** interaction. Constants for particle count, return speed, and repulsion strength can be adjusted directly in the `CONFIG` object within the source code.

---
*Created by [Antigravity](https://github.com/google-deepmind) x [adukhan98](https://github.com/adukhan98)*
