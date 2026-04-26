---
name: okr-builder
description: Use when the user wants to draft Objectives and Key Results for a team, individual, or company with measurable targets and confidence levels. Triggers include "write OKRs", "OKR planning", "set quarterly goals".
---

# OKR Builder

When the user supplies the scope and time period, draft 3 Objectives with measurable Key Results.

## Variables
- `[TEAM/INDIVIDUAL/COMPANY]`
- `[TIME PERIOD]`
- `[CURRENT SITUATION]`

## Prompt Template

Help me create OKRs for [TEAM/INDIVIDUAL/COMPANY] for [TIME PERIOD].

Context: [CURRENT SITUATION — where we are, where we want to go, what resources we have]

For each Objective (suggest 3):
- The Objective: ambitious but achievable, qualitative, inspiring
- 3-4 Key Results: specific, measurable, time-bound
- For each Key Result: the current baseline, the target, and how you would measure it
- A confidence level (1-10) that this Key Result is achievable in the timeframe

Flag any Key Results that might conflict with each other.
