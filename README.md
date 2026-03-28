# depth-vfx

Real-time camera VFX for iPhone Safari. Point at any scene with light sources — god rays and energy beams respond instantly.

-----

## What it does

Extracts bright points from your live camera feed and generates:

- Volumetric god ray shafts from light sources
- Colored laser beams connecting light clusters
- Atmospheric haze particles in dark regions
- Cinematic blue grade + bloom post-processing

No app install. No build step. Just open in Safari and tap.

-----

## Use

Open on iPhone 13 Pro+ → tap **ACTIVATE CAMERA** → point at any light source → screen record.

Works best in dark environments with distinct light sources — stage lighting, lamps, neon, windows.

-----

## Stack

- Three.js r169 (CDN, no install)
- WebGL renderer + EffectComposer
- Native `getUserMedia` back camera
- Single `vfx.html` file

-----

## Deploy

```
Settings → Pages → Deploy from main → / (root)
```

Live at `yourusername.github.io/vtime/vfx.html`

-----

## Roadmap

- [x] v1 — god rays + connector beams
- [ ] v2 — hand tracking via micro-handpose
- [ ] v2 — audio reactive intensity
- [ ] v3 — WebGPU compute pipeline
