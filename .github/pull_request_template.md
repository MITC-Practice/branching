<!--
PR Title format (suggested): type(scope): summary [ABC-123]
Examples: feat(payments): add 3DS step [PAY-742] | fix(api): null ref in order mapper
-->

## Context
<!-- One or two sentences: the problem, why now, and the user/business impact. -->

## Changes
<!-- Bullet list of notable changes (user-visible + key internal). Keep it crisp. -->
- 

## Test Plan
<!-- How did you verify it? Exact steps/commands, data used, and expected results. Link to CI if relevant. -->
- 

## Risks & Rollback
<!-- What can break and how will we mitigate it? Feature flag? Safe default? Rollback plan? -->
- 

## Impact
- **Performance:** <!-- expected latency/memory/DB/index impact; before/after metrics if known -->
- **Security/Privacy:** <!-- auth, PII, secrets, permission changes -->
- **Breaking changes:** <!-- none | describe + migration path -->

## Checklist
- [ ] Scope is small/focused (≈ ≤300 LOC diff) or justified
- [ ] Tests added/updated and passing (unit/integration/e2e as applicable)
- [ ] Docs/README/changelog updated (if user-facing)
- [ ] Telemetry/alerts/dashboards updated (observability in place)
- [ ] DB/schema/config changes are backward compatible and idempotent
