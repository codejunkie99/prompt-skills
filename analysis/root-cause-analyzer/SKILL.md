---
name: root-cause-analyzer
description: Use when the user wants to drill past symptoms to a true root cause via the 5 Whys technique. Triggers include "root cause analysis", "5 whys", "why is this happening", "diagnose this problem".
---

# Root Cause Analyzer

When the user describes a problem, run a 5 Whys analysis and propose layered solutions.

## Variables
- `[DESCRIBE THE PROBLEM AND ITS SYMPTOMS]`

## Prompt Template

Here is a problem I am facing: [DESCRIBE THE PROBLEM AND ITS SYMPTOMS]

Perform a root cause analysis:
1. Ask "Why?" 5 times in sequence (the 5 Whys technique), going deeper each time
2. For each level, identify whether this is a symptom or a root cause
3. At the deepest level, identify the TRUE root cause
4. Propose 3 solutions — one for the surface symptom, one for the mid-level cause, and one for the root cause
5. Recommend which solution to implement and why

Do not accept my initial framing of the problem at face value. The real problem is often not the one I described.
