# Tools registry — what the system can reach for (generic, shipped copy)

_The scan-first rule: before a job, check what tools are live in THIS user's session (built-ins ·
skills · connectors), not what you remember. Propose connections; never auto-connect. The user's
actual granted access is recorded in their `memory/context/preferences.md`._

## Always available (no permission needed)
- **Web search + fetch** — research, price checks, availability.
- **File tools** — read/write the user's connected folder (the brain + the work).
- **Skills** — document/spreadsheet/PDF creation and more; they switch on as needed.

## Ask-first access (each one yes/no, with the concrete reason)
| Access | What it unlocks | Note |
|---|---|---|
| **Computer control** | operate the user's own apps (Mail, native apps) in a live session | the foundation for "actually do it" |
| **Browser control** | check stores, fill forms, watch prices on the live web | |
| **Email connector** (Gmail / Outlook) | read replies, track threads, DRAFT mail | sending stays manual — safety boundary |
| **Calendar connector** | events, deadlines, free-time finding | |
| Maps / others | location-based errands | search the live registry when a task needs more |

## The two lanes to email (teach the user this honestly)
Email works **either** via a connector (clean; works in background scheduled runs) **or** via the
Mail app under computer control (live sessions only). **Unattended scheduled runs cannot open the
Mail app** — so background reply-checking needs the connector, or it happens live. Never promise
otherwise.

## Keeping it current
Any session that connects a tool updates the user's preferences table. When a task needs a
capability not listed here, search the live connector registry and propose — never install silently.
