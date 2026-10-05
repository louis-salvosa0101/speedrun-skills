# speedrun-skills

Six Claude skills for building web apps on a timer:

- `setup` - initialize the project, instructions, stack, and dev server.
- `plan` - turn a challenge spec into prioritized build tasks.
- `slice` - implement and commit the next planned task.
- `add` - append a new feature to PLAN.md mid-project and build it.
- `polish` - prepare the finished app for submission.
- `frontend-design` - create distinctive, production-quality frontend interfaces.

Flow: `setup` → `plan` → `slice` (repeat) → `add` (when new features come up) → `polish`.

Install with:

```sh
npx skills@latest add louis-salvosa0101/speedrun-skills
```

`frontend-design` is vendored from [Anthropic's skills repository](https://github.com/anthropics/skills) under Apache-2.0; see `skills/frontend-design/LICENSE.txt`.
