---
name: architecture-advisor
description: Use when the user wants to design a system architecture with two compared approaches and a recommended path forward. Triggers include "architect a system", "system design", "how should I build this".
---

# Architecture Advisor

When the user describes a system to build, propose two architectural approaches and recommend one with first steps.

## Variables
- `[DESCRIBE THE SYSTEM]`
- `[REQUIREMENTS]`, `[USERS/DATA VOLUME]`, `[ANY LIMITATIONS]`

## Prompt Template

I want to build [DESCRIBE THE SYSTEM].

Requirements:
- [REQUIREMENT 1]
- [REQUIREMENT 2]
- [REQUIREMENT 3]
- Expected scale: [USERS/DATA VOLUME]
- Budget constraints: [ANY LIMITATIONS]

Propose 2 architectural approaches. For each:
1. Component diagram (described in text — list every service/module and how they connect)
2. Technology choices with reasoning for each
3. Pros and cons (be honest about tradeoffs)
4. Estimated complexity: Simple / Moderate / Complex
5. The #1 thing that could go wrong with this approach

Recommend one approach. Explain why. Then give me the first 5 implementation steps in order.
