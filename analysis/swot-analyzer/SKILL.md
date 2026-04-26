---
name: swot-analyzer
description: Use when the user wants a specific, weighted SWOT analysis of a company, product, or strategy with a strategic priority recommendation. Triggers include "SWOT analysis", "strengths and weaknesses", "strategic analysis".
---

# SWOT Analyzer

When the user supplies a target, produce a specific SWOT with impact ratings and a single top priority.

## Variables
- `[COMPANY/PRODUCT/STRATEGY]`

## Prompt Template

Perform a comprehensive SWOT analysis of [COMPANY/PRODUCT/STRATEGY].

For each quadrant (Strengths, Weaknesses, Opportunities, Threats):
- List 5 specific items (not generic — tied to THIS specific situation)
- For each item: one sentence explaining WHY it belongs in this quadrant
- Rate each item's impact: High / Medium / Low

Then provide:
- The #1 strategic priority based on this analysis (one sentence)
- The biggest risk if this priority is ignored (one sentence)
- The first action to take this week (one specific, actionable step)
