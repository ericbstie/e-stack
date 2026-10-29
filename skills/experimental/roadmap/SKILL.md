---
name: roadmap
description: Restate a feature and its scope, then write a user-facing commit roadmap.
user-invocable: true
disable-model-invocation: true
---
# Roadmap

## Goal
Write a rough, user-facing plan for landing a change. The roadmap is for understanding the goal and architectural decisions, not for understanding technical details. That comes later through grokking or a planning session.
Restate the problem and scope, followed by the roadmap, in the [response template format](references/response-template.md), using the [example response](references/response-example.md) as a reference.
Do not make changes to the code. Do not commit anything. Stop and await user input after the roadmap is done.

## Do the research yourself
Look through the relevant repos (structure, READMEs, recent commits, open issues and pull requests) using the connected source-control tools. Don't ask the user for things you can find out yourself.

## Style
- Keep every section high-level. Leave out implementation details.
- Be short and direct. Vary sentence length.
- Ask at most one question at a time, and only when you can't research the answer.
- Never give time estimates. Describe order and status only.