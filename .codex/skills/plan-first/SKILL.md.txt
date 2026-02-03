---
name: plan-first
description: Force planning mode and require GO before executing anything.
---

Follow AGENTS.md.

Output exactly:
- Intent
- Current state
- Assumptions
- Plan (max 6)
- Verification (commands + expected outputs)
- Risks & rollback (max 3)

Then STOP and ask: "Type GO to execute."
Do not run commands or edit files until GO.
Ask at most 2 clarifying questions, only if truly needed.
