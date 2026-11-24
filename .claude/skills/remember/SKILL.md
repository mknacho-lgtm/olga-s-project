---
name: remember
description: Save a fact or preference to the project's memory file. Use when the user says "remember ..." or runs /remember.
---

Add the fact the user gave (in $ARGUMENTS or their message) to `docs/memory.md`:

1. Read `docs/memory.md`.
2. If the fact replaces or contradicts an existing entry, update that entry instead of adding a duplicate.
3. Otherwise add it as a new bullet, in short plain words.
4. If the fact is really a rule for one part of the project (e.g. only CSS), put it in the matching file in `.claude/rules/` or a folder `CLAUDE.md` instead, and say where you put it.
5. Tell the user in one line what you saved and where.
