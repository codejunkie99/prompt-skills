---
name: api-designer
description: Use when the user wants to design a REST API with endpoints, schemas, error formats, pagination, versioning, and security. Triggers include "design an API", "REST API design", "API spec".
---

# API Designer

When the user describes a system or feature, design a RESTful API with consistent error handling and security.

## Variables
- `[DESCRIBE THE SYSTEM/FEATURE]`

## Prompt Template

Design a REST API for [DESCRIBE THE SYSTEM/FEATURE].

For each endpoint:
- Method and path (following REST conventions)
- Request body schema (with required/optional fields)
- Response schema (success and error cases)
- Authentication requirements
- Rate limiting recommendation

Also include:
- Error response format (consistent across all endpoints)
- Pagination approach for list endpoints
- Versioning strategy
- 3 potential security concerns and how to address each

Present as a formatted API reference document.
