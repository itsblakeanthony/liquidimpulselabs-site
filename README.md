# Liquid Impulse Labs website

Fluid by design. Charged by nature.

Static website for Liquid Impulse Labs and the PPL Training app, served by
GitHub Pages at [liquidimpulselabs.com](https://liquidimpulselabs.com).
Plain HTML and CSS only: no frameworks, no build step, no tracking scripts.

| File                | Purpose                                         |
|---------------------|-------------------------------------------------|
| `index.html`        | Company home page                               |
| `ppl-training.html` | PPL Training features                           |
| `support.html`      | Support page and contact email                  |
| `privacy.html`      | Privacy Policy                                  |
| `terms.html`        | Terms of Use                                    |
| `assets/style.css`  | Shared styles. Colours are set at the top       |
| `assets/*.png`      | Logo mark, app icon and favicons                |
| `CNAME`             | Custom domain for GitHub Pages                  |

The header and footer are repeated in each HTML file, so if you change a link
there, change it on every page.

## Publishing

1. Repository → **Settings** → **Pages** → *Deploy from a branch*, choose the
   branch and `/ (root)`, then **Save**.
2. The `CNAME` file sets the custom domain to `liquidimpulselabs.com`. At your
   domain registrar, point the domain at GitHub Pages (see GitHub's
   "Managing a custom domain for your GitHub Pages site" guide), then tick
   **Enforce HTTPS** in the Pages settings once it becomes available.
