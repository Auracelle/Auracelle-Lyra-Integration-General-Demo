# Auracelle Lyra v3 — E-AGPO-HT Integration (HTML Prototype)

This repository packages a **single-file interactive HTML integration artifact** for *Auracelle Lyra v3* showing how notebook components map into the v3 architecture (Page 1 E-AGPO, Page 2 E-AGSO, and new Page 3 E-AGPO-HT Sandbox).

## Quick start
### Option A — open locally
Open `index.html` in a modern browser.

### Option B — serve locally (recommended)
Some browsers restrict local file APIs when opening HTML directly. Serve the folder:

```bash
python -m http.server 8080
```

Then open:
- `http://localhost:8080`

## GitHub Pages
This repo includes a GitHub Actions workflow to deploy to GitHub Pages on push to `main`.
After enabling Pages in repo settings (Build and deployment → GitHub Actions), the site will publish automatically.

## Repository contents
- `index.html` — the prototype (no build step)
- `.github/` — issue/PR templates + Pages deploy workflow
- `docs/` — ethics + integration notes
- `CITATION.cff` — citation metadata for academic reuse

## Responsible use
This is a **research / training prototype** for assurance governance and wargaming method development.
Outputs are not forecasts and should not be used as operational decisions without appropriate oversight.

## License
See [LICENSE](LICENSE).

## Contact
PI: **Grace-Alice Evans**
