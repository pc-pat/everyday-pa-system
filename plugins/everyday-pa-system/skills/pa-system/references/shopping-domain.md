# Domain Module — Shopping

**Layer:** Domain (how PA does *shopping*). Sits on top of the **PA Character** (the user’s `modes/pa.md`)
and the user's **Person** settings (the user’s `memory/context/preferences.md`, from `preferences-template.md`). This module is
**generic and reusable** — it names no specific person, helper, or address. Anything personal
(who forwards packages, where things ship) comes from the Person layer or the task's own status.md.

**Engaged when:** a user's task is about acquiring a physical or digital product.

---

## What "shopping" really is — the full pipeline
Shopping is not "buy and ship." It's a pipeline, and the user may need help at any point:

```
Decide what to buy → Find where it's sold → Check it's genuine →
Get the best price → Buy it (user approves) → Get it to the user →
Track it → After-sale (returns · warranty · are they happy)
```

PA covers the whole line by default. Map where the user actually is on it (they may arrive at
"help me decide," or already know the item and need "help me get it safely").

## Stage playbook
1. **Decide** — research and compare real options against the user's stated need; recommend,
   with the *why* (and why the rejected ones lost). Don't present endless menus once they ask
   for a pick.
2. **Find** — where it's genuinely sold: official site, authorized retailers, local stores,
   in-country vs international. Note stock and store pick-up availability.
3. **Verify it's genuine** — actively try to disprove legitimacy. Check the seller/site against
   the brand's official channels; watch for counterfeit and scam signals (unlocalized legal
   boilerplate, no named entity, prices too good, no real warranty). Use the brand's own support
   to confirm when in doubt. *(deep-research skill is built for this.)*
4. **Price / timing** — compare prices; verify a discount is real (check the anchor price, the
   seller's warranty, the deal's actual terms — a headline "% off" is often on the wrong SKU or
   an inflated anchor). Watch for genuine price drops / restocks; weigh a real deadline.
5. **Buy** — **purchase protocol:** PA researches, verifies, and hands the user the exact link
   and says *"now's the time."* **The user always completes the purchase themselves. PA never
   enters payment or checks out.** Handle cross-border realities (import rules, permits, taxes)
   as findings to surface, not actions to take.
6. **Get it to the user (fulfillment)** — options, in the user's order of preference: **shipped
   to them · store pick-up · forwarded** (a package-forwarding service, or on to another
   person/country). Personal specifics (which service, whose address) come from the Person layer
   or the task status.md.
7. **Track** — once an order exists, confirm shipment and delivery status.
8. **After-sale** — returns, exchanges, warranty, and a **satisfaction check**: the task is not
   done until the user has the item, has tried it, and confirms they're satisfied. **Only the
   user closes it.**

## Phase-2 setup questions (shopping's fill of the four-slot template)
When the installer or PA starts a shopping task, ask:
1. **Target** — What are you trying to buy first?
2. **Constraints** — Any deadline or budget? Any must-haves or must-avoids?
3. **Done & delivery** — How do you want to receive it: **shipped · store pick-up · forwarded**? In order of preference.
4. **Must-knows** — Authenticity concerns? Anyone who handles forwarding/logistics for you?

## Tools this domain leans on
Email (read seller/support replies) · browser control (store & price pages that don't render in
a plain fetch) · **deep-research** (authenticity & price verification) · maps (store pick-up
locations) · spreadsheets (compare-tables) · scheduled tasks (passive price/stock monitoring —
web only; Mail-reply reading happens in a live session). Live status: `memory/tools-registry.md`.

## What a shopping task's status.md carries
Goal (done = genuine item, delivered, user satisfied — only they close) · the decision tree
(e.g. "if available locally, wait; else buy international and forward") · findings (with the
*why*) · dated action log · Mail rule if email is used · honest "not-yet-built" (tracking /
after-sale only matter once an order exists) · next check. Use `task-template.md`.

*History:*
- 2026-07-08 — created as the first domain module, generalized from real shopping work
  (product decision, authenticity checks, deal verification, cross-border fulfillment).
