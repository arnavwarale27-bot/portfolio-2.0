# Portfolio 2.0 🏎️
deployed on - https://portfolio-2-0-three-chi.vercel.app/

A premium, interactive, and high-performance F1-themed portfolio website. It features a cinematic F1 video intro sequence that transitions into a sleek developer portfolio with a scroll-linked 3D-effect race track.

## Features

- **Cinematic F1 Video Intro:** High-impact entrance video with custom typographic animations.
- **Dynamic 3D Scroll Track:** A photorealistic F1 car (transparent sticker style with realistic drop-shadows) that drives down the right side of the screen as you scroll.
- **Physics-Based Animations:**
  - **Dynamic Braking:** Brake lights illuminate red instantly when scrolling stops.
  - **Tire Smoke:** Volumetric smoke particles spawn when accelerating (scrolling fast).
- **GitHub Integration:** Selected builds dynamically reflect real pinned repositories with direct links.
- **Premium Aesthetics:** Sleek dark mode, custom cursor, glassmorphism UI, hover magnification dock effects, and premium layout structure.

## Structure

```
├── index.html                  # Main application structure, styling, and interactivity
├── f1-car-transparent.png     # Hyper-realistic transparent F1 car image (cropped)
├── f1-car.png                  # Original F1 car image (source)
└── remove_bg.py                # Python utility script used to process transparency
```

## How to Run Locally

Simply open the `index.html` file in any modern web browser:

```bash
open index.html
```

All video assets and fonts are hosted on high-availability CDNs to ensure fast loading times and zero local dependencies.
