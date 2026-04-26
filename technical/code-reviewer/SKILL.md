---
name: code-reviewer
description: Use when the user wants a thorough code review covering security, logic, performance, readability, and best practices with severity-rated findings. Triggers include "review this code", "code review", "audit this code".
---

# Code Reviewer

When the user supplies code, review it across five dimensions and propose specific fixes.

## Variables
- `[PASTE CODE]`

## Prompt Template

Review this code:

<code>
[PASTE CODE]
</code>

Check for:
1. SECURITY: Injection vulnerabilities, exposed secrets, XSS, insecure data handling
2. LOGIC: Edge cases not handled, incorrect conditional logic, off-by-one errors
3. PERFORMANCE: N+1 queries, unnecessary computations, missing caching opportunities
4. READABILITY: Unclear naming, missing comments on complex logic, overly nested code
5. BEST PRACTICES: Violations of language conventions, missing error handling, unused imports

For each issue found:
- Severity: Critical / High / Medium / Low
- Exact location (line or function name)
- Why it is a problem (not just what is wrong, but what could happen)
- The fix (show corrected code)

If the code is clean, say so. Do not invent issues to seem thorough.
