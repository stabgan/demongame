# Demon vs God

A text-based adventure game built with Unity and exported as a WebGL application. Navigate choices using your keyboard (keys 1, 2, 3) to progress through the story.

## 🎮 Play Now

**[Click here to play](https://stabgan.github.io/demongame)**

> Requires a keyboard — press **1**, **2**, or **3** to make choices.

## What It Does

This is a classic textual adventure game prototype exploring the Unity game development workflow. Players make decisions through numbered prompts that drive the narrative forward.

## 🛠 Tech Stack

| Technology | Purpose |
|---|---|
| 🎮 Unity | Game engine and scene management |
| 🌐 WebGL | Browser-based rendering |
| 📄 HTML / CSS / JS | Web hosting and loading UI |

## Project Structure

```
├── index.html                  # Entry point — loads the Unity WebGL player
├── Build/
│   ├── demonvsgod.json         # Unity build configuration
│   ├── demonvsgod.data.unityweb        # Game data (compressed)
│   ├── demonvsgod.wasm.code.unityweb   # WebAssembly game code
│   ├── demonvsgod.wasm.framework.unityweb  # Unity framework
│   └── UnityLoader.js          # Unity WebGL loader
└── TemplateData/
    ├── style.css               # Loading screen styles
    ├── UnityProgress.js        # Loading progress bar
    └── *.png / *.ico           # UI assets
```

## Running Locally

Serve the project root with any static HTTP server:

```bash
# Python
python -m http.server 8000

# Node.js
npx serve .
```

Then open `http://localhost:8000` in your browser.

> Opening `index.html` directly via `file://` will not work due to browser security restrictions on WebGL content.

## ⚠️ Known Issues

- Built with an older Unity WebGL export format (uses `UnityLoader.js` instead of the modern `createUnityInstance` API). Upgrading requires re-exporting from Unity.
- No mobile / touch support — keyboard input only.

## License

See [LICENSE](LICENSE) for details.

---

*Made by Kaustabh Ganguly (Stabgan) — 2019*
