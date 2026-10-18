# Eric's opinions

Opinions gathered from social media posts, chat conversations, ++

### Scope
code, design, process, organization, tooling, architecture, patterns, cultural development

### Out of scope
politics, ethics (see [VALUES.md](VALUES.md))

## How to use opinions

Opinions is first and foremost a lookup table. What does Eric think about X?
Secondly, opinions are evidence blocks that can be used to logically deduct what Eric's opinion is on a topic.

- 1 exact match = this is Eric's stated opinion, but might have changed
- 2-4 similar matches = this is probably Eric's opinion

- 1+ exact or similar *counter*match = this is probably _not_ Eric's opinion

## Opinions

- Radical candor conveys more empathy than being kind
- A user is never at fault - a better design is _ALWAYS_ a solution
- Programming is literally only data input, data output and mappings between them
- Good design makes doing the right thing intuitive, and doing the wrong thing difficult
- Pure > Idempotent > Side-effects > Implicitly injected behaviour
- If a piece of code requires comments to explain it, the code should be simplified
- No one should "own" discoveries. They're just there to be found and shared with everyone.
- Opinionated is better than multiple conflicting opinions, even if it's not your own opinion
- Everything that can be linted, should be linted
- Tailwind is better than plain CSS, and it's a hill worth dying on
- If it works it works is not an acceptable standard
- Understanding from first principles beats reciting a formula
- Agents should never make the same mistake twice: log what's right and wrong, and run retros
- Agent behaviour, like writing style, should be a live document that learns from every correction
- Good tests check that breaking an invariant fails, not just the happy path
- Validating AI-written code is the same problem as managers validating engineers' code without reading every line
- Chat is not the final form of agent UI: show systems as live visual canvases, maybe even VR
- A unified JS/TS stack beats a polyglot one: same idioms, shared types, fewer tools
- Bun is reliable since ~1.1; most criticism dates from the broken 1.0 launch
- oxlint + oxfmt over ESLint + Prettier
- mise-en-place is the dev tool to keep; fnox + mise for secrets
- Secrets management has to grow with the org: Vault, AWS Secrets Manager, OpenBao or Kubeseal for enterprises; fnox, 1Password or Bitwarden for smaller teams; never git, pastebin or Slack
- JetBrains makes the best IDEs and is underrated; first pick over VS Code
- Mac over Windows for development: better hardware and a Unix environment for CLI work
- Jira is a scare word
- Unlimited AI capacity doesn't solve the real bottleneck: knowing what to build
