---
name: elevator-pitch-builder
description: Use when the user wants three energy-level variants of an elevator pitch (bold, conversational, data-driven). Triggers include "elevator pitch", "pitch this product", "30 second pitch".
---

# Elevator Pitch Builder

When the user supplies product, audience, context, and time budget, produce three pitch variants designed to be spoken aloud.

## Variables
- `[PRODUCT/SERVICE/IDEA]`, `[WHO I AM PITCHING TO]`, `[WHERE THIS PITCH WOULD HAPPEN]`, `[30 seconds / 60 seconds / 2 minutes]`

## Prompt Template

Build an elevator pitch for [PRODUCT/SERVICE/IDEA].

Audience: [WHO I AM PITCHING TO]
Context: [WHERE THIS PITCH WOULD HAPPEN — investor meeting, networking event, cold outreach]
Time: [30 seconds / 60 seconds / 2 minutes]

Structure:
1. Hook (one sentence that makes them want to hear more)
2. Problem (one sentence describing the pain — use their language, not yours)
3. Solution (one sentence describing what I do — not how it works, what it DOES for them)
4. Proof (one sentence of credibility — traction, results, notable client)
5. Ask (one sentence — what I want them to do next)

Generate 3 versions at different energy levels:
Version A: confident and bold
Version B: conversational and warm
Version C: data-driven and precise

Each version should feel natural when spoken aloud, not written.
