# Simple Template Repository — GitHub Hygiene & Metrics (No Tokens Needed)

This is a **template repository** you can use for classes or teams.
It includes useful **.github/** defaults that work with the built‑in `GITHUB_TOKEN` only:
- PR template, CODEOWNERS, Issue templates
- Labeler (path-based labels for PRs)
- Stale issue cleanup
- Issue Metrics (weekday comment) and Team Metrics (weekly `metrics.md`)

> No Personal Access Tokens. No Project URLs. Works in a single repo.

## How to use this template
1. Create a new repo from this template: **Use this template → Create a new repository**.
2. In your new repo:
   - Edit `.github/CODEOWNERS` to reflect your teams/users.
   - Edit `.github/labeler.yml` to match your folder layout.
   - Add labels (under Issues or Pull requests in the GitHub UI)
3. Push code and open PRs — workflows run automatically.

## Project board (UI, no YAML)
If you want a board, use **Project built-in workflows** in the GitHub UI:
- When item added → set **Status = To Do**
- When issue closed → set **Status = Done**
- When PR merged → set **Status = Done**

## Commit/PR discipline
- Use closing keywords in PR descriptions: `closes #123`, `fixes #456` to auto-close issues on merge.

---

### Files included
- `.github/workflows/labeler.yml`
- `.github/workflows/stale.yml`
- `.github/workflows/issue-metrics.yml`
- `.github/workflows/team-metrics.yml`
- `.github/labeler.yml`
- `.github/issue-metrics-config.yml`
- `.github/PULL_REQUEST_TEMPLATE.md`
- `.github/CODEOWNERS`
- `.github/ISSUE_TEMPLATE/bug_report.yml`
- `.github/ISSUE_TEMPLATE/feature_request.yml`
