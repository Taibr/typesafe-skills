# TypeSafe Agent Skills — maintained fork

This maintained fork of [TypeSafe AI's skills](https://github.com/typesafe-ai/skills)
preserves the original MIT license and attribution. It owns the existing
`typesafe-ai` provider skill for TypeSafe/Jev. Official API documentation remains
at [TypeSafe](https://docs.typesafe.ai); this fork is not an official supplier release.

Read [SKILL.md](skills/typesafe-ai/SKILL.md) or its [raw Markdown](https://raw.githubusercontent.com/Taibr/typesafe-skills/main/skills/typesafe-ai/SKILL.md).

Provider-independent decision methods for both applications and agent workflows
belong to the separately maintained [design-typed-decisions skill](https://github.com/Taibr/agent-skills-sync/blob/main/skills/general/design-typed-decisions/SKILL.md).
OpenAI capability guidance is a separate provider skill at that same shared repo.
Do not install a second Jev provider skill or copy the shared patterns into this fork.

## Install

Choose one installation method per agent. Do not install both a shared skill and
the Claude plugin into the same agent as duplicate TypeSafe providers.

### Compatible agents via skills.sh

```bash
npx skills add Taibr/typesafe-skills --skill typesafe-ai
```

Select your agent when prompted. Installation is project-local by default; add
`-g` for global scope. For an already-authorized global replacement on a host
using Codex, Claude Code and OpenClaw:

```bash
npx skills add Taibr/typesafe-skills --skill typesafe-ai -g --agent codex claude-code openclaw -y
```

This keeps the existing public skill name and changes its source to the maintained
fork. Verify the source entry and exact files after replacement; do not patch
global locks or install an additional `jev` alias. Use this route for all compatible
agents on such a host. Other supported agents can use the same portable provider
guidance; their installer/discovery support must be checked before claiming adoption.

### Alternative Claude Code plugin

```bash
claude plugin marketplace add Taibr/typesafe-skills
claude plugin install typesafe@typesafe-ai
```

The original marketplace and plugin names are retained. If the same marketplace
name already points upstream, use Claude's documented scoped marketplace source
replacement procedure and verify it first; do not register a duplicate marketplace.
This alternative is unnecessary when the shared-skills route is already in use.

## Use and update

Explicitly request the TypeSafe skill, for example:

> Use the TypeSafe skill to design Jev routing for incoming support tickets.

The shared-skills route exposes the runtime's discovered `typesafe-ai` invocation.
The alternative Claude plugin exposes `/typesafe:typesafe-ai`. Native AOC workflow
operations retain their existing ownership; skill installation does not enable
inference, grants, adapters or a new provider. Use the shared decision skill only
when explicitly requested.

Update the selected source through the supported installer; inspect upstream
changes and retain fork lineage/license when maintaining it. Do not silently
switch back to the official source. The [official installation guide](https://docs.typesafe.ai/agent-skill#installation)
explains supplier installation concepts; use this fork's repository for the
selected maintained source. Recheck exact source and native discovery after updates.

| Skill | Owner |
| --- | --- |
| [typesafe-ai](skills/typesafe-ai/SKILL.md) | TypeSafe/Jev live docs, primitive/API capability and provider-specific composition |
| design-typed-decisions | Shared methods in agent-skills-sync; separate explicit invocation |

## License

[MIT](LICENSE). Original TypeSafe attribution is retained.
