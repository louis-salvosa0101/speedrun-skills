---
name: setup
description: Use at the start of a project to set up agent instructions and the tech stack. Creates AGENTS.md, CLAUDE.md, and scaffolds the stack. Never asks questions.
---

# Set up a timed web app project

1. Choose the stack from the user's argument when provided. Otherwise use Next.js, TypeScript, Tailwind CSS, and SQLite with `better-sqlite3` or Prisma.
2. Inspect the current folder. If a project already exists, keep its stack and skip scaffolding. Otherwise scaffold non-interactively; for the default stack, use `npx create-next-app@latest . --ts --tailwind --app --eslint --use-npm --yes`.
3. Write `AGENTS.md` with the selected stack, the actual dev/build/test commands, the actual folder structure, and these project rules:
   - Optimize for speed over perfection.
   - Make reasonable assumptions instead of asking clarifying questions; record them in `NOTES.md`.
   - Complete one feature per task, then run the app, fix errors, and commit the change.
   - Add dependencies only when essential.
   - Every UI flow needs loading, empty, and error states where applicable.
   - Use the `frontend-design` skill for all UI work.
4. Write `CLAUDE.md` containing only `@AGENTS.md`.
5. Initialize Git if needed, create the first commit, then start the dev server once and confirm it boots. Stop the server after confirmation.
6. Report the stack and the dev/build/test commands in exactly three lines.
