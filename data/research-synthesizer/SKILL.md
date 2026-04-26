---
name: research-synthesizer
description: Use when the user has multiple research sources on a topic and wants genuine synthesis of themes, contradictions, and gaps — not separate summaries. Triggers include "synthesize this research", "compare these sources", "research synthesis".
---

# Research Synthesizer

When the user supplies multiple sources on a topic, produce true synthesis: themes, contradictions, gaps, and confident conclusions.

## Variables
- `[TOPIC]`
- `<source_1>`, `<source_2>`, `<source_3>` — sources to synthesize

## Prompt Template

I have gathered research from multiple sources on [TOPIC]:

<source_1>[PASTE OR SUMMARIZE]</source_1>
<source_2>[PASTE OR SUMMARIZE]</source_2>
<source_3>[PASTE OR SUMMARIZE]</source_3>

Synthesize:
1. Key themes across all sources (what do they agree on?)
2. Contradictions (where do sources disagree? who is more credible and why?)
3. Gaps (what questions remain unanswered?)
4. The 3 most important conclusions I can confidently draw
5. What I should research next to strengthen my understanding

Do not just summarize each source separately. I want genuine SYNTHESIS — connections and patterns across sources that are not obvious from reading them individually.
