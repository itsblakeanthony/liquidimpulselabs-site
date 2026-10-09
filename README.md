# Liquid Impulse Labs website

Fluid by design. Charged by nature.

Static website for Liquid Impulse Labs and its iPhone app RepCharge, served by
GitHub Pages at [liquidimpulselabs.com](https://liquidimpulselabs.com).
Plain HTML and CSS only: no frameworks, no build step, no tracking scripts.

| File                | Purpose                                            |
|---------------------|----------------------------------------------------|
| `index.html`        | Company home page, with a box for each app         |
| `repcharge.html`    | RepCharge app page                                 |
| `holdtheflow.html`  | Hold the Flow game page                            |
| `support.html`      | Support, with a panel for each app                 |
| `privacy.html`      | Privacy policy, with a panel for each app          |
| `terms.html`        | Terms of use, with a panel for each app            |
| `assets/style.css`  | Shared styles. Both accent colours are set at the top |
| `assets/*`          | Company logo and icons, RepCharge logos and icons  |
| `CNAME`             | Custom domain for GitHub Pages                     |

Colours: Liquid Impulse Labs uses its yellow (`--accent`) everywhere. The
RepCharge red orange (`--repcharge-accent`) applies only inside elements with
the `repcharge` class (the RepCharge page and the RepCharge box on the home
page), so the header, footer, support, privacy and terms pages keep the
company style.

Support, privacy and terms: one page each, with an app selector. Each app's
complete document is a panel, and a link opens it directly, for example
`privacy.html#repcharge` or `privacy.html#holdtheflow` (use these for each
app's privacy policy and support URLs in App Store Connect). With no app in
the link, the first app shows. It works with CSS only, no script.

The header and footer are repeated in each HTML file, so if you change a link
there, change it on every page.

## Publishing

Repository, then Settings, then Pages: deploy from a branch, choose the branch
and `/ (root)`. The `CNAME` file sets the custom domain to
`liquidimpulselabs.com`.
