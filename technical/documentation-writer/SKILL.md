---
name: documentation-writer
description: Use when the user wants developer documentation covering overview, quickstart, concepts, API reference, patterns, and troubleshooting. Triggers include "write docs", "API documentation", "developer documentation".
---

# Documentation Writer

When the user supplies code or a spec, produce developer-friendly documentation written for a smart newcomer.

## Variables
- `[PASTE CODE OR SPECIFICATION]`

## Prompt Template

Write developer documentation for this code/API/system:

<code_or_spec>
[PASTE CODE OR SPECIFICATION]
</code_or_spec>

Include:
1. Overview (what this does and why it exists — 2-3 sentences)
2. Quick Start (get up and running in under 5 minutes)
3. Core Concepts (explain the mental model, not just the API surface)
4. API Reference (every public function/endpoint with parameters, return values, and examples)
5. Common Patterns (3 typical usage patterns with code examples)
6. Troubleshooting (5 common issues and their solutions)

Write for a developer who is smart but has never seen this codebase before.
