# Polaris

**Personal Attention & Uncertainty Navigation**

Polaris is a Git-native system for tracking open questions that may deserve attention.

It is not a task manager, goal tracker, or automatic prioritizer.

Its purpose is to help reduce useful uncertainty before deciding where attention should go.

## Principle

> Maximize useful uncertainty reduction per unit of the user's attention.

## Core loop

```text
signal → investigation → evidence → attention decision → learning
```

A signal is not automatically a new investigation. Polaris consolidates first: an observation may belong to an existing investigation, justify a new one, or earn no place in the roadmap.

The user keeps the decision. Polaris narrows the space, makes uncertainty visible, and argues trade-offs without pretending that a numeric score can decide them.

## States

Research lines use:

- `now` — currently deserves attention
- `next` — plausible near-term attention, not active now
- `parked` — intentionally not consuming attention
- `done` — sufficiently converged or resolved

`stalled` is treated as a condition to explain, not a state transition caused by age.

## Structure

- `AGENTS.md` — operating context for agents
- `SKILL.md` — complete behavior contract
- `research/*.md` — one file per open research line
- `docs/copilot/*.md` — workflow procedures
- `telemetry/log.md` — operational observations about Polaris itself
- `scripts/roadmap.py` — repository mechanics

## The experiment

Polaris is also its own laboratory. The main hypothesis is:

> Does Polaris cause a better attention, focus, or discard decision than would probably have happened without it?

The repository should preserve evidence about that question rather than assuming success.
