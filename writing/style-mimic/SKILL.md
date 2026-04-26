---
name: style-mimic
description: Use when the user wants to analyze an author's voice from samples and then write new content in that exact voice. Triggers include "write in my voice", "match this author's style", "ghostwrite in their style".
---

# Style Mimic

When the user supplies three samples from one author plus a new topic, analyze the style and produce 300 words in that voice.

## Variables
- `<sample_1>`, `<sample_2>`, `<sample_3>` — three writing samples
- `[NEW TOPIC]` — what to write about in the matched voice

## Prompt Template

Analyze these 3 writing samples from the same author:

<sample_1>[PASTE]</sample_1>
<sample_2>[PASTE]</sample_2>
<sample_3>[PASTE]</sample_3>

Identify:
- Sentence length patterns (short, mixed, long)
- Vocabulary level (simple, technical, mixed)
- Tone (formal, casual, authoritative, conversational)
- Structural habits (paragraph length, use of headers, bullet patterns)
- Signature phrases or patterns they repeat
- Things they consistently avoid

Then write a 300-word piece about [NEW TOPIC] that matches this author's exact style. The reader should believe the original author wrote it.
