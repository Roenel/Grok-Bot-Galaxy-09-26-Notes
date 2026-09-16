# Day 1 takeaways — stealable lessons

Distilled from `notes/NOTES.md` and remainder files. Citations point to source sections.  
**Coverage:** Morning/101/Codie/Lauren items are **`tldr-only`** (pre–~3:08 PM ET). Engineering onward is primarily **`live`** slide capture. **No invented Q&A.**

---

## Mindset (Grok Bot 101 — TLDR)

*Source: [NOTES.md](notes/NOTES.md) § Mindset (Roman), § Operating model (Amrita) — **tldr-only***

- Treat AI as a **colleague that owns outcomes**, with a computer in the cloud — not a one-shot task box.
- **One bot per job** (sales outbound, inbox manager); come back so it learns. Expect teammate memory.
- Give bots **their own computer**, not only MCPs/APIs — finish the last 10% (weird software, video, clicks).
- Start from the **outcome**; let the bot work backwards. Specialist bots in a group chat (Data Dan, Slide Sonya, …).
- **Approval / Auto-review** for outbound to outsiders. Teach once → skill; duplicate for clean memory; share templates.
- Closer: put a bot on the **most annoying part of your day**.

## Builders / stack / distribution (midday — TLDR)

*Source: NOTES § Stack/harness (Lauren), § Product frame (Peter + builders), § Distribution (Codie), § Live company lock — **tldr-only***

- **Ship by Thursday** / Pop-up OS: one company story for every bot; Lauren CTO, Roshan CPO; dogfood the first SF food pop-up.
- Grok = model; **harness** around it. Lightweight Grok Bot for product speed; serious eng → **Cursor cloud agents**.
- Low fidelity → high fidelity on purpose; let bots help pick stack; avoid stack debates while chasing PMF.
- Prompt habit: voice-yap, then “**Restate what I said in your own words**.” Heart messages the bot nails.
- Code is cheap; **crisp user stories** are not. Make agents **proactive** (weekly tasks, Friday numbered status).
- **Distribution beats clever product.** Sell to three real people before building; tie AI to cash; obsess X; proof vault from day one.

### Action checklist (from NOTES TLDR)

1. One annoying daily job → one bot → outcome + computer → Friday check-in.  
2. Sell one offer to three people; research-bot reverse-engineers a working channel.  
3. Coding bot: spawn a cloud agent → come back with a screenshot.  
4. Deploy main + wire signups to one store (Notion fine).

---

## Engineering (Lingxi — live)

*Source: NOTES § Engineering; [eng-remainder2.md](notes/eng-remainder2.md)–[7](notes/eng-remainder7.md)*

- **Maturity ladder:** Autocomplete → Ask & Edit → Agentic Coding → Automations (Cloud Agent) → Autonomous Coding (Grok Code).
- Grok Bot for eng: all-hours task execution, MCP tools, **manage Cursor Cloud Agents**, memory & routines.
- Use cases shown live: **Nightly Code Cleanup**, **TestFlight Seat Management**, **Auto-fix Everything**; fleet board (**FlyLo Engineering Fleet**: Task, Owner, Stage, PRs, Cloud agent, Last commit).
- **Workflow rules (stealable):** all code via cloud agents; prove tip/mergeability/CI/product proof; **humans own every merge**; one cloud agent per PR stream; **board-first** (Stage=Working row before launching); don’t re-board another owner’s PR.
- P0 pattern: board → cloud agent → **five-minute interrupt watch** (stall/`sleep 300`/drift) → playbook fan-out (Jenny / Head of Ops owns playbook).
- **What we learned (Eng slide):** treat bots like **interns**; if you unblock the same thing repeatedly, **automate one level further**; start with a **feedback loop**.
- Late Eng builders: venue-finder / OSM / Vercel protection / verification skill — proof and access controls matter for internal prototypes.

## PM (Kevin Niparko — live)

*Source: [pm-remainder1.md](notes/pm-remainder1.md), [pm-remainder2.md](notes/pm-remainder2.md); eng-remainder8 “Agents as colleagues”*

- **Three PM primitives:** Attention List (emergent signal vs stale TODOs); research across **customer context** (Gong/Granola/Databricks/Notion/tickets); **Shipping** via cloud agents (decompose / allocate / review / integrate).
- Staff a **virtual org** by role (Chief of Staff, EM, ICs, data, product, design, recruiter) — not one blank box.
- **Why many agents:** referenceability, scoped memory, parallelism (“ship while research runs while recruiting keeps warm”).
- Demo loop: chat → connected Notion/data → funnel chart → bottleneck (“fare select”) → durable **PRD** → named P0 instrumentation + pixel-lock handoff (build / QA / event owners).
- **Lessons slide:** named agents + separate memory; learn on the job (style guides from Slack); **stay quiet unless needed**; agents all the way down (EM → IC → cloud agents).

## Founders (Shub — live)

*Source: [founders-remainder3.md](notes/founders-remainder3.md)–[5](notes/founders-remainder5.md)*

- Founder maturity: Ask → Do a task → Automate a job → **Staff a function** (team of bots).
- Why Grok Bot: easy as iMessage; always-on; uses your tools; finishes the work; shareable templates.
- Use cases: Close customers on autopilot; QA + updates on product changes; adapt to competitors; ship feedback via Cloud Agents.
- Demos: **Close Bot** (landing audit, call prep), **Prod Bot** (prioritization + evidence), **Stalk Bot** (competitor pulse), **Proto Bot** (share card / feedback → prototype).
- Recap: let bots run free (access); invest in them (feedback over time); **think deeply about delegation** (1–2 hours on responsibilities).

## Power tips (Founders slides — live)

*Source: [founders-remainder5.md](notes/founders-remainder5.md)*

- **Browser use is powerful and expensive** — prefer connectors; if none, learn APIs from network traffic for next time.
- **Routines are awesome — audit them**; prefer exception-only pings; tune schedules (e.g. hourly → weekly).
- Rapid-fire: voice bot that learns from your writing; group bots by expertise; great skills + saved learnings; bots learn classification from tagging; run auto-optimization routines.
- *(Slide claim captured as stated: import cookies / let them use your IP — treat as on-screen tip, not verified advice.)*

## Explicitly not claimed

- **Q&A:** visual-only; no readable captions → **no substance recorded** ([founders-remainder6](notes/founders-remainder6.md)–[8](notes/founders-remainder8.md)).
- **Morning slides:** not invented; await replay backfill for primary capture.
