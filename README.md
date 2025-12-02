# Vector Chopper 3D

A retro-style 3D helicopter game with vector graphics, floaty physics, and full mobile support. Navigate through procedurally generated terrain while avoiding obstacles and birds!

## 🎮 Play Now
**[Play Vector Chopper](https://anacondy.github.io/3-Heli-24/)**

## Screenshots

### Main Menu (Desktop)
![Main Menu](https://github.com/user-attachments/assets/0e7b5986-c19d-4d01-9ae8-13796f4b1eab)

### Game Over Screen
![Game Over](https://github.com/user-attachments/assets/f2191d45-c765-4311-9a13-b7bab1495c72)

### Mobile 16:9 (Portrait)
![Mobile 16:9](https://github.com/user-attachments/assets/c08c8a70-4f0e-493b-b2d6-2b32f1a64cb5)

### Mobile 20:9 (Portrait)
![Mobile 20:9](https://github.com/user-attachments/assets/4ca5c535-63aa-4e65-8fa2-0d591cf45ec4)

### Mobile Landscape
![Mobile Landscape](https://github.com/user-attachments/assets/b9ed5e35-d8ea-4c98-b41f-45f685321da9)

## ✨ Features

### Graphics & Visual
- 🎮 **3D-style helicopter** with animated rotors
- 🌟 Dynamic starfield with parallax depth effect
- ✨ Particle effects and glow shaders
- 📺 Retro scanline overlay for authentic vector feel
- 💥 Screen shake on crash for impact feedback

### Mobile Support
- 📱 **Fully responsive** design for all screen sizes
- 📐 Optimized for **16:9** and **20:9** aspect ratios
- 👆 Touch-friendly controls with visual feedback
- 🔒 Safe area support for notched devices (iPhone X+, Android)
- 🖥️ Landscape and portrait orientation support

### Performance
- ⚡ **Consistent 60 FPS** with delta-time physics
- 🎯 Frame rate limiting to prevent physics issues
- 📊 Real-time FPS counter in HUD
- 🔧 Optimized rendering pipeline

### Audio
- 🎵 Dynamic rotor sound with throttle response
- 💥 Explosion sound effects
- 🐦 Bird strike audio feedback
- 🔇 **Audio stops immediately** on crash
- 🔊 Mute/unmute with visual feedback

### Gameplay
- 🚁 Floaty helicopter physics
- 🌄 Procedurally generated terrain
- 🐦 Birds as dynamic obstacles
- ⏸️ Pause/resume functionality
- 📈 Distance scoring system

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

### v2.0.0 - 3D Update
- Added 3D-style rendering with parallax depth effects
- Full mobile device optimization for 16:9 and 20:9 devices
- Improved 60 FPS performance with delta-time physics
- Fixed audio stopping on crash
- Added automated testing workflow (runs every 3 days)
- Enhanced touch controls with visual feedback
- No external dependencies - pure HTML/CSS/JS
