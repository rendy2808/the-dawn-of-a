<div align="center">

# 🌅 The Dawn Of A

**A creative sketchbook that lives in your browser.**  
Draw, write, sketch ideas — no install, no cloud, no friction.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-ff6b2b?style=for-the-badge&logo=github)](https://rendy2808.github.io/the-dawn-of-a/)
[![HTML](https://img.shields.io/badge/Built%20With-HTML5%20Canvas-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
[![Zero Dependencies](https://img.shields.io/badge/Dependencies-Zero-4361ee?style=for-the-badge)](.)
[![Single File](https://img.shields.io/badge/Architecture-Single%20File-ffb300?style=for-the-badge)](the-dawn-of-a.html)

</div>

---

## ✦ What is this?

*The Dawn Of A* is a zero-dependency, browser-native creative sketchbook — built entirely in a single HTML file. No frameworks, no build tools, no account required. Open the page, start drawing.

It supports freehand drawing, shapes, text, multi-page layouts, and three distinct creative modes — all saveable to your local machine.

---

## ✦ Features

### ✏️ Drawing Tools
| Tool | Description |
|------|-------------|
| **Pencil** | Rough, hand-drawn strokes with natural texture jitter |
| **Pen** | Smooth Catmull-Rom spline curves |
| **Brush** | Velocity-sensitive variable-width strokes |

### 📐 Shapes
- Rectangles, ellipses, lines, and arrows
- **Comic mode** — speech bubbles, shout bursts, thought clouds, narration boxes, panels
- **Graph mode** — process boxes, terminators, databases, parallelograms (flowchart-ready)

### 📒 Pages & Layout
- Multi-page book with **cinematic page-flip animation**
- Canvas sizes: A4, A3, Letter, Square, Wide
- **Snap to grid** for precise alignment

### 💾 Save & Export
- **Auto-save** to `localStorage` — your work survives a page refresh
- **Save as `.md`** — portable Markdown file with embedded drawing data
- **Export as PDF** — print-ready, one page per canvas

### 🎨 Creative Modes
| Mode | Purpose |
|------|---------|
| **Blank** | Clean canvas — freeform ideation |
| **Comic** | Panel-based storytelling with comic-specific shapes |
| **Graph** | Flowcharts, diagrams, structured thinking |

---

## ✦ Getting Started

### Use Online
👉 **[rendy2808.github.io/the-dawn-of-a](https://rendy2808.github.io/the-dawn-of-a/)**

### Run Locally
No install needed — just open the file:

```bash
git clone git@github.com:rendy2808/the-dawn-of-a.git
cd the-dawn-of-a
# open the-dawn-of-a.html in your browser
```

Or simply [download the HTML file](the-dawn-of-a.html) and open it directly.

---

## ✦ How to Use

1. **Choose a template** on first launch (Blank / Comic / Graph)
2. **Select a tool** from the left sidebar — draw, shape, text, select
3. **Pick stroke type** — pencil, pen, or brush
4. **Add pages** with the `+` button and flip between them
5. **Save your work** anytime — auto-save runs in the background
6. **Export** as PDF or `.md` when you're ready to share

---

## ✦ Tech Stack

```
HTML5 Canvas 2D API   — all rendering
Vanilla JavaScript    — zero framework, ~1800 lines
CSS custom properties — theming & layout
jsPDF (CDN)           — PDF export only
localStorage          — session persistence
```

Everything runs client-side. Nothing leaves your browser.

---

## ✦ Design Philosophy

> *Start with a blank page. Let the tool disappear.*

The interface is deliberately minimal — a clean white sidebar, soft dot-grid canvas, and an orange accent that feels like the first light of a new idea. Inspired by the creative flow of tools like Excalidraw and Notions, but stripped to the essentials.

---

## ✦ License

MIT — do whatever you want with it.

---

<div align="center">

Made with curiosity and a single HTML file.  
**[Open The Dawn Of A →](https://rendy2808.github.io/the-dawn-of-a/)**

</div>
