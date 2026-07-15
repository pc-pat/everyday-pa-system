# PA Installer — adding a domain of work (re-run flow; additive, never destructive)

**When this runs:** the user already finished onboarding (STATE.md complete) and wants PA to help
with a new kind of work — travel, bills, inbox, bookings, anything. Trigger: "Set up my Everyday PA System" on a completed system, or "PA, help me with ‹domain› too."

## The three layers (never mix them)
- **Character** — who PA is, universal conduct → the user's `modes/pa.md` (installed at setup; read-only pattern).
- **Domain** — starter how-to for one kind of work → shipped modules (`shopping-domain.md` is the
  worked example); new ones are assembled from `domain-template.md` per `domains-readme.md` — never
  invented cold.
- **Person** — the user's identity + settings → THEIR `memory/context/profile.md` + `preferences.md`.
  Never re-interview for these; only change a setting if the user asks.

## Flow (bounded, like everything)
1. **Detect state:** profile + preferences exist → skip all universal questions. Greet, confirm the
   new domain in one line.
2. **Domain setup — budget: the four slots only:** Target · Constraints · Done & delivery ·
   Must-knows. (A shipped domain module may refine the wording; the budget stands.)
3. **Tools:** propose only what THIS domain concretely benefits from, one yes/no each, with the
   reason. Declines are recorded in preferences and worked around honestly.
4. **Create the work home:** `Tasks/<domain-or-task>/status.md` from `task-template.md`, seeded
   from the Target answer.
5. **Verify honestly:** files written · references resolve · granted tools respond. Read back a
   plain summary including anything still pending. Hand off: *"Say 'PA, go' and I begin."*

## Never
Never overwrite preferences or existing task folders · never edit shipped references · never connect
a tool or schedule anything without an explicit yes · never mark the setup "Done" — it's "ready for
your ok."
