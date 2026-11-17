# AHK Group concept: website and Hospitality Intelligence platform

Two static, dependency-free pages. No build step.

- `website/index.html`: concept corporate website
- `platform/index.html`: interactive hospitality platform prototype (login is a demo, no credentials are checked)
- `assets/`: logo files (SVG, light and dark)
- `index.html`: simple landing page linking to both

All figures, locations, guests and projects are demonstration data. This is a concept prepared for discussion, not an official AHK Group product.

## Run locally
Open `index.html` in a browser, or run `python3 -m http.server` in this folder.

## Publish on GitHub Pages
1. Push this folder to a repository.
2. Settings → Pages → Deploy from branch → `main` / root.
3. Visit `https://<user>.github.io/<repo>/`.

External resources: Google Fonts and Chart.js (cdnjs) load from the internet.
