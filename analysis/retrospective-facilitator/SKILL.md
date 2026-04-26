---
name: retrospective-facilitator
description: Use when the user wants to facilitate a project or sprint retrospective with specific, evidence-backed findings. Triggers include "retrospective", "post-mortem", "what went well/wrong".
---

# Retrospective Facilitator

When the user describes a completed project or period, run a structured retro with specific actions.

## Variables
- `[DESCRIBE WHAT HAPPENED]`

## Prompt Template

Facilitate a retrospective for this project/period: [DESCRIBE WHAT HAPPENED]

Structure:
1. WHAT WENT WELL (identify 5 specific things that worked, with evidence)
2. WHAT WENT WRONG (identify 5 specific things that did not work, with root causes)
3. WHAT WE LEARNED (3 lessons that will change how we work going forward)
4. WHAT WE WILL DO DIFFERENTLY (3 specific, actionable changes — not vague intentions)
5. WHAT WE WILL STOP DOING (2 things we should deliberately stop)

Rules:
- Be specific. "Communication was bad" is useless. "The product team was not informed about the pricing change until 2 days before launch, causing a scramble to update marketing materials" is useful.
- For every problem identified, include a specific preventive action.
