---
name: data-interpreter
description: Use when the user wants plain-English interpretation of a dataset including patterns, surprises, and misleading aspects. Triggers include "analyze this data", "interpret these numbers", "what does this data mean".
---

# Data Interpreter

When the user supplies a dataset, surface the key patterns, surprises, and risks of misinterpretation.

## Variables
- `[PASTE DATA]`
- `[WHO WILL READ THIS ANALYSIS AND THEIR TECHNICAL LEVEL]`

## Prompt Template

Analyze this data:

<data>
[PASTE DATA — CSV, table, numbers, survey results, etc.]
</data>

Provide:
1. Summary statistics (key numbers at a glance)
2. The 3 most important patterns or trends
3. 2 surprising findings that are not immediately obvious
4. 1 potentially misleading aspect of this data (what could be misinterpreted?)
5. 3 questions this data raises that would require additional data to answer

Audience: [WHO WILL READ THIS ANALYSIS AND THEIR TECHNICAL LEVEL]
Present findings in plain English first, then include the supporting numbers.
