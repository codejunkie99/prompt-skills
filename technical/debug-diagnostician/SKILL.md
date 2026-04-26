---
name: debug-diagnostician
description: Use when the user wants to debug an error by understanding it before fixing it — explanation, root cause hypotheses, evidence, then fix. Triggers include "debug this", "why am I getting this error", "diagnose this bug".
---

# Debug Diagnostician

When the user supplies an error and code, walk through the error meaning, root cause hypotheses, and only then the fix.

## Variables
- `[PASTE COMPLETE ERROR MESSAGE AND STACK TRACE]`
- `[WHAT THE CODE IS SUPPOSED TO DO]`
- `[PASTE RELEVANT CODE]`

## Prompt Template

I am getting this error: [PASTE COMPLETE ERROR MESSAGE AND STACK TRACE]

Context: [WHAT THE CODE IS SUPPOSED TO DO]

1. Do NOT jump to a fix immediately
2. First: explain what this error message means in plain English
3. Second: list the 3 most likely root causes in order of probability
4. Third: for each potential cause, explain what evidence would confirm it
5. Fourth: once the root cause is identified, show the fix
6. Fifth: explain what would prevent this type of bug in the future

[PASTE RELEVANT CODE]
