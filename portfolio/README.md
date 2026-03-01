# Portfolio bundle (100 unique demo websites)

This folder contains 100 single-page demo websites with:
- unique color palettes per site
- varied menu formats
- varied hover interactions
- varied animation styles
- unique hero/product image seeds
- visible **Demo Site** label on every page

## Quick GitHub hosting (automatic)
This repo includes a GitHub Actions workflow that deploys `/portfolio` to **GitHub Pages** automatically.

### 1) Push this repository to GitHub
```bash
git remote add origin https://github.com/<your-username>/code-generator.git
git push -u origin work
```

### 2) Enable GitHub Pages in your repo
1. Open **Settings → Pages**
2. Under **Build and deployment**, select **Source: GitHub Actions**

### 3) Wait for deployment
- Open **Actions** tab and check workflow: **Deploy portfolio to GitHub Pages**
- After success, your live URL will be:

`https://<your-username>.github.io/code-generator/`

> This deployment publishes the `portfolio/` folder as the web root, so visitors open the URL directly.

## Manual URL pattern (if you deploy differently)
If you publish full repository root instead of only `portfolio/`, your link becomes:

`https://<your-username>.github.io/code-generator/portfolio/`
