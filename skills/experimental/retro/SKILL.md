---
name: retro
description: Extract learnings from a session. Use before finishing a task, ending a session or compacting.
user-invocable: true
disable-model-invocation: true
---
Analyse the and suggest improvements to the working process itself.

## Issues to look for

- Failed tool calls
- Assumptions that were later proven false
- Generated code with build errors
- Changes that introduced a bug
- Follow up correctional prompts by the user

## Tools to prevent future mistakes

In preferred order, enforce corrections on common mistakes through:
1. Better code / more intuitive code structure
2. Lint rules, tests, hooks
3. Documentation
4. AGENTS.md / CLAUDE.md / copilot-instructions.md
5. Skill file

Pick what makes sense first, but take priority into consideration.

## Tracking
Track each retro in a separate markdown file under ./retrospectives in this skill directory.

## Response format

```
## Changes since last retrospective
<bullet points; high level short sentence fragments (max 1 sentence)>

## This retrospective
<2-3 high-level sentences about what went well>

### Suggestion #<number>
<1-2 high level short sentences about the experienced problem/potential> 

<code block / specific extract of what went wrong>

<for complex problems only: 1-3 sentences on why it failed using plain language>

hint: ask for further explanations with /concise
```

Repeat the `Suggestion #<number>` section 0-3 times.
Write 0-5 bullet points on changes since last retrospective.
Drop any sections or parts that don't strictly give any meaningful new information.
Always link to the relevant code file and line number.
