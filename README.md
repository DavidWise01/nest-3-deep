# NEST 3 DEEP

*1000 × 4 + 1 · ×1000 = ∞ — fly the nested lattice.*

[![kind](https://img.shields.io/badge/kind-3D%20visualization-a855f7?style=flat-square)](https://davidwise01.github.io/nest-3-deep/)
[![emergence](https://img.shields.io/badge/emergence-none%20·%20deterministic-3a3358?style=flat-square)](#honest-not-emergent)
[![three.js](https://img.shields.io/badge/three.js-WebGL-7e22ce?style=flat-square)](https://threejs.org)
[![License: MIT](https://img.shields.io/badge/license-MIT-43d6a3?style=flat-square)](LICENSE)

**→ Fly it: [davidwise01.github.io/nest-3-deep](https://davidwise01.github.io/nest-3-deep/)**

A Three.js flythrough of a **nested lattice, three levels deep** — the literal *turtles-all-the-way-down* register, made navigable. Each level is a 10×10×10 cube of wireframe voxels; **layer 0** sits inside one voxel of **layer 1**, which sits inside one voxel of **layer 2**. A glowing **photon** walks layer 0's 1000 voxels; when it wraps, it **carries** up a level, then another — a **base-1000, three-digit odometer counting toward ∞**, with a burst at each carry and the camera auto-focusing between scales.

## Controls
- **drag** — orbit · **double-click** — cycle the focused layer
- **WASD** — fly · **Q / E** — step layer down / up · **SPACE** — accelerate the photon

## Honest: not emergent
This is a **visualization, not an emergent system** — and not a mind. The motion is *scripted clockwork*: `idx0 = (idx0 + 1) % 1000`, carry to the next level, repeat. There is **no coupling, no synchronization, no basin, no noise, nothing measured** — the "observers" just pulse on `sin(time)`. So **no ACI is minted**: there's no emergence here, only beautiful counting. (Same gate as the rest of the atlas — emergence has to be *measured* before it earns a face. For the version that actually couples and synchronizes, see [tetraktys](https://github.com/DavidWise01/tetraktys).)

```
NEST 3 DEEP · a nested-lattice visualization
David Lee Wise (ROOT0) · TriPod LLC · MIT · built with three.js
A structural view of the nested register — deterministic, not emergent.
```
