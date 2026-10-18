# MIT Skills Collage

A hand-picked collage of the most-starred **MIT-licensed** agent skills on GitHub (`SKILL.md` format, works with Claude Code and other coding agents). Each skill folder keeps its original author's `LICENSE`.

## Included (vendored in `skills/`)

| Folder | Upstream | Stars* | Author | What it gives you |
|---|---|---|---|---|
| `skills/superpowers` | [obra/superpowers](https://github.com/obra/superpowers) | 301k | Jesse Vincent | Brainstorm → plan → TDD → review workflow, 15 skills |
| `skills/agent-skills` | [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) | 108k | Addy Osmani | Production engineering skills, 25 skills |
| `skills/taste-skill` | [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) | 99k | Leonxlnx | Art direction and UI taste for coding agents |
| `skills/humanizer` | [blader/humanizer](https://github.com/blader/humanizer) | 58k | Siqi Chen | Removes signs of AI-generated writing |
| `skills/obsidian-skills` | [kepano/obsidian-skills](https://github.com/kepano/obsidian-skills) | 50k | Steph Ango | Obsidian CLI, Markdown, Bases, Canvas |

## Also worth installing (MIT, too large to vendor)

| Upstream | Stars* | Notes |
|---|---|---|
| [tt-a1i/archify](https://github.com/tt-a1i/archify) | 85k | Interactive architecture diagrams |
| [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) | 65k | Researches a topic across Reddit, X, YouTube, HN |
| [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) | 53k | Scientific research skills (~470 MB repo) |
| [alirezarezvani/claude-skills](https://github.com/alirezarezvani/claude-skills) | 28k | 380 skills and plugins |
| [Jeffallan/claude-skills](https://github.com/Jeffallan/claude-skills) | 12k | 67 full-stack developer skills |

\*Stars as of 2026-10-18, licenses checked through the GitHub API. Repos without a license (e.g. `anthropics/skills`, `ComposioHQ/awesome-claude-skills`) were left out on purpose.

## Install

```bash
git clone https://github.com/Kutlu24/mit-skills-collage
cp -r mit-skills-collage/skills/humanizer ~/.claude/skills/
```

Copy any folder from `skills/` into `~/.claude/skills/` (user-wide) or `.claude/skills/` (per project). Some skills in the same upstream group reference each other, so copy a group's skill folders together.

## Licensing

This repo's own files (README, NOTICE) are MIT. Every vendored skill is the work of its author and stays under their MIT license, included next to the files. See [NOTICE](NOTICE). Open an issue and I'll remove anything on request.
