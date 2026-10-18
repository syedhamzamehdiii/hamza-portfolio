# SHM — Hamza Mehdi Portfolio

A distinctive responsive portfolio with a midnight-indigo canvas, violet/pink/orange gradients, CSS-built 3D-inspired space scene, mouse-reactive hero depth, tilting project cards, and motion-aware scroll reveals.

## Pages and assets
- `index.html` — main portfolio, project links, social profiles, capabilities, and contact form
- `cv.html` — print-ready CV with **Download CV · Save as PDF** button (uses the browser's print-to-PDF)
- `favicon.svg` — custom SHM monogram tab icon

## Projects
SafeApp (Google Play), PostFlow (under development), NovexaHub, KyberQ (Google Play and App Store), TripsAdora, and Content-Nation (currently under Google Play review).

## Run locally
```bash
python3 -m http.server 8000
```
Open http://localhost:8000.

## Deploy
This is a static HTML/CSS/JS site; import the GitHub repository into Vercel and leave the build command empty. On each push to the connected branch, Vercel should deploy automatically.

## Customize
Edit project descriptions/links in `index.html`; update resume content in `cv.html`. The contact form opens a pre-filled email draft; it does not submit to a backend.
