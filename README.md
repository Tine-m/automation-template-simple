# Template Repository — GitHub Hygiene & Metrics

This **template repository** contains:
- PR template, Issue templates
- CODEOWNERS (to auto-request reviewers)
- Labeler (path-based labels for PRs)
- Stale issue cleanup
- Issue Metrics (weekday comment) and Team Metrics (weekly report `metrics.md`)

> No Personal Access Tokens. No Project URLs. Works in a single repo.

## How to use this template
1. Create a new repo from this template: **Use this template → Create a new repository**.
2. In your new repo:
   - Edit `.github/CODEOWNERS` to reflect your teams/users.
   - Edit `.github/labeler.yml` to match your folder layout. Used by `.github/workflows/labeler.yml`
   - Add labels (under Issues or Pull requests in the GitHub UI)
3. Push code and open PRs — workflows run automatically.

## Project board
Use use **Project built-in workflows** in the GitHub UI:
- When item added → set **Status = To Do**
- When issue closed → set **Status = Done**
- When PR merged → set **Status = Done**

## Commit/PR discipline
- Use closing keywords in PR descriptions: `closes #123`, `fixes #456` to auto-close issues on merge.

---

## Metrics & Reports

We collect lightweight team metrics:
- Daily bot comment → response time, closure time `.github/workflows/issue-metrics.yml`
- Weekly metrics.md → opened vs closed issues/PRs `.github/workflows/team-metrics.yml`

These are for learning and improvement, not for micro-management.

---
## Good Citizen Checklist  
- `.github/ISSUE_TEMPLATE/bug_report.yml`, `feature_request.yml`
- `.github/PULL_REQUEST_TEMPLATE.md` (ask for “Closes #123”)
- CODEOWNERS to auto-request reviewers

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



