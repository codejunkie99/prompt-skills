---
name: feedback-giver
description: Use when the user wants to draft spoken feedback using observation/impact/expectation/support framework. Triggers include "give feedback", "feedback to my report", "performance feedback".
---

# Feedback Giver

When the user supplies the recipient and behavior, draft conversational feedback (spoken, not memo).

## Variables
- `[WHO]`, `[WHAT]`, `[POSITIVE RELATIONSHIP? RECURRING ISSUE? FIRST TIME?]`, `[SUPPORTIVE / DIRECT / SERIOUS]`

## Prompt Template

I need to give feedback to [WHO — role, relationship] about [WHAT — specific behavior or work].

Context: [POSITIVE RELATIONSHIP? RECURRING ISSUE? FIRST TIME?]

Draft the feedback using this framework:
1. Observation (what specifically I observed — behavior, not character)
2. Impact (how it affected the team, the project, or the outcome — specific, not vague)
3. Expectation (what I would like to see going forward — specific and achievable)
4. Support (what I will do to help them succeed — not just demand change)

Tone: [SUPPORTIVE / DIRECT / SERIOUS]

Write it as spoken words, not an email. This is a conversation, not a memo.
