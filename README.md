# 🎮 Demon Game

A classic text-based adventure game built in Unity and exported to WebGL. This prototype explores interactive storytelling through simple keyboard controls and branching narrative paths.

## 🎯 What It Does

This is a text-based adventure game where players navigate through story scenarios using keyboard inputs (1, 2, 3). The game presents narrative choices and responds to player decisions, creating an interactive storytelling experience.

**🎮 [Play the Game](https://stabgan.github.io/demongame)**

## 🛠 Tech Stack

| Technology | Purpose |
|------------|---------|
| 🎯 Unity | Game engine and development environment |
| 🌐 WebGL | Browser-based deployment target |
| 📝 JavaScript | Unity WebGL loader and progress handling |
| 🎨 CSS | UI styling and responsive design |
| 📱 HTML5 | Web container and structure |

## 🎮 How to Play

1. **Visit the game**: Click the play link above or open `index.html` in a web browser
2. **Controls**: Use keyboard keys `1`, `2`, `3` to make choices
3. **Navigate**: Follow the story prompts and make decisions to progress

## 🚀 Local Development

To run locally:

```bash
# Clone the repository
git clone https://github.com/stabgan/demongame.git
cd demongame

# Serve the files (Python example)
python -m http.server 8000

# Or use any static file server
# Then visit http://localhost:8000
```

## 📁 Project Structure

```
├── Build/                 # Unity WebGL build files
│   ├── demonvsgod.data.unityweb
│   ├── demonvsgod.json
│   ├── demonvsgod.wasm.*
│   └── UnityLoader.js
├── TemplateData/         # Unity WebGL template assets
│   ├── style.css
│   ├── UnityProgress.js
│   └── UI assets (icons, logos)
└── index.html           # Main game container
```

## ⚠️ Known Issues

- **Legacy Unity WebGL**: Uses older Unity WebGL export format (pre-2020)
- **Browser Compatibility**: May have issues with newer browsers due to deprecated WebGL loader
- **Mobile Support**: Limited mobile device compatibility
- **HTTPS Required**: Some browsers require HTTPS for WebGL content

## 🎯 Future Improvements

- Upgrade to modern Unity WebGL template
- Add mobile touch controls
- Implement save/load functionality
- Expand story content and branching paths
- Add audio and visual effects

## 👨‍💻 Developer

Created by **Kaustabh Ganguly** (Stabgan) © 2019

*This project represents early exploration into game development and Unity workflows.*

---

**Note**: This game requires a keyboard for input. Mobile users may experience limited functionality.