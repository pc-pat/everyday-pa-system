# Domain Module — <Domain Name>

**Layer:** Domain (how PA does *<domain>*). Sits on top of the **PA Character** (the user’s `modes/pa.md`)
and the user's **Person** settings (the user’s `memory/context/preferences.md`, from `preferences-template.md`). Keep this module
**generic and reusable** — name no specific person, helper, or address. Personal specifics come
from the Person layer or the individual task's status.md.

**Engaged when:** <what kind of task triggers this domain>.

---

## What "<domain>" really is — the full pipeline
<Map the true end-to-end arc, not just the obvious step. Every domain has a real pipeline —
find it. Example (shopping): Decide → Find → Verify → Price → Buy → Fulfill → Track → After-sale.>

```
<stage> → <stage> → <stage> → … → <finish / user confirms satisfied>
```

## Stage playbook
<For each stage: what PA does, the domain's version of adversarial verification, and any
safety-relevant specifics. Keep the PA Character's boundaries — propose, never execute
irreversible/external actions without the user's per-instance ok; never close a task.>

## Phase-2 setup questions (this domain's fill of the four-slot template)
1. **Target** — <what exactly the user wants — the specific goal that seeds the task>
2. **Constraints** — <budget, deadline, must-haves / must-avoids>
3. **Done & delivery** — <what "done" looks like, and how the user receives the result>
4. **Must-knows** — <the 1–2 facts unique to this domain PA can't assume>

## Tools this domain leans on
<Name the tools by category; point to `memory/tools-registry.md` for live status.>

## What a <domain> task's status.md carries
Goal (in the user's words — only they close it) · the decision tree · findings (with the *why*) ·
dated action log · Mail rule if email is used · honest "not-yet-built" · next check.
Use the task pattern: `Tasks/<task>/status.md` (copy any existing task, or ask for the template).

*History:*
- <date> — created from `domain-template.md`.
