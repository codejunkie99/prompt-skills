---
name: email-drafter
description: Use when the user wants to draft a focused, action-oriented email and compare two tonal versions. Triggers include "draft an email", "write an email to", "compose an email".
---

# Email Drafter

When the user requests an email draft, gather the situation and tone preferences, then produce two version variants.

## Variables
- `[DESCRIBE THE SITUATION, THE RECIPIENT, AND YOUR GOAL]`
- `[professional/casual/direct/diplomatic]`
- `[TONE 1]`, `[TONE 2]`

## Prompt Template

Draft an email for this situation: [DESCRIBE THE SITUATION, THE RECIPIENT, AND YOUR GOAL]

Tone: [professional/casual/direct/diplomatic]

Rules:
- Subject line: specific and action-oriented (not "Quick question" or "Following up")
- Opening: Get to the point in the first sentence. No "I hope this finds you well."
- Body: Maximum 3 short paragraphs. Each paragraph serves one purpose.
- Close: Clear next step or ask. The recipient should know exactly what you want them to do.
- Total length: Under 150 words

Generate 2 versions:
Version A: [TONE 1 — e.g., direct and assertive]
Version B: [TONE 2 — e.g., warm and collaborative]
