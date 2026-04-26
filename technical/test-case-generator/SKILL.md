---
name: test-case-generator
description: Use when the user wants comprehensive test coverage across happy path, edge cases, errors, security, and performance. Triggers include "generate tests", "test cases for", "write unit tests".
---

# Test Case Generator

When the user supplies a function or feature, generate test cases across five categories with rationale.

## Variables
- `[PASTE CODE OR DESCRIBE THE FEATURE]`

## Prompt Template

Generate comprehensive test cases for this function/feature:

<code_or_description>
[PASTE CODE OR DESCRIBE THE FEATURE]
</code_or_description>

Test categories:
1. HAPPY PATH: 3 tests for normal, expected usage
2. EDGE CASES: 5 tests for boundary conditions, empty inputs, maximum values
3. ERROR CASES: 3 tests for invalid inputs, missing data, system failures
4. SECURITY: 2 tests for injection attempts, unauthorized access
5. PERFORMANCE: 1 test for behavior under load or with large datasets

For each test:
- Test name (descriptive)
- Input
- Expected output
- Why this test matters
