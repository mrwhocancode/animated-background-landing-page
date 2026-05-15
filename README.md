# Animated Background Landing Page

A clean, minimal landing page featuring a **perspective dot-grid canvas background** that responds to mouse movement. Built with pure HTML, CSS, and vanilla JavaScript — no frameworks, no dependencies.

![HTML](https://img.shields.io/badge/HTML-100%25-e34c26?style=flat-square&logo=html5&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)
![No dependencies](https://img.shields.io/badge/dependencies-none-brightgreen?style=flat-square)

---

## Preview

> Dark navy background · Perspective dot grid · Mouse parallax · Responsive nav · Outlined CTA button

---

## Features

- **Perspective dot-grid** — small dots converge toward a vanishing point in the upper-right, simulating depth
- **Mouse parallax** — distant dots shift subtly on hover, giving the background a 3D feel
- **Zero dependencies** — no libraries, no CDN scripts, no install required. Just open `index.html`
- **Fully responsive** — nav and hero scale cleanly across screen sizes
- **Lightweight** — single HTML file, renders instantly

---

## Getting Started

### Option 1 — Just open it
```bash
# Clone the repo
git clone https://github.com/mrwhocancode/animated-background-landing-page.git

# Open in your browser
open index.html
```

### Option 2 — Serve locally with live reload
```bash
# Install live-server globally (one-time)
npm install -g live-server

# Run from the project folder
live-server
```

---

## Project Structure

```
animated-background-landing-page/
├── index.html        # Everything — markup, styles, and canvas animation
├── package.json
└── README.md
```

---

## Customisation

All the key values are easy to tweak at the top of the `<script>` block in `index.html`:

| Variable | What it controls |
|---|---|
| `cols` / `rows` | Density of the dot grid |
| `VP.xFrac` / `VP.yFrac` | Position of the vanishing point (0–1) |
| `mouse parallax strength` | How much dots shift on mouse move |
| CSS `--bg` | Background colour |
| Dot `hue` / `sat` / `lit` | Dot colour range |

---

## License

MIT — free to use, modify, and distribute.

---

*Made by [@mrwhocancode](https://github.com/mrwhocancode)*
