# The Storybook Arcade — DrakeDragon Games

A mobile-first fairytale/Wonderland-inspired game library featuring **18 games**, unique AI-generated illustrated thumbnails, live game links, search, category filters and a Surprise Me feature.

## Deploy on GitHub Pages

1. Create a new GitHub repository (for example, `StorybookArcade`).
2. Upload **the contents of this folder**, so `index.html` and `assets/` are at the repository root. Do not upload the parent folder as an extra nested directory.
3. Go to **Settings → Pages** and choose **Deploy from a branch**, your main branch, and **/(root)**. Save.
4. Open `https://YOURUSERNAME.github.io/StorybookArcade/` after GitHub Pages publishes.

All eighteen game links are included in the page. Generated artwork is stored locally under `assets/`, so the image gallery does not depend on external image hosts. Google Fonts are optional: system serif/sans-serif fallbacks work without them.

## Customize

Edit the `games` JavaScript array at the end of `index.html` to change titles, copy, categories, and URLs. Replace any `assets/<slug>.webp` image to change its thumbnail.
