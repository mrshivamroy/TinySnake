# 🐍 Tiny Snake

[![Live Demo](https://img.shields.io/badge/Live-Demo-2ecc71?style=for-the-badge&logo=github)](https://mrshivamroy.github.io/TinySnake)
[![PWA Ready](https://img.shields.io/badge/PWA-Ready-764ba2?style=for-the-badge&logo=pwa)](https://mrshivamroy.github.io/TinySnake)
[![Offline](https://img.shields.io/badge/100%25-Offline-667eea?style=for-the-badge)](https://mrshivamroy.github.io/TinySnake)
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)

> **A classic snake game reimagined as a fully offline-capable Progressive Web App with zero dependencies.**

## 🎮 [Play Now](https://mrshivamroy.github.io/TinySnake)

---

## ✨ Features

### 🎯 Game Mechanics
- **Classic Snake Gameplay** - Eat food, grow longer, avoid walls and yourself
- **Smooth Animations** - Pure CSS animations for fluid movement
- **Score Tracking** - Real-time score display with high score persistence
- **Game Over Detection** - Collision detection with walls and self
- **Pause Functionality** - Pause and resume anytime

### 📱 Cross-Platform Support
- **Desktop Controls** - Arrow keys, WASD, and Spacebar for pause
- **Mobile D-Pad** - Touch-friendly on-screen controls
- **Swipe Gestures** - Natural swipe controls on touch devices
- **Fully Responsive** - Adapts perfectly to any screen size

### 🚀 PWA Capabilities
- **Installable** - Add to home screen on any device
- **Offline First** - Works completely without internet after first load
- **Service Worker** - Intelligent caching for instant loading
- **No Dependencies** - Zero external libraries, fonts, or CDNs
- **Lightweight** - Less than 50KB total size

### 🎨 Design
- **Pure CSS Graphics** - No images or SVGs, just beautiful CSS
- **Gradient Backgrounds** - Eye-catching purple gradient theme
- **Pixel Art Feel** - Nostalgic retro gaming aesthetic
- **Smooth Transitions** - Polished animations throughout

---

## 🎯 How to Play

### Desktop
- **Arrow Keys** or **WASD** - Control snake direction
- **Spacebar** - Pause/Resume game
- **Start Button** - Begin a new game

### Mobile
- **D-Pad Buttons** - Tap directional buttons to move
- **Swipe Gestures** - Swipe in any direction to control
- **Touch Controls** - Tap on-screen buttons

### Rules
1. 🍎 Eat the red food to grow and score points
2. 🐍 Don't hit the walls or your own tail
3. 📈 Beat your high score!

---

## 🚀 Quick Start

### Option 1: Play Online
Simply visit **[https://mrshivamroy.github.io/TinySnake](https://mrshivamroy.github.io/TinySnake)** and start playing!

### Option 2: Install as PWA
1. Visit the game URL
2. Click the **"📱 Install App"** button (or browser's install prompt)
3. Add to home screen
4. Play offline anytime!

### Option 3: Run Locally

```bash
# Clone the repository
git clone https://github.com/mrshivamroy/TinySnake.git
cd TinySnake

# Start a local server (choose one):

# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Node.js (http-server)
npx http-server -p 8000

# PHP
php -S localhost:8000

# Open in browser
# Navigate to: http://localhost:8000
```

---

## 📁 Project Structure

```
TinySnake/
├── index.html           # Main game file with embedded CSS & JS
├── manifest.json        # PWA manifest configuration
├── service-worker.js    # Service worker for offline caching
└── README.md           # This file
```

---

## 🛠️ Technology Stack

- **HTML5** - Semantic structure
- **CSS3** - Grid layout, animations, and pure CSS graphics
- **Vanilla JavaScript** - Game logic and controls
- **Service Workers** - Offline functionality
- **Web App Manifest** - PWA configuration

**Zero External Dependencies** - Everything runs natively in the browser!

---

## 🎨 Key Technical Highlights

### Pure CSS Graphics
```css
.snake-head::before,
.snake-head::after {
    /* Snake eyes created with pure CSS */
    content: '';
    position: absolute;
    width: 25%;
    height: 25%;
    background: #000;
    border-radius: 50%;
}
```

### Offline Caching Strategy
```javascript
// Service worker caches all assets
const CACHE_NAME = 'tiny-snake-v1';
const urlsToCache = ['./','./index.html','./manifest.json'];
```

### Responsive Grid System
```javascript
const GRID_SIZE = 20;
const CELL_SIZE = Math.min(500, window.innerWidth - 60) / GRID_SIZE;
```

---

## 🧪 Testing Offline Mode

### Method 1: Browser DevTools
1. Open game in browser
2. Open DevTools (`F12`)
3. Go to **Application** → **Service Workers**
4. Check **"Offline"** checkbox
5. Refresh page - game still works!

### Method 2: Real Offline Test
1. Install the game as PWA
2. Disconnect from internet (turn off WiFi/mobile data)
3. Open the installed app
4. Play without any internet connection!

---

## 📊 Browser Compatibility

| Browser | Desktop | Mobile | PWA Install |
|---------|---------|--------|-------------|
| Chrome  | ✅      | ✅     | ✅          |
| Edge    | ✅      | ✅     | ✅          |
| Firefox | ✅      | ✅     | ✅          |
| Safari  | ✅      | ✅     | ⚠️          |
| Opera   | ✅      | ✅     | ✅          |

⚠️ Safari supports PWA with limited features

---

## 🎯 Features Roadmap

- [ ] Multiple difficulty levels (Easy, Normal, Hard)
- [ ] Different game modes (Classic, Endless, Timed)
- [ ] Leaderboard system
- [ ] Sound effects and music toggle
- [ ] Custom themes and snake skins
- [ ] Multiplayer mode
- [ ] Power-ups and special items
- [ ] Achievement system

---

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. 🍴 Fork the repository
2. 🔨 Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. 💾 Commit your changes (`git commit -m 'Add AmazingFeature'`)
4. 📤 Push to the branch (`git push origin feature/AmazingFeature`)
5. 🎉 Open a Pull Request

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

**Shivam Roy**

- 🌐 Portfolio: [Your Portfolio](https://mrshivamroy.github.io)
- 🐙 GitHub: [@mrshivamroy](https://github.com/mrshivamroy)

---

## 🙏 Acknowledgments

- Inspired by the classic Nokia Snake game
- Built with ❤️ for retro gaming enthusiasts
- Thanks to the web development community for PWA resources

---

## 🎮 Play Now!

### [🐍 Start Playing Tiny Snake →](https://mrshivamroy.github.io/TinySnake)

---

<div align="center">

**Made with 💚 by Shivam Roy**

If you enjoyed this game, please consider giving it a ⭐ on GitHub!

[![Star on GitHub](https://img.shields.io/github/stars/mrshivamroy/TinySnake?style=social)](https://github.com/mrshivamroy/TinySnake)
[![Follow on GitHub](https://img.shields.io/github/followers/mrshivamroy?style=social)](https://github.com/mrshivamroy)

</div>

---

## 📈 Stats

![GitHub repo size](https://img.shields.io/github/repo-size/mrshivamroy/TinySnake)
![GitHub last commit](https://img.shields.io/github/last-commit/mrshivamroy/TinySnake)
![GitHub issues](https://img.shields.io/github/issues/mrshivamroy/TinySnake)
![GitHub pull requests](https://img.shields.io/github/issues-pr/mrshivamroy/TinySnake)

---

**Happy Gaming! 🎮🐍**