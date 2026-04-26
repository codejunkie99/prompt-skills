# prompt-skills

40 expert-level prompt templates packaged as Claude Code skills. Drop the
folder into `~/.claude/skills/` (or any skill-loader path) and Claude will
trigger the right template based on your request.

Each skill is a single `SKILL.md` with frontmatter (`name`, `description`)
plus the prompt template, the variables it needs, and short usage guidance.
The templates work in any LLM that understands structured prompts —
Claude, ChatGPT, Gemini — but the trigger metadata is tuned for Claude
Code's skill loader.

## Layout

```
writing/         10 skills — articles, threads, emails, copy, headlines, more
analysis/        10 skills — SWOT, decision matrix, OKRs, pricing, risk, more
technical/        8 skills — architecture, code review, debugging, APIs, tests
productivity/     4 skills — weekly plan, learning, negotiation, habits
data/             3 skills — data interpretation, surveys, research synthesis
communication/    5 skills — hard conversations, feedback, pitches, apologies
```

## Use as a skill (Claude Code)

Symlink or copy the folders into your Claude Code skills directory:

```sh
ln -s "$(pwd)/writing" ~/.claude/skills/prompt-skills-writing
# repeat per category, or symlink the whole repo
```

Then ask Claude things like "draft an email for...", "write a thread about...",
"review this code", "build me an OKR set" — Claude will load the matching
skill and run its prompt template.

## Use as a raw prompt (any LLM)

Open the relevant `SKILL.md`, copy the `Prompt Template` section, replace
the `[BRACKETED]` variables with your inputs, and paste it into Claude,
ChatGPT, or Gemini.

## Source

Compiled from a public collection by [@eng_khairallah1](https://x.com/eng_khairallah1)
and converted to skill format.
