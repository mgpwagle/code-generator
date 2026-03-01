# Branch protection setup (GitHub)

Use this guide to configure **classic branch protection** so your repository is safer and your pull-request process works consistently.

## Recommended rule for `main`

Go to: **Repository → Settings → Branches → Add classic branch protection rule**

- **Branch name pattern:** `main`
- ✅ Require a pull request before merging
  - ✅ Require approvals: **1** (or **0** if you are solo)
  - ✅ Dismiss stale pull request approvals when new commits are pushed
  - ✅ Require review from code owners *(optional)*
- ✅ Require status checks to pass before merging
  - Add check: `Deploy portfolio to GitHub Pages / deploy`
- ✅ Require branches to be up to date before merging
- ✅ Restrict who can push to matching branches *(optional)*
- ✅ Do not allow bypassing the above settings
- ✅ Allow force pushes: **off**
- ✅ Allow deletions: **off**

## Important notes

- GitHub does **not** allow PR authors to approve their own pull requests.
- If you are the only maintainer, set required approvals to **0** to avoid blocking yourself.
- For team workflows, keep approvals at **1+** and have another reviewer approve.

## Optional: protect `work` branch too
If you actively merge into `work`, add a second rule for `work` with the same settings.

## Quick verification checklist

After saving rules:
1. Open a test PR.
2. Confirm merge button is blocked until required checks pass.
3. Confirm force-push and branch delete are blocked.
4. Confirm Pages deploy check appears in PR status checks.
