---
name: survey-analyzer
description: Use when the user wants to analyze survey results for findings, consensus, division, surprises, and actionable recommendations. Triggers include "analyze survey", "survey results", "what does this survey show".
---

# Survey Analyzer

When the user supplies survey responses, produce a structured analysis with limitations.

## Variables
- `[PASTE SURVEY RESPONSES]`

## Prompt Template

Analyze these survey results:

<survey_data>
[PASTE SURVEY RESPONSES]
</survey_data>

Provide:
1. Key demographics/segments in the respondent pool
2. Top 5 findings ranked by significance
3. Areas of consensus (where respondents strongly agree)
4. Areas of division (where opinions are split)
5. Surprising findings that contradict common assumptions
6. Actionable recommendations based on the data (3 specific things to do)
7. Limitations of this data (sample size, bias, what we cannot conclude)
