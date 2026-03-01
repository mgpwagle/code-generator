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
git remote add origin https://github.com/<your-username>/<your-repo>.git
git push -u origin main
```
(If your branch is `work` or `master`, push that branch instead; workflow supports all three.)

### 2) Enable GitHub Pages in your repo
1. Open **Settings → Pages**
2. Under **Build and deployment**, select **Source: GitHub Actions**

### 3) Wait for deployment
- Open **Actions** tab and check workflow: **Deploy portfolio to GitHub Pages**
- After success, open the URL shown in the deploy step output.

## 404 fix for your specific URL
If `https://mgpwagle.github.io/portfolio` shows 404, it means the site is being checked at the wrong path.

Use this mapping:
- If repo name is `portfolio` → `https://mgpwagle.github.io/portfolio/`
- If repo name is `code-generator` → `https://mgpwagle.github.io/code-generator/`
- If repo is user-site `mgpwagle.github.io` → `https://mgpwagle.github.io/`

> GitHub Pages URL must include the repository name for project sites.


## Repository protection (recommended)
For safer collaboration, configure classic branch protection rules as described in `docs/branch-protection.md`.
