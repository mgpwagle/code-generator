# Portfolio bundle (100 unique UI pages)

This portfolio now includes 100 company demos with **different layout and content combinations per page**:
- unique menu style per site
- unique color theme per site
- unique section order/composition (services/products/projects/testimonials/timeline/faq/cta)
- unique SVG hero illustration accents
- different hover interaction and animation behavior
- unique footer/company copy per site

## View
- `portfolio/index.html`
- `portfolio/sites/site-001.html` ... `portfolio/sites/site-100.html`


## Published branch + CSS troubleshooting
- This workflow now updates both **GitHub Pages (Actions source)** and the **`gh-pages` branch**.
- So you can use either Pages source mode:
  1. **GitHub Actions** (recommended), or
  2. **Deploy from a branch** → branch `gh-pages` / folder `/ (root)`.
- CSS files are published in both paths:
  - `/assets.css` and `/sites/...`
  - `/portfolio/assets.css` and `/portfolio/sites/...`

If styles still look old, hard refresh (Ctrl/Cmd + Shift + R) after the workflow run completes.
