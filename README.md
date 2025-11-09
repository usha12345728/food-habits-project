# Food Habits — Eat Smart, Live Better

Student project: a single-file responsive website that promotes healthy eating habits for students and campus communities.  
Includes practical tips, an integrated gallery from fieldwork, an interactive contact section, and subtle animations.

## Demo
If GitHub Pages is enabled:
https://usha12345728.github.io/food-habits-project/

## Features
- Single-file, responsive `index.html` (no build tools required)
- Gallery with captions and light animations
- Theme toggle (dark / light)
- Reveal-on-scroll animations and micro-interactions
- Floating contact bar with SVG icons + scroll-to-top button
- Image fallback for offline / missing images

## File structure

food-habits-project/
├── index.html
└── images/
├── hero-bg.jpg
├── Image1.jpg
├── image2.jpg
├── image3.jpg
├── image4.jpg
├── image5.jpg
├── image6.jpg
└── image7.jpg


## How to preview locally
1. Place `index.html` and the `images/` folder in the same project folder.  
2. Open `index.html` in a browser (double-click or right-click → open with browser).  
No server or build step required.

Optional: run a lightweight static server (useful for testing relative paths)
```bash
# using Python 3
python -m http.server 8000
# then open http://localhost:8000 in your browser
