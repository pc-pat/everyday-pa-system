# PA Domains — how PA handles each *kind* of work (installed reality)

A **domain module** is how PA does one kind of work — shopping, travel, bills, inbox. Domains are
**modular on purpose:** the PA Character (`modes/pa.md`, installed) stays small and universal;
each new kind of work is a **new file generated into the USER'S folder** — never an edit to the
Character, and **never a write into this installed plugin** (shipped files are read-only).

## The three layers
- **Character** (`modes/pa.md` (installed in the user's `modes/`)) — who PA is. Same for everyone.
- **Domain** (`shopping-domain.md` shipped as the worked example; new ones → the user's
  `modes/pa-<domain>.md`) — how PA does one kind of work. Generic, reusable.
- **Person** (the user's `memory/context/profile.md` + `preferences.md`) — their own settings.
A domain module names no specific person, address, or account — anything personal comes from the
Person layer or the task's `status.md`.

## How to add a new domain (do it exactly this way)
1. **Read the pattern:** `domain-template.md` (structure) + `shopping-domain.md` (worked example).
2. **Map the full pipeline** — the real stages end-to-end, not just the obvious one. (Shopping
   isn't "buy": it's Decide→Find→Verify→Price→Buy→Fulfill→Track→After-sale. Every domain has a
   true arc — find it.)
3. **Write the stage playbook** — what PA does at each stage, including verification and any
   safety-relevant specifics, honestly bounded by the tools the user has granted.
4. **Fill the four-slot setup questions** — Target · Constraints · Done & delivery · Must-knows
   (budget stays 4; see the shopping module for tuned wording).
5. **List the tools it leans on** — point at the user's `memory/tools-registry.md`; propose
   anything missing, one yes/no each.
6. **Keep it generic** — personal specifics live in the Person layer / the task.
7. **Save as `modes/pa-<domain>.md` in the user's folder**, create the first task at
   `Tasks/<task>/status.md` (from `task-template.md`), and note the new domain in the user's
   CLAUDE.md team table (PA's line).
8. **Verify honestly** — files written, references resolve, tools respond — report incl. partials.

`shopping-domain.md` is the worked pattern — read it before building a new one.
