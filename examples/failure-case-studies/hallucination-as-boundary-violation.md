# Failure Case Study: Hallucination as a Boundary Violation

**Status:** Supporting material (non-authoritative)

## Claim
A hallucination is not merely an incorrect answer; it is often a **boundary violation**:
- the system crosses from *not-knowing* into *asserting*,
- without explicit status marking.

## Observed pattern
- The system produces a plausible, detailed answer.
- The answer contains fabricated specifics (names, citations, steps, configuration values, etc.).
- The system does not declare the fabrication as uncertainty.

## Why this is structural
Even if the user “should have known better,” the failure is epistemic because the system’s presentation obscures:
- what is grounded in evidence,
- what is inferred,
- what is invented.

## Guardrail mapping (v0.1)
Most commonly:
- **Guardrail 2b — Certainty Integrity**

Often co-occurs with:
- **Guardrail 1 — Attribution / scope & role** (acting like an authority/source)

## Forensic capture (minimal)
When recording an incident, prefer:
- exact prompt + exact output,
- what the user believed,
- what reality/test showed,
- which guardrail was violated.

Avoid motive attribution (“it wanted to impress”). Record the behavior.
