# Wormhole & Black Hole

An interactive, single-file educational visualization of an Einstein–Rosen bridge and a black hole, rendered in WebGL with Three.js.

Open `wormhole.html` in any modern browser — no build step, no dependencies beyond a CDN-loaded Three.js.

## Features

- **Wormhole** — a catenoid embedding diagram with adjustable throat radius, length, and flare. Geodesics show how light bends through curved space; a traveler particle threads the throat.
- **Black hole** — event horizon, photon sphere, accretion disk (with Doppler boost), ISCO, infalling particles, spin axis. Sliders for mass, disk tilt, and spin rate.
- **"Fall into the black hole"** — first-person fall with gravitational lensing, blueshift, chromatic aberration, vignette, and phase-by-phase narration (approach → ISCO → photon sphere → horizon → crossing → inside).
- **Hover any feature** for a tooltip; click for a plain-English explanation.
- **Controls** — drag to orbit, right-drag to pan, scroll to zoom, WASD + QE to fly, Shift to boost, R to reset.

## Stack

Pure HTML / CSS / vanilla JS modules. Three.js r160 loaded from CDN with `EffectComposer` for the post-processing lens shader.
