# Help — one page (this lives in YOUR folder as HELP.md, with every prompt you might need)

The golden rule: **your PA never fails silently.** If something's off, it should tell you
plainly. If it suddenly acts like a generic assistant — that's the #1 symptom below.

## 1 · "It doesn't remember me / answers like generic Claude"
**Cause:** the folder isn't connected to this chat (connections don't always persist).
**Fix:** Project → **Context** → reconnect the **Everyday PA System** folder → just say **hello** in a
new Cowork chat there. **Worked when:** it greets you by name and knows your goal. Failed twice? Run the health
check below and follow what it reports.

## 2 · "It doesn't respond to me in a plain chat (outside my Project)"
Plain chats don't auto-load anything. Use your Project — or connect the folder to the chat,
then paste the **connect prompt** below (it's the same block you pasted into your Project's
Instructions — one prompt, two uses). The Global Instruction, section 8, makes this smoother —
but the folder still has to be connected to the chat.

## 3 · "Setup got interrupted / I closed the app mid-onboarding"
Nothing is lost. If setup was interrupted: new **Cowork** chat → say **"Set up my everyday PA
System"** — it reads STATE.md and resumes where you stopped, never re-asking what you answered.
If setup was already complete: just say **hello** in your Project.

## 4 · "A setup wizard for something else appeared"
Another plugin answered instead. Close that flow and use the exact phrase **"Set up my everyday
PA System"** (or, for daily use, just say hello inside your Project) — that phrase belongs
to this system only.

## 5 · "It says it can't create folders / take actions"
You're in a plain Chat, not **Cowork**. Look for the Chat/Cowork switch and pick Cowork —
setup and anything touching your computer needs it.

## 6 · "It can't do something (read email, check a site)"
That capability isn't connected. It should say exactly which access is missing and what it
unlocks. Grant it when asked — or decline; it works around it honestly.

## 7 · "I think its memory is wrong"
Say what's wrong in chat — it edits the file and confirms. Your memory is plain files here:
`memory/context/profile.md`, `preferences.md`, `memory/people/`. Read them yourself anytime.

## 8 · "I want my team in ANY chat" (the Global Instruction)
Two options — either way, a chat still needs your folder connected. Paste in Settings →
"Global Instruction" / "Personal preferences" / "Custom instructions":
- **Extension** (you already have an instruction you like — ADD this to its end; the block is
  in the prompts section below).
- **Full "Great Mind Peer"** (you have none — a complete thinking-partner instruction; it
  REPLACES the field, so don't paste it over one you want to keep). Say **"show me the Global
  Instruction options"** in any chat with your folder connected and the full text is provided.

## 9 · "I want to start over"
Disconnect (or rename) this folder and say "Set up my Everyday PA System" in a new Cowork chat.
Your old files stay yours — nothing is deleted without your ok.

---

## The prompts (copy from here whenever you need them)

**The CONNECT PROMPT — one block, two uses: paste ONCE into your Project's Instructions box,
or paste into any chat (with this folder connected) to wake your team there:**
```
You are the Chief of Staff of my Everyday PA System — the connected "Everyday PA System" folder.
Read STATE.md and CLAUDE.md in that folder now and follow them (they hold my profile, the team,
and the safety boundaries); greet me by name, mention my goal and where we left off, then
continue — the greeting comes FIRST, before any other tool use or task list. Route my requests
to the right specialist in modes/ automatically (read its playbook first). If the folder is not
readable, say so plainly and tell me how I reconnect it — do not proceed as a generic
assistant. On "wrap up," save the session to memory/log/.
```

**Health check (already ran once at setup; run manually when anything seems off):**
```
Run my PA System health check — verify from files, not memory, and don't install or send anything:
(1) confirm you can read AND write my "Everyday PA System" folder — prove it with a probe file;
(2) run a full verify — every file my CLAUDE.md references resolves (the nine specialist
playbooks in modes/, profile, preferences, HELP, HOW-TO-USE), nothing missing or broken;
(3) read back who you think I am in one paragraph, from my profile;
(4) flag any empty or "unknown — deepen later" memory worth filling (profile gaps, no people
files yet), and how to fill it;
(5) list which tools/connectors are live vs not, and what each missing one would unlock for me;
(6) status from STATE.md — set up vs pending — plus the safety boundaries in one line.
Finish with a one-page readiness checklist.
```

**Global Instruction — EXTENSION (add to the end of an existing instruction you like):**
```
My Everyday PA System: my personal AI team lives in my "Everyday PA System" folder. When I name a
specialist (PA, Venture, Build, X, Relations, Architect), say "Red Team this" or "bring in a
[domain] expert", or say "wake up my PA System", read that folder's STATE.md and CLAUDE.md
first and operate from them, routing to the right specialist in modes/. If the folder is not
connected or readable, say exactly that and how I reconnect it — never proceed as a generic
assistant. Hard boundaries always: never send messages, move money, handle credentials or 2FA,
or install anything without my explicit ok on that instance; never mark work "Done" — only
"Pending your confirmation."
```


