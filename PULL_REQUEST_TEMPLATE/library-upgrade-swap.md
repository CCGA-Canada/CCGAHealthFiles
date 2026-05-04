<!--
  Use this template for:
  - NuGet package upgrades (major or minor)
  - Library swaps (replacing one library with another)

  Title prefix:
    chore: for library upgrades
    refactor: for library swaps

  Title format:
    chore(PROJ-123): upgrade PackageName from vX to vY
    refactor(PROJ-123): replace OldLibrary with NewLibrary
-->

**Title format:**
```
chore(PROJ-123): upgrade PackageName from vX to vY
refactor(PROJ-123): replace OldLibrary with NewLibrary
```

## Summary
<!-- What changed and why? -->
<!-- Upgrade: "Upgraded X from vA to vB to resolve a security vulnerability." -->
<!-- Swap: "Replaced X with Y. X is no longer maintained / Y is the recommended alternative." -->

Closes #PROJ-123

## Package / Library Change
- **Package:** <!-- e.g. Newtonsoft.Json -->
- **From:** <!-- e.g. 12.0.3 / Newtonsoft.Json -->
- **To:** <!-- e.g. 13.0.3 / System.Text.Json -->
- **Type:** Major upgrade / Minor upgrade / Library swap

## Motivation
- <!-- e.g. CVE-XXXX-XXXX vulnerability in 12.x — [link] -->
- <!-- e.g. Microsoft recommends System.Text.Json for .NET 6+ — [link] -->

## Breaking Changes / Compatibility Notes
<!-- List breaking changes from the official changelog that affect our codebase. -->
<!-- For a swap, list API differences and how they were handled. -->
- <!-- e.g. JObject.Parse() now throws on duplicate keys by default -->

Migration guide: <!-- https://... -->
Full changelog: <!-- https://... -->

## Approach / Reasoning
<!-- Why was this upgrade/swap handled this way? -->
<!-- What key decisions or trade-offs were made? -->
<!-- Mention alternatives considered, if relevant. -->
<!-- Explain any wrappers, adapters, phased migration choices, or compatibility handling. -->

## Area of Impact

**Scope:**  
<!-- include the libraries that have been changed/removed/added or updated -->

**Affected areas:**  
<!-- e.g. Serialization helpers, Producer API, validation layer -->

**Impact level:**  
High / Medium / Low

**What could break:**  
- <!-- e.g. Any class relying on old serialization behaviour -->

**What is NOT affected:** (optional)
- <!-- e.g. Database schema and migrations -->
- <!-- e.g. API endpoint routing and contracts -->

## Codebase Updates
- <!-- e.g. Updated JsonSerializerHelper.cs to handle new behaviour explicitly -->
- <!-- e.g. Rewrote 3 custom JsonConverter<T> implementations -->

## Risk Assessment
| Risk | Level | Notes |
|------|-------|-------|
| <!-- Risk --> | High / Medium / Low | <!-- Notes --> |

## Testing
- [ ] All existing unit tests pass
- [ ] Integration tests pass end-to-end
- [ ] Manually tested via Swagger on staging (only in the scope of the library)
- [ ] Build output has no warnings

## Rollback Plan
<!-- e.g. Revert this PR, restore previous package version in .csproj, and redeploy. -->
<!-- in extreme cases, we need a separate document outlining step by step for fallbacks and rollback. -->

## References
- <!-- e.g. Official migration guide: https://... -->
- <!-- e.g. CVE advisory: https://... -->

## Notes for Reviewer
<!-- Call out the highest-risk files for focused review. -->
