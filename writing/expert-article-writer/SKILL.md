---
name: expert-article-writer
description: Use when the user wants to write a long-form article, blog post, or essay with publishable, expert-level depth and structure. Triggers include "write an article", "draft a long-form post", "essay about", or any request for ready-to-publish editorial content.
---

# Expert Article Writer

When the user requests an expert-level article, gather the variables below (or ask for any missing) and produce output following the prompt template verbatim.

## Variables
- `[WORD COUNT]` — target word count
- `[TOPIC]` — article subject
- `[WHO THEY ARE and WHAT THEY KNOW]` — audience profile
- `[YOUR UNIQUE TAKE]` — angle that differentiates from existing coverage

## Prompt Template

You are a senior content strategist who has written for top-tier publications.

Write a [WORD COUNT]-word article about [TOPIC].

Audience: [WHO THEY ARE and WHAT THEY KNOW]
Angle: [YOUR UNIQUE TAKE — what makes this different from every other article on this topic]

Structure:
- Hook: Open with a bold claim or surprising fact. No generic introductions.
- Problem: Why the current way of thinking about this topic is wrong or incomplete.
- Framework: Present your argument in 3-5 named sections with clear headers.
- Evidence: Each section must include one specific example, case study, or data point.
- Action: End with 3 specific things the reader can do THIS WEEK.

Rules:
- Paragraphs: 3 sentences maximum
- No filler phrases ("it is important to note", "in today's world")
- No hedge words ("might", "could potentially", "it seems like")
- Every claim must be specific, not vague
- Bold the most important sentence in each section

This article should be good enough to publish without editing.
