<div align="center">

# 🌐 360° Panorama Viewer

**An interactive WebGL viewer — look around a full 360° equirectangular panorama right in your browser.**

[![Play Now](https://img.shields.io/badge/▶%20PLAY%20NOW-live-brightgreen?style=for-the-badge)](https://torantulino.github.io/panorama-360-viewer/)

[![GitHub Pages](https://img.shields.io/badge/Hosted%20on-GitHub%20Pages-blue?style=flat-square&logo=github)](https://torantulino.github.io/panorama-360-viewer/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](LICENSE)
[![No dependencies](https://img.shields.io/badge/dependencies-none-success?style=flat-square)](index.html)

</div>

---

## 🕹️ Controls

| Input | Action |
|-------|--------|
| **Click** | Enter look mode (captures mouse) |
| **Mouse move** | Look around |
| **Click & drag** | Look around (without pointer lock) |
| **Touch & drag** | Look around on mobile |
| **ESC** | Release mouse |

## ✨ Features

- Pure WebGL — no libraries, no frameworks, single HTML file
- Equirectangular sphere projection with inverted normals (camera inside)
- FPS-style Pointer Lock API for seamless mouse look
- Touch support for mobile devices
- Live video texture streaming from an HTML5 `<video>` element

## 🚀 Running Locally

Just open `index.html` in a browser — no build step needed.

```bash
# Optional: serve locally to avoid CORS issues with the video
npx serve .
```

## 📄 License

MIT © Torantulino
