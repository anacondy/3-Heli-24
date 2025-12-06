# Vector Chopper 3D

A retro-style 3D helicopter game with vector graphics, floaty physics, and full mobile support. Navigate through procedurally generated terrain while avoiding obstacles, birds, and dragons!

## 🎮 Play Now
**[Play Vector Chopper](https://anacondy.github.io/3-Heli-24/)**

## Screenshots

### Desktop 16:9 - Main Menu
![Desktop Main Menu](https://github.com/user-attachments/assets/1cca38ea-6fd9-48cc-b00e-b69d39fb0b52)

### Desktop 16:9 - Game Over Screen (with Level Display)
![Desktop Game Over](https://github.com/user-attachments/assets/63cb66fe-385d-4ba4-a23d-8adad18b88a6)

### Desktop 16:9 - Gameplay
![Desktop Gameplay](https://github.com/user-attachments/assets/196f8869-a0b5-49ef-885b-9fa9c321a4c9)

> **Note:** Mobile devices are required to play in **landscape mode only**. When accessing the game in portrait mode on mobile, a "Rotate Your Device" overlay will appear prompting users to rotate their device for the best experience.

## ✨ Features

### Graphics & Visual
- 🎮 **3D-style helicopter** with animated rotors
- 🌟 Dynamic starfield with parallax depth effect
- ✨ Particle effects and glow shaders
- 📺 Retro scanline overlay for authentic vector feel
- 💥 Screen shake on crash for impact feedback
- 🐉 **Dragon obstacles** with animated wings and fire breath

### Mobile Support
- 📱 **Fully responsive** design for all screen sizes
- 📐 Optimized for **16:9** and **20:9** aspect ratios in landscape
- 👆 Touch-friendly controls with visual feedback
- 🔒 Safe area support for notched devices (iPhone X+, Android)
- 🖥️ **Landscape-only mode** - game only runs in landscape orientation
- 📲 "Rotate Your Device" overlay blocks gameplay in portrait mode

### Performance
- ⚡ **Supports 60Hz, 90Hz, 120Hz, and 144Hz** displays
- 🎯 Runs at native display refresh rate
- 📊 Real-time FPS counter in HUD
- 🔧 Delta-time physics for consistent gameplay at any frame rate
- 🖼️ High DPI display support with device pixel ratio optimization

### Audio
- 🎵 Dynamic rotor sound with throttle response
- 💥 Explosion sound effects
- 🐦 Bird strike audio feedback
- 🔇 **Audio fades out smoothly** on crash (0.4s fade effect)
- 🔊 Mute/unmute with visual feedback

### Gameplay
- 🚁 Floaty helicopter physics
- 🌄 Procedurally generated terrain
- 🐦 Birds as dynamic obstacles
- 🐉 **Dragons** spawn at Level 2+ with fire breath attacks
- 📈 **Progressive difficulty** system (up to Level 10)
- ⏸️ Pause/resume functionality
- 🏆 Distance scoring with level display

## 🎮 Controls

### Desktop (Keyboard)
| Key | Action |
|-----|--------|
| W / ↑ / Space | Fly Up |
| S / ↓ | Dive Down |
| P / Enter | Pause/Resume |
| M | Mute/Unmute |
| Enter / Space | Start Game |

### Mobile / Touch
- **Tap & Hold Anywhere**: Fly up
- **Release**: Fall down
- **Touch Zone Button**: Visual feedback area (bottom-right)

## 🛠️ Technical Details
- **Rendering**: HTML5 Canvas 2D with 3D-style effects (parallax stars, depth shading)
- **Audio**: Web Audio API with pink noise synthesis
- **Physics**: Delta-time based for consistent behavior across frame rates
- **Mobile**: CSS viewport units, safe-area-insets, touch events
- **Dependencies**: None (pure HTML/CSS/JS)

## 📅 Automated Updates & Deployment
This game is automatically tested, updated, and deployed via GitHub Actions:

### Continuous Deployment
- **Auto-deploy**: Site deploys automatically when changes are merged to `main`
- **Live URL**: [https://anacondy.github.io/3-Heli-24/](https://anacondy.github.io/3-Heli-24/)

### Automated Testing (Every 3 Days)
- HTML validation and structure checks
- Mobile compatibility verification
- Performance metric validation
- Automated screenshot generation

See `TEST_REPORT.md` for the latest test results.

## 🔄 Version History

### v2.1.0 - Dragons & Difficulty Update
- 🐉 Added **dragon obstacles** with animated wings and fire breath
- 📈 **Progressive difficulty system** - game gets harder over time (up to Level 10)
- 🖥️ **Landscape-only mode** for mobile devices
- ⚡ **High refresh rate support** (60Hz, 90Hz, 120Hz, 144Hz)
- 🔇 **Audio fade effect** on crash - rotor sound smoothly fades out
- 📱 Fixed mobile touch issues for "Engage Rotors" button
- 🎮 Level display added to game over screen
- 🔧 Optimized delta-time physics for all frame rates

### v2.0.0 - 3D Update
- Added 3D-style rendering with parallax depth effects
- Full mobile device optimization for 16:9 and 20:9 devices
- Improved 60 FPS performance with delta-time physics
- Fixed audio stopping on crash
- Added automated testing workflow (runs every 3 days)
- Enhanced touch controls with visual feedback
- No external dependencies - pure HTML/CSS/JS
