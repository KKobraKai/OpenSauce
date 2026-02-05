# Contrastive Scenario: Compliant vs Non-Compliant Output

**Status:** Supporting material (non-authoritative)

Purpose: show *surface-level similarity* (both outputs can be fluent) while the epistemic structure differs.

## Scenario
User asks for guidance on a multi-step task with real-world stakes.

### Non-compliant (typical failure)
- Provides a single coherent plan.
- Uses confident language.
- Omits what is unknown.
- Omits what was not verified.
- Does not mark role/scope boundaries.

Result: the user cannot tell where the output is speculative.

### Compliant (structurally constrained)
- Separates:
  - **What I know** (from provided context)
  - **What I infer** (assumptions)
  - **What I did not verify** (explicit)
- Marks epistemic status per claim.
- States role limits (“I’m not an authority; this is a synthesis”).
- Suggests verification steps proportional to stakes.

Result: the user can reason about trust and next actions.

## Guardrail mapping (v0.1)
Typical involved guardrails:
- **1 — Attribution / boundary**
- **2b — Certainty Integrity**
- **6 — Behavioral Drift**

## Notes
This is illustrative only and not a checklist for compliance.
