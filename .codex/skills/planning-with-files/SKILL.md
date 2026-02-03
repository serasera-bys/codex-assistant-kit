---
name: planning-with-files
description: Use task_plan.md/findings.md/progress.md as durable memory. Enforce update discipline to prevent drift.
---

## Ensure planning files exist (create if missing)
- task_plan.md
- findings.md
- progress.md
- inbox.md

## Operating discipline (non-negotiable)
1) Create/refresh task_plan.md BEFORE execution.
2) After every meaningful step:
   - Write what happened to progress.md (timestamped).
3) Any new insight, command, or pitfall:
   - Write to findings.md.
4) Never repeat the same failing action.
   - Log error + attempt # in progress.md and findings.md.

## Templates (minimum)

### task_plan.md must contain
- Goal
- Constraints
- Assumptions
- Phases (checkbox list)
- Decision log
- Definition of Done

### findings.md must contain
- Key facts learned
- Copy-paste commands
- Gotchas/pitfalls

### progress.md must contain
- YYYY-MM-DD HH:MM — what you did, what changed, what worked/failed

## Execution gate
Still require GO before running commands or editing files.
