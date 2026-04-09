# Payout Gates from Delivery Gates

## Purpose

Payout should not be a separate truth system. It should be derived from DelEx delivery gates and the evidence required to pass them.

## Core rule

No payout decision should be final unless the relevant delivery gate evidence is present and the required approvals exist.

## Mapping

### Gate-aligned payout examples

#### Readiness baseline support
Possible reward condition:
- dependency evidence completed
- baseline package validated
- accountable owner accepts the evidence

#### Shadow readiness support
Possible reward condition:
- review surfaces and telemetry are present
- validation reports exist
- failure taxonomy or tuning evidence is linked

#### Controlled-action pilot support
Possible reward condition:
- rollback evidence exists
- policy signoff exists
- approved action subset is recorded
- exception queue is staffed

## Required payout evidence

A payout decision should be able to point to:
- linked engagement
- linked gate
- linked evidence artifacts
- approval record
- decision owner
- escrow reference, if used

## Stop conditions

Payout should be blocked when:
- gate evidence is incomplete
- approvals are missing
- severe exception or rollback invalidates completion
- work was superseded or rejected in gate review

## Why this matters

If payout ignores delivery gates, incentives can undermine governance. If payout derives from delivery gates, incentives reinforce the same control system.
