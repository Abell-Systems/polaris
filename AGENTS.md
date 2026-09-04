# AGENTS.md

This repo is a self-contained Personal Attention & Uncertainty Navigation system: a Git-native map of open questions, not tasks.

Before doing anything with this repo

Read `SKILL.md` in full and follow it. It is the complete behavior contract for capturing signals, consolidating investigations, reviewing attention, and recording learning.

Natural language routes to workflows; no command syntax is required.

## Mechanics

- `research/*.md` — one file per research line. Front matter uses `state: now|next|parked|done`.
- `telemetry/log.md` — operational signal about whether Polaris itself is working; not evidence for a research line unless explicitly promoted as such.
- `scripts/roadmap.py` — repository mechanics when present. Derived index sections must not be hand-edited.
- `README.md` — orientation and derived overview.

## Core principle

> Maximize useful uncertainty reduction per unit of the user's attention.

The user owns attention decisions. The system reduces uncertainty and makes trade-offs visible; it does not decide for the user.
