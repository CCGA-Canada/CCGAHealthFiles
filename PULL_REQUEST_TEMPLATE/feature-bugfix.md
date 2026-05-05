<!--
  Use this template for:
  - New features and enhancements
  - Bug fixes
  - Refactor-only changes

  Title format:
    feat(PROJ-123): short description of the change
    fix(PROJ-123): short description of the fix
    refactor(PROJ-123): short description of the refactor
-->

**Title format:**
```
feat(PROJ-123): short description of the change
fix(PROJ-123): short description of the fix
```

## Summary
<!-- What does this PR do? 1-3 sentences. -->
<!-- For a bug fix, include the root cause here. -->

Closes #PROJ-123 <!-- what ticket does it impact/closes. -->

## Area of Impact

**Affected areas:**  
<!-- e.g. Producer API, Application intake flow, validation layer -->

**Impact level:**  
High / Medium / Low

**What could break:**  
- <!-- e.g. Producer search results, validation flow, API response handling -->

**What is NOT affected:** (optional)
- <!-- e.g. Database schema — no migrations added -->
- <!-- e.g. API contracts — request/response models unchanged -->
- <!-- just in a nutshell, what was not impacted (areas and flows) -->

## Changes
- <!-- Added X -->
- <!-- Updated Y -->
- <!-- Removed Z -->

## Approach / Reasoning
<!-- Why was this solution chosen? -->
<!-- What key decisions or trade-offs were made? -->
<!-- Mention alternatives considered, if relevant. -->
<!-- For a bug fix, explain how the change resolves the root cause. -->

## Testing
- [ ] Unit tests added / updated in Tests/
- [ ] Integration tests pass / business logic tested
- [ ] Manually tested via Swagger / Postman
- [ ] No Build errors (pipeline)
- [ ] No warnings in build output (optional)

**Steps to test:**
<!-- we should be precise about the steps to make sure we are including all the possible cases -->
1. <!-- e.g. Run the API locally -->
2. <!-- e.g. POST to /api/signup with an invalid email -->
3. <!-- e.g. Confirm 400 response with validation message -->

## Screenshots (if available)
| Before | After |
|--------|-------|
| img    | img   |

## Notes for Reviewer
<!-- Any areas of concern, open questions, or extra context. -->
