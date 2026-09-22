# FocusFlow AI Planner

**Status: Concept brief.** The features below are proposed; this repository does not yet contain an implemented application or measured results.

[Portfolio](https://eskstrom.github.io/) · [Related projects](https://eskstrom.github.io/?category=tools-play#library)

## Product brief

An AI-assisted planning tool that turns goals and tasks into a realistic weekly schedule, protects deep-work blocks, tracks plan-versus-actual, and generates a reflection.

## Design focus

A weekly planning concept that respects availability and user overrides.

## Proposed scope

- Task capture with duration, deadline, energy level, and priority.
- Schedule generator constrained by availability.
- Daily plan-versus-actual check-in.
- Weekly insight: overcommitment, task rollover, and focus-block completion.

## Validation targets

- Schedule respects explicit constraints.
- Users can override every AI suggestion.

## Potential implementation

Python/FastAPI or TypeScript/Next.js, SQLite, calendar-style UI.

## Guardrails

Keep user data local in the demo and do not make wellness or productivity guarantees.

[Implementation planning notes](notes/IMPLEMENTATION-NOTES.md)
