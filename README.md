# CoCAD — Multimodal CAD Model Generation

This repository hosts the static website for the TCC project **CoCAD — Multimodal Generative System for Parametric CAD Models** by **Lucas Palmiro de Freitas** (Poli-USP · Télécom Paris · École Polytechnique, M2 Data Science).

The site presents the project abstract, architecture, dataset description, preliminary results, links to resources, and contact information.

## Structure

- `index.html` — main one-page site with sections for Home, Abstract, Architecture, Dataset, Results, Repository & Resources, and Contact.
- `style.css` — styling for layout, typography, hero section, responsive grids, and card components.
- `_config.yml` — minimal GitHub Pages configuration (no Jekyll theme).

## Local Preview

You can open the site directly in a browser by double-clicking `index.html`, or use a simple local server (recommended to mirror GitHub Pages behavior):

```powershell
cd path\to\TCC-Webpage
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

## Deploying to GitHub Pages

1. Push this repository to GitHub (public).
2. In the repository settings, go to **Pages**.
3. Set **Source** to the default branch (e.g., `main`) and **root** directory.
4. Save — GitHub Pages will build and publish the site at the indicated URL.

Once the public CoCAD code repository, training notebooks, and dissertation are available, update the placeholder links in the **Repository & Resources** and **Contact** sections in `index.html`.\n