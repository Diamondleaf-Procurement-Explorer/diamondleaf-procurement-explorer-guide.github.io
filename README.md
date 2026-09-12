# Diamondleaf Compass

Public navigation hub for Diamondleaf community discussions, the product roadmap and service status. Hosted using the existing GitHub Pages repository and URL.

## Contents

- Three primary destination cards: Discussions, Product Roadmap and Service Status.
- Direct links to all eight discussion categories.
- An expandable Statuspage iframe loaded only when opened, with a permanent direct-link fallback.
- Responsive layout, keyboard focus indicators and reduced-motion support.

## Deployment

Replace `index.html` and `_config.yml` in the existing repository, and update this README. Keep the existing GitHub Pages branch and folder settings. No build dependencies, API tokens or additional hosting are required. Commit and push through the existing publishing workflow.

Links use `target="_top"` so GitHub opens outside any containing product iframe. GitHub pages block iframe embedding. Statuspage response headers allowed framing when checked on 12 September 2026, but this may change; the direct link always remains available.

The page contains no hard-coded operational status. Service status information comes from the embedded Statuspage itself.
