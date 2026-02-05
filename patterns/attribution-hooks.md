# Pattern: Attribution Hooks

> Illustrative only. Not canonical. Not sufficient.

## What “hook” means (plain language)
A **hook** is a short, repeatable sentence fragment you can attach to an answer.
It “hooks” the answer to an explicit epistemic anchor:
- **Source:** where the claim came from
- **Boundary:** what is not known / not checked
- **Role:** what kind of act this is (summary, hypothesis, plan)

The goal is not a cautious tone. The goal is to prevent **fluency** from being mistaken for **evidence**.

## Why call them “hooks”
Because they are **small**, **attachable**, and **reusable**.
You can prepend them to almost any response without rewriting the whole answer.

A hook should be:
- short enough to say every time,
- specific enough to reduce ambiguity,
- boring enough to be trusted.

## Hook examples (copy/paste)
Use one (or more) of these at the top of an answer.

### Source hooks (where did this come from?)
- “Based only on what you provided in this thread, …”
- “I’m inferring this from your description; I did not look it up.”
- “This is a synthesis of the text/logs you pasted; I’m not adding external facts.”

### Boundary hooks (what didn’t I check?)
- “I did not verify this against primary sources.”
- “I can’t confirm X from the available evidence.”
- “I may be missing constraints because I don’t have Y.”

### Role hooks (what am I doing right now?)
- “I’m proposing a hypothesis / next check, not asserting a fact.”
- “I’m summarizing; if this is wrong, the source text is the authority.”
- “I’m outlining options; you will need to validate before acting.”

## Descriptive examples (good vs bad)

### Bad (epistemically ambiguous)
“Here’s what happened and why. The system definitely violated the standard. Do X to fix it.”

Why it’s bad:
- No separation between **observation** and **interpretation**.
- No statement of what was verified vs assumed.
- Mixes analysis with prescriptions.

### Better (epistemically explicit)
“Based only on what you provided in this thread, **I observe** A and B.
I’m **inferring** C as a plausible explanation; I did not verify it against external sources.
I cannot confirm D from the available evidence.
I’m acting as an analyst to propose next checks, not as an authority on ground truth.”

What improved:
- Observations are distinguished from inferences.
- Boundaries are explicit.
- The role is stated.

## Guardrail mapping (v0.1)
Most related:
- **Guardrail 1 — Attribution / boundary**

Also supports:
- **Guardrail 2b — Certainty Integrity** (forces marking unverified content)

## Notes
This is a communication pattern, not a compliance mechanism.
