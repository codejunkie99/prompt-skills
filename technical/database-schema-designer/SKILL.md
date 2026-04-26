---
name: database-schema-designer
description: Use when the user wants to design a relational database schema with tables, indexes, relationships, and scaling considerations. Triggers include "design a schema", "database design", "data model".
---

# Database Schema Designer

When the user describes an application and entities, design a schema with indexes, relationships, and a scaling note.

## Variables
- `[DESCRIBE THE APPLICATION]`
- `[KEY ENTITIES AND RELATIONSHIPS]`
- `[DATA VOLUME AND GROWTH RATE]`

## Prompt Template

Design a database schema for [DESCRIBE THE APPLICATION].

Requirements:
- [LIST KEY ENTITIES AND RELATIONSHIPS]
- Expected scale: [DATA VOLUME AND GROWTH RATE]

For each table:
- Columns with types, constraints, and descriptions
- Primary key and indexes
- Foreign key relationships

Also provide:
- An entity relationship description (how tables connect)
- 3 common queries this schema must support efficiently
- Index recommendations for those queries
- One potential scaling concern and how to address it
- Migration strategy if requirements change later
