# Liquid Impulse Labs website

Fluid by design. Charged by nature.

Static website for Liquid Impulse Labs and its iPhone app RepCharge, served by
GitHub Pages at [liquidimpulselabs.com](https://liquidimpulselabs.com).
Plain HTML and CSS only: no frameworks, no build step, no tracking scripts.

| File                | Purpose                                            |
|---------------------|----------------------------------------------------|
| `index.html`        | Company home page, with a RepCharge section        |
| `repcharge.html`    | RepCharge app page                                 |
| `support.html`      | RepCharge support and contact emails               |
| `privacy.html`      | RepCharge privacy policy                           |
| `terms.html`        | RepCharge terms of use                             |
| `assets/style.css`  | Shared styles. Both accent colours are set at the top |
| `assets/*`          | Company logo and icons, RepCharge logos and icons  |
| `CNAME`             | Custom domain for GitHub Pages                     |

Colours: Liquid Impulse Labs uses its yellow (`--accent`) everywhere. The
RepCharge red orange (`--repcharge-accent`) applies only inside elements with
the `repcharge` class, so the header and footer keep the company style.

The header and footer are repeated in each HTML file, so if you change a link
there, change it on every page.

## Publishing

Repository, then Settings, then Pages: deploy from a branch, choose the branch
and `/ (root)`. The `CNAME` file sets the custom domain to
`liquidimpulselabs.com`.
