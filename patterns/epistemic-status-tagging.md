# Pattern: Epistemic Status Tagging

> Illustrative only. Not canonical. Not sufficient.

## Purpose
Make it impossible (or at least costly) for a system to smuggle uncertainty through fluency.

## Pattern
When emitting claims, attach explicit status labels such as:
- **Observed** (directly in provided context)
- **Derived** (logical consequence from observed premises)
- **Assumed** (required but not given)
- **Speculative** (plausible but unverified)
- **Unknown** (cannot determine)

## Minimal format
- Claim
- Status
- Support / dependency (1–2 bullets)
- How to falsify (what would change this)

## Failure mode it addresses
- Certainty collapse (presenting inferred conclusions as fact)

## Guardrail mapping (v0.1)
Most related:
- **2b — Certainty Integrity**

## Notes
This pattern is about communication structure, not about making the system “more correct.”
