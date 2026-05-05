<!--
  ⚠️ EXCEPTION-ONLY TEMPLATE ⚠️

  Use this template only when two tickets are genuinely inseparable —
  for example, they touch the same layer and splitting them would create
  a broken intermediate state or a misleading review.

  DO NOT use this template simply to reduce PR count.
  If the tickets are independent, open separate PRs.

  Title format (use the prefix that best matches the primary change type):
    feat(PROJ-123, PROJ-456): short description covering both tickets
    fix(PROJ-123, PROJ-456): short description covering both tickets
    refactor(PROJ-123, PROJ-456): short description covering both tickets
-->

**Title format:**
```
feat(PROJ-123, PROJ-456): short description covering both tickets
fix(PROJ-123, PROJ-456): short description covering both tickets
refactor(PROJ-123, PROJ-456): short description covering both tickets
```
<!-- Use the prefix that best matches the primary change type across both tickets. -->

## Summary
<!-- Why are these two tickets in one PR? Justify the grouping. -->
<!-- e.g. Both touch the same service layer and are part of the same sprint goal. -->

Closes #PROJ-123, Closes #PROJ-456

## Grouping Justification
<!-- Why are these two tickets intentionally grouped in one PR? -->
<!-- Explain why separate PRs would be harder, riskier, or misleading. -->
<!-- If the tickets are independent, split them into separate PRs. -->

## Why Not Separate PRs?
<!-- Explicitly state why this cannot or should not be split. -->
<!-- e.g. PROJ-456 directly depends on the interface introduced in PROJ-123 and cannot be reviewed in isolation. -->

---

## Ticket 1 — [PROJ-123] <!-- Ticket title -->

**What changed:** <!-- What does this change do? -->

**Why it is needed:** <!-- Why is it needed? -->

**Approach / reasoning:** <!-- How was it implemented? -->

---

## Ticket 2 — [PROJ-456] <!-- Ticket title -->

**What changed:** <!-- What does this change do? -->

**Why it is needed:** <!-- Why is it needed? -->

**Approach / reasoning:** <!-- How was it implemented? -->

<!-- If one ticket depends on the other, call it out: -->
<!-- "Note: PROJ-456 depends on the interface change in PROJ-123. Review PROJ-123 first." -->

---

## Dependency / Review Order
<!-- Are the tickets independent, or does one depend on the other? -->
<!-- e.g. Review PROJ-123 first because PROJ-456 depends on its interface change. -->

---

## Area of Impact

**Affected areas:**  
<!-- e.g. Producer API, Application intake, shared validation layer -->

**Impact level:**  
High / Medium / Low

**What could break:**  
- <!-- e.g. Any class using the updated interface -->

**What is NOT affected:** (optional)
- <!-- e.g. Database schema — no migrations -->
- <!-- e.g. API contracts — DTOs unchanged -->

---

## Changes

**PROJ-123**
- <!-- e.g. Added EmailValidationService.cs -->

**PROJ-456**
- <!-- e.g. Added PasswordPolicyService.cs -->

---

## Testing

**PROJ-123**
- [ ] <!-- Unit tests added -->
- Steps: <!-- How to verify -->

**PROJ-456**
- [ ] <!-- Unit tests added -->
- Steps: <!-- How to verify -->

---

## Notes for Reviewer
<!-- e.g. Review PROJ-123 changes first — PROJ-456 builds on top of them. -->
