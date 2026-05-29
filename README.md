# SKYDRIFT 🌥️

A mobile cloud-climbing game. Tap to jump, tap again to double-jump, bounce off
clouds and climb as **high** as you can. The world morphs as you rise — sunset →
dusk → night → aurora → space — and new hazards (drifting clouds, downdrafts,
double-jump jammers, crumbling clouds) layer in the higher you go.

Built as a single self-contained `index.html` — pure HTML5 Canvas + vanilla JS,
no build step, no dependencies.

## Play locally
Just open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Features
- One-thumb controls (jump / double-jump), built for mobile (portrait)
- "Perfect bounce" timing + combo scoring
- Wardrobe: multiple characters + jump-trail effects
- Local accounts + auto-saved scores + leaderboard
- Difficulty that ramps then escalates via milestone mechanics

## Deploy
It's a static site — drop the folder on any static host (Netlify, Vercel,
Cloudflare Pages, GitHub Pages).
