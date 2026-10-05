---
name: add
description: Use when the user wants a new feature or requirement mid-project. Appends it to the existing PLAN.md as small tasks, then builds the first new task. Never overwrites existing tasks. Never asks questions.
---

# Add

Add a new feature to an in-progress project without disturbing existing work.

1. Read AGENTS.md, PLAN.md, NOTES.md, and the last 10 lines of `git log --oneline`.
2. Append the requested feature to PLAN.md as one or more small tasks (10 minutes or less each, as unchecked checkboxes).
   - Put it under MUST-HAVE if the original spec requires it, otherwise under NICE-TO-HAVE.
   - If the user says it is urgent, place it as the next unchecked task.
   - Never rewrite, reorder, or uncheck existing tasks. Keep completed checkboxes as they are.
3. Record any assumptions in NOTES.md.
4. Build the first new task end to end (data, API, UI using the frontend-design skill), run it, fix errors, tick it off, and git commit with a clear message.
5. Do not start the next task. Report in 2 lines what was added and what works.
6. If PLAN.md does not exist, tell the user to run the plan skill first and stop.
