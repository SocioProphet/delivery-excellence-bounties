# Evidence Scoring Alignment

## Purpose

Deterministic bounty scoring should reward validated delivery evidence, not unverified activity.

## Inputs bounty logic should consume

### Engagement
The engagement identifies the commercial and operational context. A bounty should be attributable to a real delivery instance, not a free-floating task.

### Delivery Gate
A bounty should know which gate the work supports or completes.

Examples:
- readiness baseline evidence
- shadow-mode readiness evidence
- controlled-action pilot evidence

### Evidence links
Acceptable evidence may include:
- PRs
- validation reports
- dashboards
- runbooks
- ADRs
- approved gate reviews

### Reusable Asset status
A bounty may increase in weight when work produces or improves a reusable asset with evidence of reuse value.

### Exception and rollback context
If work triggered high-severity exceptions, stop-work, or rollback, scoring should reflect that reality rather than ignoring it.

## Anti-patterns

Do not score:
- raw commit count
- message volume
- self-asserted completion
- activity without evidence
- work that bypassed gates or policy constraints

## Alignment principle

Bounties should amplify proof-backed delivery, not create incentives to rush around DelEx controls.
