---
name: decision-matrix
description: Use when the user must choose between 2-4 options and wants a weighted, scored decision matrix with a recommendation. Triggers include "help me decide", "decision matrix", "weigh these options".
---

# Decision Matrix

When the user supplies options and context, build a weighted scoring matrix and recommend a choice.

## Variables
- `[LIST 2-4 OPTIONS]`
- `[RELEVANT BACKGROUND]` — budget, timeline, team, goals

## Prompt Template

I need to decide between these options: [LIST 2-4 OPTIONS]

Context: [RELEVANT BACKGROUND — budget, timeline, team, goals]

Build a decision matrix:
1. Identify the 5 most important criteria for this decision (ask me if unsure)
2. Weight each criterion by importance (must total 100%)
3. Score each option against each criterion (1-10)
4. Calculate weighted scores
5. Present as a formatted table

Then write a 2-paragraph recommendation that:
- Clearly states which option to choose and why
- Acknowledges the strongest argument for the runner-up
- Identifies the one condition that would change the recommendation
