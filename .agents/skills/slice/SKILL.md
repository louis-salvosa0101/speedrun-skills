---
name: slice
description: Use to build the next task from PLAN.md end to end, test it, and commit.
---

# Build one planned slice

1. Read `PLAN.md` and select the first unchecked task in build order. If no unchecked task remains, report that and stop.
2. Implement only that task end to end, including data, API, and UI as needed. Use the `frontend-design` skill for UI work.
3. Run the app and the relevant checks, fix errors caused by the change, and confirm the task works.
4. Mark that task complete in `PLAN.md` and commit the change with a clear message. Do not start another task.
5. Report in exactly two lines what works and what was committed.
