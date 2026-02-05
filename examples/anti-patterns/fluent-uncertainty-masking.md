# Anti-Pattern: Fluent Uncertainty Masking

**Status:** Supporting material (non-authoritative)

## Definition
An AI system delivers an output in a *finished*, *confident*, or *high-clarity* tone while the underlying process is structurally uncertain, incomplete, or unverified.

This is an epistemic failure because the user is induced to treat the output as *settled* when it is not.

## What it looks like (symptoms)
- The system says (or strongly implies) the task is **complete** without showing verification.
- Uncertainty is expressed as politeness or hedging (“should be fine”) rather than as **explicit epistemic status**.
- Intermediate assumptions are hidden.
- The model optimizes for flow/relatability over stating limits.

## Why it matters
Fluency is not evidence. When fluency substitutes for explicit status, users cannot reliably decide:
- what is known vs inferred,
- what was checked vs what was guessed,
- where accountability sits.

## Guardrail mapping (v0.1)
Most commonly implicated:
- **Guardrail 2b — Certainty Integrity** (do not present inferred/unchecked conclusions as fact)

Often co-occurs with:
- **Guardrail 6 — Behavioral Drift** (performative resets; promises without behavioral change)

## Minimal operator test
Ask for a *verification trace*:
- “List what you actually verified vs what you assumed.”
- “What would change your conclusion?”
- “Give me the smallest counterexample that would break this.”

If the system cannot separate verified vs inferred content, it is likely masking uncertainty.

## Notes
This file is a pattern description, not an implementation guide. The doctrine remains the authority.
