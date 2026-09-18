# Synthesis Engine — Landing Page

Cinematic single-page landing for the [Synthesis Engine Showcase](https://github.com/deusexlumen/synthesis-engine-showcase).

Built with the **threejs-webgpu-spectacle** skill.

## What’s included

- **WebGPU + TSL** fullscreen background
  - Projected accretion disk (heat gradient + Doppler side-boost)
  - Photon-ring suggestion
  - Multi-layer procedural star field
  - Soft galactic nebula
  - Mouse parallax + slow orbital drift
  - Filmic tonemap + vignette matching brand purple
- Full content from the public showcase README
  - Hero, features, precision ladder, architecture claims, CTA
- Loading screen, sticky header, responsive layout, WebGPU fallback
- Zero build step — open and go

## Run

```bash
# from this folder
npx serve .
# or
python -m http.server 8080
```

Open in **Chrome** or **Edge** (WebGPU). Firefox/Safari fall back to a static cosmic gradient.

## Files

| File        | Purpose                          |
|-------------|----------------------------------|
| `index.html`| Complete page (HTML + CSS + JS)  |
| `README.md` | This file                        |

## Notes

- Three.js r170 via CDN. For production: pin version and self-host.
- Content mirrors the public showcase (status, tests, precision numbers, design decisions).
- Skill used: `threejs-webgpu-spectacle` (WebGPU/TSL foundation + spectacle layer patterns).
