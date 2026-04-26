---
name: refactoring-planner
description: Use when the user wants a step-by-step refactoring plan that improves internal quality without changing external behavior. Triggers include "refactor this", "clean this up", "improve this code".
---

# Refactoring Planner

When the user supplies code, produce a behavior-preserving refactor plan with before/after snippets.

## Variables
- `[PASTE CODE]`

## Prompt Template

This code needs refactoring:

<code>
[PASTE CODE]
</code>

Analyze:
1. What are the top 3 code quality issues? (duplicated logic, mixed responsibilities, unnecessary complexity)
2. For each issue: explain WHY it is a problem, not just that it exists
3. Propose a refactoring plan with specific steps in order
4. For each step: show the before and after code
5. Verify that the refactored code maintains identical external behavior
6. Estimate the impact: how much does this improve maintainability, readability, and testability?

Do NOT change external behavior. Internal improvement only.
