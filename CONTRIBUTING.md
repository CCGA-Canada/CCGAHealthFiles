# Contributing

## Pull Request Templates

All pull requests must use one of the approved company PR description templates.

Use the template that best matches the change type:

| PR Type | Template |
|---|---|
| Feature / Bug Fix | `feature-bugfix.md` |
| Library Upgrade / Swap | `library-upgrade-swap.md` |
| 2-Ticket PR | `two-ticket-pr.md` |

> **Note:** Repo-level PR templates override these company-wide defaults. If a repository defines its own templates, use those instead.

---

## PR Title Format

All PR titles must follow this format:

```text
type(PROJ-123): short description
```

**Examples:**

```text
feat(PROJ-123): add producer search results page
fix(PROJ-124): correct validation message
chore(PROJ-125): upgrade FluentValidation from v11 to v12
refactor(PROJ-126): replace old mapping library with new library
```

---

## Which Template to Use

| Change Type | Template |
|---|---|
| New feature, enhancement, bug fix, or refactor | `PULL_REQUEST_TEMPLATE/feature-bugfix.md` |
| NuGet package upgrade or library swap | `PULL_REQUEST_TEMPLATE/library-upgrade-swap.md` |
| Intentionally combined 2-ticket PR (exception only) | `PULL_REQUEST_TEMPLATE/two-ticket-pr.md` |

---

## 2-Ticket PRs — Exception Only

The `two-ticket-pr.md` template exists for cases where two tickets are genuinely inseparable — for example, they touch the same layer and splitting them would create a broken intermediate state or a misleading review.

**Do not use the 2-ticket template simply to reduce PR count.** If the tickets are independent, open separate PRs.

---

## Selecting a Template on GitHub

When opening a pull request on GitHub, click **"Compare & pull request"**, then use the template selector to choose the appropriate template before writing your description.
