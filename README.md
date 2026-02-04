# codex-assistant-kit

A small set of Codex skills and SOPs to make workflows more reliable by forcing planning, explicit execution gates, and lightweight durable memory.

## What this is for
- Stress-testing repeatable assistant workflows
- Capturing ideas quickly without turning them into full plans
- Enforcing a deliberate plan-then-execute cadence

## What is inside
- `capture-idea`: capture a raw idea into `inbox.md` with one short next action
- `plan-first`: enforce a planning output and require `GO` before execution
- `planning-with-files`: use `task_plan.md`, `findings.md`, `progress.md`, `inbox.md` as durable memory

## How to use
- Open a project where you want these rules enforced
- Copy the `.codex/skills` folder into that project or install the skills into your Codex home
- Invoke a skill by name when you want that behavior

## Design notes
These SOPs intentionally trade speed for reliability. If you want a lightweight mode for small tasks, use `capture-idea` or apply the “light mode” rules in `planning-with-files`.

## License
TBD
