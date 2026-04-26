---
name: risk-assessor
description: Use when the user wants a pessimistic risk assessment of a project or decision with probability/impact ratings, early warning signs, and mitigations. Triggers include "risk assessment", "what could go wrong", "pre-mortem".
---

# Risk Assessor

When the user describes an initiative, surface the 7 most likely risks and plot them on a 2x2.

## Variables
- `[DESCRIBE THE INITIATIVE/DECISION/PROJECT]`

## Prompt Template

I am about to [DESCRIBE THE INITIATIVE/DECISION/PROJECT].

Perform a risk assessment:
1. List the 7 most likely risks (things that could go wrong)
2. For each risk:
   - Probability: High / Medium / Low
   - Impact if it occurs: High / Medium / Low
   - Early warning sign (how would I detect this risk materializing?)
   - Mitigation strategy (what would I do to prevent it?)
   - Contingency plan (what would I do if it happens anyway?)
3. Plot all risks on a 2x2 matrix (probability vs. impact)
4. Identify the top 3 risks I should actively monitor

Be pessimistic. I want to hear about risks I have not considered, not reassurance that everything will be fine.
