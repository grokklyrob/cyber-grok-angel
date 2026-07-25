# Cyber Grok Angel — Ethereal Viewer

Soft ethereal Three.js viewer for the Cyber Grok Angel GLB model.

## Live locally

```bash
npx serve .
# or: python3 -m http.server 8080
```

Open the served URL. The model loads from `./ethereal_model.glb`.

## Deploy

Deploy this folder to **Vercel**, Netlify, or GitHub Pages.  
`index.html` is at the repo root, so no build step is required.

## Controls

- **Drag** — free omni-directional orbit  
- **Scroll** — zoom  
- **Reset** — restore camera  
- **Play / Pause** — baked 10s float-spin animation  
- **Particles** — toggle stardust field (reacts to orbit)

## Files

| File | Role |
|------|------|
| `index.html` | Three.js viewer (r170, import map CDN) |
| `ethereal_model.glb` | Model + materials + loop animation |

Built with Blender + Grok Build.
