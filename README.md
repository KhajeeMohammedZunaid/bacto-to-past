# Zuris Logo & Path Animation

Vector logo assets and interactive SVG path animation showcase for **Zuris**.

---

## 🎨 Overview

This repository contains official vector assets and an interactive SVG path animation showcase crafted with smooth ambient blur effects and responsive theme compatibility.

### Assets Included
- [`zuris-1.svg`](zuris-1.svg) — Zuris emblem vector (white fill, dark background variant)
- [`zuris-2.svg`](zuris-2.svg) — Zuris emblem vector (black fill, light background variant)
- [`logo-path-animation.html`](logo-path-animation.html) — Interactive SVG path stroke animation showcase (mirrored to `index.html` and `logo path anaimion.html`)

---

## ⚡ Animation & Design Specifications

- **Typography**: Google Font **Inter** (800 weight) with strictly calibrated `-4.5px` letter spacing (`letter-spacing: -4.5px`).
- **Stroke Path Drawing**: High-precision `stroke-dasharray` and `stroke-dashoffset` tracing computed dynamically from SVG path geometry.
- **Atmospheric Glow & Blur**: Multi-layer ambient radial illumination with hardware-accelerated frosted glass container (`backdrop-filter: blur(32px)`).
- **Smooth Blur Type Reveal**: Progressive entrance animation transitioning from `filter: blur(14px)` to `blur(0px)`.
- **Theme Compatibility**: Seamless toggle between luxury dark obsidian (`#09090b`) and crisp light platinum (`#f8fafc`).
- **Controls**: Interactive replay triggers and playback speed adjustment (1x, 1.5x, 2x).

---

## 🚀 Local Preview

Open [`logo-path-animation.html`](logo-path-animation.html) in any modern web browser or start a lightweight local web server:

```bash
# Using Python
python -m http.server 3000

# Using Node.js
npx serve .
```
Then navigate to `http://localhost:3000` to experience the animation.
