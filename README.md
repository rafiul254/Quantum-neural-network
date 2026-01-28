# 🧠 3D Quantum Neural Network Visualization

An interactive, real-time 3D neural network visualization with stunning visual effects, particle animations, and dynamic color themes. Built with Three.js and modern web technologies.

![WebGL](https://img.shields.io/badge/WebGL-Enabled-blue) ![Three.js](https://img.shields.io/badge/Three.js-r128-green) ![License](https://img.shields.io/badge/License-MIT-yellow)

## ✨ Features

### 🎨 Visual Features
- **6 Beautiful Color Themes**: Purple Nebula, Red Aurora, Blue Ocean, Green Matrix, Golden Sun, Pink Cosmos
- **6 Background Options**: Dark, Navy, Ocean, Void, Purple, Deep
- **Particle Effects**: Click anywhere to trigger explosive particle animations
- **Bloom Effects**: Gorgeous glowing nodes and connections
- **Dynamic Lighting**: Breathing and pulsing animations

### 🎮 Interactive Controls
- **Click to Pulse**: Trigger energy waves through the network
- **Drag to Rotate**: 360° orbital camera controls
- **5 Formation Types**: Switch between different network structures
- **Density Control**: Adjust network complexity (30% - 150%)
- **Pause/Play**: Freeze animation at any moment
- **Fullscreen Mode**: Immersive full-screen experience
- **Camera Reset**: Return to default view

### 🌌 Advanced Effects
- **2000+ Twinkling Stars**: Animated background starfield
- **Curved Connections**: Smooth bezier-like connection lines
- **Flow Animation**: Energy flowing through connections
- **Pulse Propagation**: Wave effects spreading from click points
- **Auto-Rotation**: Smooth automatic camera rotation

## 🚀 Demo

**[Live Demo](https://github.com/rafiul254/Quantum-neural-network)** ← Click to see it in action!

## 🛠️ Technologies Used

- **Three.js** (r128) - 3D graphics rendering
- **WebGL** - Hardware-accelerated graphics
- **GLSL Shaders** - Custom vertex and fragment shaders
- **Orbital Controls** - Interactive camera manipulation
- **Post-processing** - Bloom and effects
- **Vanilla JavaScript** - No framework dependencies
- **CSS3** - Glassmorphism UI design

## 📦 Installation

### Option 1: Direct Usage
Simply download `index.html` and open it in a modern web browser. That's it!

```bash
# Download the file
curl -O https://raw.githubusercontent.com/your-username/quantum-neural-network/main/index.html

# Open in browser
open index.html  # Mac
start index.html # Windows
xdg-open index.html # Linux
```

### Option 2: Clone Repository
```bash
git clone https://github.com/your-username/quantum-neural-network.git
cd quantum-neural-network
```

Then open `index.html` in your browser.

### Option 3: Local Server (Recommended for Development)
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000`

## 🎯 Usage

### Basic Interaction
1. **Click anywhere** on the canvas to trigger pulse effects
2. **Drag** to rotate the camera view
3. **Scroll** to zoom in/out
4. Click **theme buttons** to change colors
5. Adjust **density slider** to change network complexity

### Keyboard Shortcuts
- `ESC` - Exit fullscreen mode

### UI Controls
- **Change Formation** - Switch between 5 different network structures
- **Freeze/Play** - Pause or resume animation
- **Reset Camera** - Return to default camera position
- **Fullscreen** - Toggle fullscreen mode
- **Theme Selector** - Choose from 6 color themes
- **Background Selector** - Choose from 6 background colors
- **Density Slider** - Adjust network density (30% - 150%)

## 🎨 Customization

### Changing Colors
Edit the `colorPalettes` array in the JavaScript section:
```javascript
const colorPalettes = [
    [
        new THREE.Color(0xa78bfa),  // Light purple
        new THREE.Color(0x818cf8),  // Medium purple
        new THREE.Color(0x6366f1),  // Dark purple
        new THREE.Color(0x4f46e5)   // Deepest purple
    ],
    // Add your own color palette here
];
```

### Adjusting Network Size
Modify these values:
```javascript
const config = {
    densityFactor: 1.0,           // Network density
    numFormations: 5,             // Number of formations
    maxConnectionDistance: 25      // Connection range
};
```

### Changing Animation Speed
```javascript
controls.autoRotateSpeed = 0.5;   // Rotation speed (default: 0.5)
```

## 🔧 Browser Compatibility

| Browser | Version | Support |
|---------|---------|---------|
| Chrome | 90+ | ✅ Full Support |
| Firefox | 88+ | ✅ Full Support |
| Safari | 14+ | ✅ Full Support |
| Edge | 90+ | ✅ Full Support |
| Opera | 76+ | ✅ Full Support |

**Requirements:**
- WebGL 2.0 support
- Modern JavaScript (ES6+)
- Hardware acceleration enabled

## 📱 Mobile Support

Fully responsive and touch-enabled:
- ✅ Touch to trigger pulses
- ✅ Pinch to zoom
- ✅ Drag to rotate
- ✅ Optimized performance for mobile devices

## ⚡ Performance

- **60 FPS** on modern hardware
- **Optimized rendering** with shader-based particles
- **Efficient memory usage** with geometry instancing
- **Adaptive quality** based on device capabilities

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Ideas for Contributions
- [ ] Add more color themes
- [ ] Create new formation patterns
- [ ] Add sound effects
- [ ] Implement VR support
- [ ] Add export/screenshot feature
- [ ] Create mobile-optimized version
- [ ] Add more particle effects

## 📝 License

This project is licensed under the MIT License.

```

## 🙏 Acknowledgments

- **Three.js** - Amazing 3D library
- **Google Fonts** - Outfit font family
- **Inspiration** - Neural network visualizations and quantum computing aesthetics
- **Community** - All contributors and users

## 📞 Contact

- **GitHub**: https://github.com/rafiul254
- **Email**: rafuulislam2004@gmail.com
- **Linktree**: https://linktr.ee/rafi.ire6thengineer

## 🌟 Star History

If you like this project, please give it a ⭐️ on GitHub!

[![Star History Chart](https://api.star-history.com/svg?repos=your-username/quantum-neural-network&type=Date)](https://star-history.com/#your-username/quantum-neural-network&Date)

## 🐛 Known Issues

- Fullscreen mode may not work on iOS Safari (browser limitation)
- Performance may vary on older mobile devices
- Bloom effect intensity may differ between browsers

## 🔮 Future Plans

- [ ] Add VR/AR support
- [ ] Machine learning integration
- [ ] Real-time data visualization
- [ ] Multiplayer interaction
- [ ] Export as video/GIF
- [ ] Custom formation builder
- [ ] Audio reactivity
- [ ] Node customization

## 📊 Project Stats

![GitHub stars](https://img.shields.io/github/stars/your-username/quantum-neural-network?style=social)
![GitHub forks](https://img.shields.io/github/forks/your-username/quantum-neural-network?style=social)
![GitHub issues](https://img.shields.io/github/issues/your-username/quantum-neural-network)
![GitHub pull requests](https://img.shields.io/github/issues-pr/your-username/quantum-neural-network)

---

<div align="center">
  <p>Made with ❤️ and ✨</p>
  <p>© 2026 Rafiul Islam All rights reserved.</p>
</div>