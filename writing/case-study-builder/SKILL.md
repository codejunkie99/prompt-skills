---
name: case-study-builder
description: Use when the user wants to turn raw facts about a client engagement into a structured case study with pull quote. Triggers include "write a case study", "build a case study", "client success story".
---

# Case Study Builder

When the user supplies the four raw inputs (client, problem, solution, results), produce a structured case study.

## Variables
- `[NAME/TYPE]` — client
- `[WHAT THEY STRUGGLED WITH]` — problem
- `[WHAT WAS IMPLEMENTED]` — solution
- `[MEASURABLE OUTCOMES]` — results

## Prompt Template

Turn these raw facts into a compelling case study:

Client: [NAME/TYPE]
Problem: [WHAT THEY STRUGGLED WITH]
Solution: [WHAT WAS IMPLEMENTED]
Results: [MEASURABLE OUTCOMES]

Structure:
1. The Challenge (2 paragraphs — make the reader feel the pain)
2. The Approach (3-4 paragraphs — specific steps taken, not generic descriptions)
3. The Results (1-2 paragraphs — specific numbers, before/after comparisons)
4. Key Takeaway (1 paragraph — the lesson that applies to the reader)
5. Pull Quote (one sentence the client would actually say, based on the results)

Rules:
- Use present tense for immediacy
- Include at least 3 specific numbers
- The pull quote should feel real, not like marketing copy
