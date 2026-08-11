# Flextail 2026 Product Launch

A static product launch activity page for the FLEXTAIL 2026 release collection.

## What is included

- Interactive product showcase
- Division and release-window filters
- Clickable product detail modal
- Launch timing roadmap matrix
- Placeholder image support through `images/{product_key}.png`
- GitHub Pages deployment workflow

## Product image naming

The page will automatically show product images if matching files are added under `images/`.

Examples:

```text
images/max_blast_300.png
images/evo_sup_pump_200.png
images/max_espresso.png
images/nano_pump_9.png
```

If an image is missing, the page shows a clean branded placeholder instead.

## GitHub Pages

This repository includes `.github/workflows/pages.yml` for deploying the static site to GitHub Pages from the `main` branch.

If the first deployment does not start automatically, open repository Settings > Pages and choose GitHub Actions as the Pages source.
