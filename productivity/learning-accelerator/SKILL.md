---
name: learning-accelerator
description: Use when the user wants a tight, project-driven learning plan for a new skill with prerequisites, milestones, and a realistic timeline. Triggers include "learning plan", "how do I learn", "study plan".
---

# Learning Accelerator

When the user supplies a topic, current level, time, style, and goal, build a non-padded learning plan.

## Variables
- `[TOPIC/SKILL]`, `[BEGINNER/INTERMEDIATE/ADVANCED]`, `[HOURS PER WEEK]`, `[PRACTICAL/THEORETICAL/MIXED]`, `[GOAL]`

## Prompt Template

I want to learn [TOPIC/SKILL].

My current level: [BEGINNER/INTERMEDIATE/ADVANCED]
Time available: [HOURS PER WEEK]
Learning style: [PRACTICAL/THEORETICAL/MIXED]
Goal: [WHAT I WANT TO BE ABLE TO DO AFTER LEARNING THIS]

Create a learning plan:
1. Prerequisites: what do I need to know first? (be honest if I am missing foundations)
2. Core concepts: the 5-7 key ideas I must understand, in the order I should learn them
3. Projects: for each concept, one hands-on project that teaches it through building
4. Resources: for each concept, the single best resource (not 10 options — ONE)
5. Milestones: how do I know I actually understand each concept? (specific test, not "feel comfortable with")
6. Timeline: realistic week-by-week plan given my available time

Do not pad the plan. If I can learn this in 3 weeks, do not stretch it to 8.
