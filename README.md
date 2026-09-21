# Timothy — public website

The landing page at [asktimothy.org](https://asktimothy.org). Static HTML,
CSS, and the [Timothy design tokens](tokens.css); no build step.

This is the marketing site, not the product. The engine and the giving
module live at [project-timothy/giving-network](https://github.com/project-timothy/giving-network).

## Editing

Everything is in `index.html` and `style.css`. Open `index.html`
directly in a browser to preview; there is nothing to install or build.

Colors, type, and spacing come from `tokens.css`, generated from the
brand kit. Don't hand-edit that file; a new version replaces it whole.

## Deploying

Pushes to `main` deploy automatically via Vercel.
