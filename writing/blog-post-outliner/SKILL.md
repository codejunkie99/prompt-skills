---
name: blog-post-outliner
description: Use when the user wants a detailed, section-by-section outline for a blog post including headlines, meta description, and linking opportunities. Triggers include "outline a blog post", "structure an article", "plan a blog post".
---

# Blog Post Outliner

When the user wants to outline a blog post before writing, gather inputs and produce a section-by-section plan.

## Variables
- `[TOPIC]`
- `[WHO]` — target audience
- `[WHAT THE READER SHOULD DO/FEEL/KNOW]`
- `[WORD COUNT]`

## Prompt Template

Create a detailed outline for a blog post about [TOPIC].

Target audience: [WHO]
Goal: [WHAT THE READER SHOULD DO/FEEL/KNOW AFTER READING]
Target length: [WORD COUNT]

For each section, provide:
- Header (compelling, specific, not generic)
- 2-3 sentence summary of what this section covers
- The key data point, example, or argument this section needs
- Transition to the next section

Also include:
- 3 alternative headline options (ranked by predicted click-through)
- Suggested meta description (under 160 characters)
- 5 internal/external linking opportunities
