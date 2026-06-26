# Cajueiro AR — Embodied Generative Tree

**Augmented Reality Experience for the Principia Orthogona / TOGT / dm³ Framework**

This repository delivers an interactive Augmented Reality (AR) installation featuring the iconic **Cajueiro** (cashew tree) from Pirangi, RN, Brazil — the living embodiment and central metaphor of the **dm³ system** DM³ and the generative four/five-operator cycle (G = C → K → F → U → E).

## Overview

The AR overlay activates when your device's camera detects the printed QR target. It displays the tree in 3D space with contextual information, animations, and connections to the mathematical framework (g-series regimes, operator cycle, seed-to-canopy to forest morphogenesis).

### Repository Contents

| File                  | Description |
|-----------------------|-----------|
| `index.html`          | Main entry point — launches the AR experience (optimized for mobile browsers) |
| `cajueiro-ar.html`    | Dedicated AR scene file (MindAR + Three.js) |
| `qr_with_tree.png`    | Printable QR target marker with tree visual |
| `qr-target.mind`      | MindAR compiled target file (used by the AR engine) |
| `cajueiro.mp4`        | Video asset (background / fallback / explanatory loop) |

## How to Use

### Quick Start (Recommended)
1. Print or display `qr_with_tree.png` clearly on paper or a screen.
2. Open `index.html` on a mobile device (iOS Safari or Android Chrome recommended).
3. Allow camera access.
4. Point the camera at the printed QR target.
5. The **Cajueiro AR overlay** will appear automatically.

### Alternative
- Open `cajueiro-ar.html` directly for the standalone AR scene.

## Technical Stack

- **MindAR** — Web AR engine (image tracking)
- **Three.js** — 3D rendering
- **HTML + JavaScript** — Lightweight, no build step required
- Works offline after first load (assets are local)

## Connection to the Framework

The Cajueiro is not merely a visual: it is the **physical root** of the entire Principia Orthogona project.

- **Seed → Canopy** morphogenesis mirrors the **g-series** (g⁰ → g⁶ → g³³ → g⁶⁴)
- Walking meditation paths around the tree embody the **four-operator cycle**:
  - **C** — Compress / Attention
  - **K** — Curvature / Embodiment
  - **F** — Fold / Testing
  - **U** — Unfold / Expansion
- The AR experience serves as a living didactic tool, linking formal Lean 4 proofs (AXLE registry) with embodied practice.

## Printing Instructions

- Print `qr_with_tree.png` at A4 or larger.
- Use matte paper for best tracking.
- Ensure good lighting and avoid strong glare.

## Project Links

- **Main Framework**: https://sluing.github.io/neuro/SBM/1080.html (AXLE Theorem Registry)
- **GitHub Organization**: https://github.com/TOTOGT
- **Lean 4 Formalization**: https://totogt.github.io/AXLE
- **Zenodo Papers**: https://zenodo.org/records/20710023
## License

- Code: MIT
- Assets & Educational Content: CC BY 4.0
- The Cajueiro itself remains a living organism in Pirangi, RN, Brazil.

---

**"From one tree, many branches. From one seed, a generative canopy."**

Made with curiosity and rigor as part of the **Principia Orthogona** living book series.
