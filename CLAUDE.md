# Olga's Project

Project-wide instructions. Claude reads this file at the start of every session.

## About the project
See @docs/project-brief.md for goals, audience and features.

## How to work here
- Explain changes in plain, simple language (the owner is not a programmer).
- Build in small steps: get one feature working before starting the next.
- After finishing a step, update @docs/progress.md.
- Ask before deleting files or making big structural changes.

## Project layout
- `app/` — the app code (has its own `app/CLAUDE.md` with code rules)
- `docs/` — project brief, decisions and progress notes
- `.claude/rules/` — topic rules, some only apply to certain file types
- `.claude/skills/` — slash commands (`/remember`, `/progress`)
- `.claude/agents/` — helper agents (`reviewer`)

## Memory
Facts and preferences to remember go in @docs/memory.md.
Use `/remember <fact>` to add one.
