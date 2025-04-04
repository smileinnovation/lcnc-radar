# Smile Low-Code / No-Code Technology Radar

This repository contains a curated technology radar to explore, assess, and share insights about low-code and no-code (LCNC) platforms. It supports internal innovation initiatives, product scouting, and technical strategy alignment.

## 🧭 What is this?

The radar is a structured, taggable collection of LCNC tools — categorized into quadrants and rings — to guide adoption decisions at Smile.

- **Quadrants** reflect the type of technology: no-code platforms, low-code RAD platforms, open-source tooling, or automation/integration tools.
- **Rings** indicate our current recommendation level: *adopt*, *trial*, *assess*, or *hold*.
- Each tool includes a detailed Markdown file with strengths, weaknesses, integration notes, and suitability for Smile use cases.

## 🚀 Getting Started

### View the Radar

The radar is published via GitHub Pages automatically by a GitHub Action on every push to the `main` branch. The contents of the `/build` directory are deployed to the `gh-pages` branch.

You can access the live radar at:

```
https://smileinnovation.github.io/lcnc-radar/
```

### Local Development

To build the site locally:

```bash
npm install
npm run build
```

This will generate the static site into the `/build` directory.

For development purpose, you can also use the `npm run serve` to pop a webserver, serving static files in the `/build` folder localy.