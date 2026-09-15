# Grok Bot Galaxy — Day 1 research notes
Source broadcast: https://x.com/i/broadcasts/1AxRnZbVpjaxl
Event: https://x.ai/galaxy · https://luma.com/3ifrgttw
Builders: Matt Palmer (@mattyp), Lauren Tan (@poteto), Roshan Sadanani (@roshan_s)
Guest / 101 speakers: Roman Ugarte (@romanugarte_), Amrita (@iamrita98), Codie Sanchez (@Codie_Sanchez), Peter Yang, Lingxi Li (@lingxi) at 12:30 PT
Window: 8:30 AM–6:00 PM PT daily, Sept 15–17 (listed live-only; no official replay)
Compiled: viewer TLDRs from @ChrisSimpson live-clip notes + host posts (cross-check against stream when capture is available)

## Day 1 schedule (PT)
- 8:30–9:00 Livestream starts
- 9:00–10:00 Grok Bot 101 — Roman Ugarte (+ Amrita)
- Midday: live company build (Ship by Thursday / Pop-up OS)
- 12:30–2:00 Grok Bot for Engineering — Lingxi Li
- 2:30–3:30 Grok Bot for Product Managers — Kevin Niparko
- 4:00–5:30 Grok Bot for Founders — Shub Gaur
- 6:00 Day 1 ends

## Live company lock (builders)
1. Company name working title: **Ship by Thursday** (alt: Potato Lab)
2. Lauren = CTO / Chief Potato Officer; Roshan = CPO
3. Near-term: food pop-up in SF
4. Meta product: **Pop-up OS** / OS for running restaurant pop-ups, dogfooded on the first one
5. Keep company story consistent for guests and for every Grok Bot

## Key takeaways to learn

### Mindset (Roman Ugarte — Grok Bot 101)
- Stop treating AI like a task box. Treat it like a colleague that owns outcomes, has a computer, and lives in the cloud.
- One bot per job responsibility (sales outbound, inbox manager) — not a new chat per task. Come back so it learns.
- Expect teammate memory (e.g. slide format weeks later).
- Give bots their own computer, not only MCPs/APIs — clicking weird software, watching video, finishing the last 10%.
- Cloud so work continues when laptop is closed.
- Arc: chat → copilot beside you → AI teammates that own a piece of the company.

### Operating model (Amrita — Grok Bot 101)
- Bots are long-lived teammates: give an outcome, they use a real computer (even without MCPs), remember teaching, ask when risky.
- Start with the outcome; let the bot work backwards.
- Spin specialist bots (Data Dan, Slide Sonya, Email Ethan) into a group chat.
- Prefer computer use when MCPs/APIs missing.
- Approval rules / Auto-review for outbound to outsiders.
- Teach when it asks → S3 memory; teach a Task once → skill.
- Duplicate for clean memory + same persona; share keepers as templates.
- Closer: put a bot on the most annoying part of your day.

### Stack / harness (Lauren Tan)
1. Grok = model; harness around it.
2. Grok Bot is lightweight (not GrokBuild) — fast product work.
3. Serious engineering: connect Cursor → Cursor cloud agents.
4. Low fidelity → high fidelity on purpose.
5. Let bots help pick the stack; avoid tech-stack debates while chasing PMF.
- Orchestration: Grok Bot spins Cursor Cloud agents (own VM); they test/click while you stay in Grok Bot chat. “Tell Tater to use Cloud agents.”
- Wiring: deploys on main even if page is empty HTML; ask bot to wire landing signups into Notion instead of debating Sheets vs Notion.
- Prompt habit: voice-yap a few minutes, then “Restate what I said in your own words.”
- Heart messages the bot nails so follow-ups learn preference.

### Product / research frame (Peter Yang + builders)
- Who is the customer? What is the pain? What value do you create?
- Build for people watching: cool Grok Bot tech + a business regular people can use.
- Code is cheap; crisp user stories are not (Roshan restaurant-ops demo: morning reservation brief, manage reviews, day-one demos from stories).
- Peter Yang exit tip: make agents proactive — schedule weekly tasks; Friday numbered status from each bot; ask for human-bot collaboration in-product (not forever Slack bounce).

### Distribution (Codie Sanchez advisory)
- Distribution beats clever product. Sell before you build. Tie every AI idea to cash.
- Sell to three real people before building; if nobody pays, no business yet.
- Obsess distribution (esp. X). Cool product + no path to butts in seats = default fail.
- Controversy OK when it’s a real POV (her ads take → 2.4M views/applicants).
- Organic first: ~5.7M organic vs ~2k ads early on stream; know persona before buying ads.
- Distribution as moat (Jack Dorsey: #1 reason AI bets die = no distribution).
- Proof vault from day one (screenshots, charts, receipts).
- X lead magnet worth more than an email (15k SMB survey insight page ~5 min).
- Research: imitate → iterate → innovate; reverse-engineer winners with a research bot.
- Ads: less corporate; dog/couple creative beat logo (~40% worse when corporate).
- SMBs: only sell AI tied to immediate revenue (~15% multiple frame).
- First principle: business exists to make money; make leads 10x more valuable.

### Action checklist (steal today)
1. Pick ONE annoying daily job → one Grok Bot → outcome + computer → Friday check-in → same bot tomorrow.
2. Sell one offer to three people; research-bot reverse-engineers the distribution channel that already works.
3. Open coding Grok Bot: “spawn a cloud agent for this repo and come back with a screenshot.”
4. Ship pipe: deploy main + wire signups to one store (Notion fine).

## Transcript status
Full verbatim audio transcript: in progress (broadcast is live; official replay not listed). This file is a structured takeaway transcript of teachable arcs until continuous audio capture is locked.

## Capture status
- 2026-09-15 15:13 ET: Player live; BRB screen; no CC. HLS audio capture blocked by Auto-review (signed URL). Continuing via live watch + viewer notes.

## Engineering segment — Lingxi Li (live capture ~12:30 PT)
Session title on slide: “Grok Bot for Engineers” (Tue Sep 15). Presenter lower-third/OCR: Lingxi Li / “LingLei — Engineer, Grok Bot”; SpaceX branding.

### Observed
- Live bot/fleet status panel on stage (~16 / 444 messages / 0 working / 11 active — numbers dynamic)
- Browser engineering/chat demo: left rail of bots/workspaces, threaded messages, code/link cards
- Title slide, then **AI Maturity Curve**:
  1. Autocomplete — Cursor Tab
  2. Ask & Edit — Cursor Agent
  3. Agentic Coding — Cursor 3
  4. Automations — Cursor Cloud Agent
  5. Autonomous Coding — Grok Code
- Teaching point: engineering assistance as a maturity ladder from inline completion → interactive edits → agentic coding → automated → autonomous coding

Screenshots archived under /tmp/.sand-browser/ from this capture window.

### After maturity curve (continued Engineering)
**Introducing Grok Bot**
- Fully Autonomous AI Agents: execute engineering tasks around the clock; achieve objectives
- Connect to tools: MCP — Notion, Figma, Slack, Jira-like
- Manage Cursor Cloud Agents: first-party integration to scale workflows
- Memory & Routines: remember preferences; recurring tasks

**Why Grok Bot**
- No more caffeinated laptop
- Beautifully available on all platforms
- Control computer when needed
- First-party coding agent integration

**Get Things Done when I am away — Engineering use cases**
- Cloud agents inspect transcripts, screenshots, proofs from prior work
- Then send follow-ups / push back on the engineer’s behalf
- So the engineer does not have to sit at the computer

Still Engineering mid-session; no handoff to live company builders observed in this window.
# Grok Bot Galaxy — Engineering remainder capture

Broadcast: https://x.com/i/broadcasts/1AxRnZbVpjaxl  
Capture window: ~10 minutes from video clock ~4:10:56 to ~4:21:05 (Tue Sep 15, 2026).  
Playback was running and unmuted throughout (control showed **Mute**). Tab left open.

## Chronological teachable-point notes

1. **Nightly Code Cleanup** (Engineering Use Cases)
   - Every night at 3 a.m., the Bot researches the whole repository for code-quality problems or improvements.
   - It hands PRs over by morning, so the engineer wakes to proposed fixes rather than a fresh investigation.
2. Speaker camera-only interval: Lingxi Li continued explaining the use case; the Nightly Code Cleanup slide returned briefly before the next case.
3. **TestFlight Seat Management** (Engineering Use Cases)
   - Before Grok Bot, building an internal email-driven tool to add people to TestFlight took time.
   - With Grok Bot, state the goal; it builds MCPs and listens on Slack for requests automatically.
4. **Auto-fix Everything** (Engineering Use Cases)
   - Bot monitors main CI, integration tests, and deployment pipelines.
   - When something breaks, it immediately makes a fix, proves it locally, and merges the PR itself (as presented on slide).
5. **Meet the team**
   - Lingxi — Chief of Staff; Craig — UI Engineer; Steve — Devex Engineer; Hogan — Infra Engineer; Jenny — Head of Operations.
6. **Nightly Audit Engineer demo**
   - Product UI showed a bot named “Nightly Audit Engineer.” Prompt: “Please create your routines and write your memories.”
   - Bot response: it researches a whole codebase, then ships one cleanup per area (“research-first, spread-out cleanups”), and is setting itself up.
   - Sidebar also showed “Lingxi’s Engineer Bot” and “Bot (Chief of Staff)”; Marketplace was visible.
7. **Lingxi’s Engineer Bot demo / FlyLo Engineering Fleet**
   - A fleet board is described as “FlyLo Engineering Fleet”; schema: Task name, Owner, Stage, PRs, Cloud agent, Last commit.
   - A 30-minute fleet watcher points at the board and fires a task when work is boarded.
   - Demo boarded GitHub PR #72 (“Trust polish”), checked the board, attached its cloud agent, reopened the PR after a cancelled/closed-without-merge state, and walked it through Watching 1/3 → Working (Bugbot legal-links finding) → Watching 1/3 → Watching 2/3 after Bugbot threads cleared.
   - User then asked the bot to rename “Nightly Audit Engineer” to Steve and explain the engineering workflows; the bot confirmed the rename and briefing.
8. **Workflow policy / engineering rules demo**
   - Code & merge: all code goes through Cursor cloud agents; prove remote tip, mergeability, CI green, and real product proof. Humans own every merge; never merge without Lingxi’s explicit approval. Don’t open new PRs against default branch; one cloud agent per PR stream.
   - Board-first (Notion: FlyLo Engineering Fleet): create Stage=Working row before digging/launching; fields are Task name, Owner, Stage, PRs, Cloud agent, Last commit; keep follow-ups on the same row/agent; don’t re-board another owner’s PR.
   - CLEAN ladder: Working → Watching 1/3 → 2/3 → 3/3 → Ready for review; also Holding/Blocked/Done/Cancelled. Four consecutive CLEAN ticks are required; Ready is terminal pre-merge. Agent-finished is not Done; Done means merged. CI/security/check-run/bot-thread failures still block.
   - Rebase/CI/proof: rebase only for real conflicts or needed default-branch CI fixes; never merge default into the branch; fix root causes; visual proof must be real verified product chrome, with playable MP4 hosted in the PR body, never a white-canvas mock or committed artifact.

## Screenshots

- `grok_bot_engineering_screenshots/01_nightly_code_cleanup.png`
- `grok_bot_engineering_screenshots/02_testflight_seat_management.png`
- `grok_bot_engineering_screenshots/03_auto_fix_everything.png`
- `grok_bot_engineering_screenshots/04_meet_the_team.png`
- `grok_bot_engineering_screenshots/05_nightly_audit_engineer_demo.png`
- `grok_bot_engineering_screenshots/06_lingxis_engineer_bot_demo.png`
- `grok_bot_engineering_screenshots/07_engineering_workflow_rules.png`

## Handoff status

The requested ~10-minute window completed while Engineering was still presenting the workflow demo. No explicit Engineering → Builders/PM/BRB handoff or next-session announcement was visible before capture ended, so “what comes next” was not reached/observable in this window. The tab remains open, playing, and unmuted.

## Engineering remainder — FlyLo demo + “What we learned”
See also `eng-remainder2.md`. Highlights:
- Named bots + routines enforce rules (Steve = Nightly Audit Engineer; Jenny owns playbook; engineer bots do not edit it)
- Research-first nightly pass across booking-frontend / web / crew-app / factory
- P0: “Trip lookup broken” — board first, cloud agent, 5-min interrupt watch; playbook fan-out via Jenny
- Fleet board source of truth: Task, Owner, Stage, PRs, Cloud agent
- What we learned: treat like interns; think one level further (automate repeated unblocks); start with a feedback loop
# Engineering remainder 3
Capture began around 2026-09-15 16:41 EDT, video ~4:41:18 / 4:43:30.

## New material observed
- Around 4:42:30–4:42:35 on the broadcast: screen-share demo of GitHub organization settings for `shipbythursday`, Install Cursor / Cursor GitHub App. The page shows Cursor connected to GitHub “to allow agents to do work for you in the background.”
- Visible permissions: read access to administration, commit statuses, custom organization roles, repository packages, deployments, members, metadata, plus read/write access to actions, checks, code, discussions, issues, merge queues, pull requests, and workflows.
- Repository access choices shown: “All repositories” (selected) vs “Only select repositories”; Save/Cancel controls at bottom.
- This is a new post-“What we learned” live builder demo; no handoff yet at this point.
- Around 4:43:45: demo changed Repository access to “Only select repositories.” Picker displayed `shipbythursday/galaxy-g-chart` (no description) and `shipbythursday/throwaway-count-1-to-10` (“Throwaway test repo for project agent count demo”). Lower page exposed Danger zone: Suspend this installation / Uninstall “Cursor”.
- Around 4:43:49: confirmation banner: “Okay, Cursor was updated for the @shipbythursday account.” The GitHub App was saved with narrowed repo scope.
- Around 4:44:59–4:45:03: returned to in-room builders (three at table; Lingxi Li on right) with a shared-screen demo. The shared screen is a Slack-like workspace beside a Google page; visible channels include `tater`, `hashbrown`, `PlanetScale Bot`, and `grepot`. Chat appears to be debugging/iterating a verification skill and bot/admin-dashboard workflow, with a message referencing a new CRM channel for bug reports/screenshots and another saying the first stop is to run the verification skill against the admin dashboard. Text is small in the broadcast, so details are approximate.
- Around 4:46:18–4:46:21: shared screen switched to Slack dark-mode workspace, channel `#pm-reviews`. In-room trio remains visible above. Channel shows join notices (Lauren, Matt Palmer and others), an automation notice saying automation is enabled in the channel and can trigger on matching messages, and a bot/automation post with a “please review” GitHub/Cursor-style link. This looks like the team’s review/approval loop for agent-generated work.
- Around 4:48:39–4:48:43: new demo in a Grok Bot desktop-style app, channel `Founding Eng`. A question card offered “Type / spacing / scale,” “Logo treatment,” “OG image too,” or “I’ll describe it.” Message from Push lander to company main: “Going to tighten type, spacing, and scale on the current title-only lander, same Geist / timer / black-on-white. No new copy.” Bot response: “Stopped. Nothing else in flight.” Follow-up: “Idle. The lander is still the title-only page on `shipbythursday/thursday` PR #2. Say when you want to pick it back up.” This demonstrates stopping/pausing work and resuming from an existing PR.
- Around 4:49:54: Chrome omnibox search for `pstack`; suggestions included pstack GitHub/skills/Cursor/plugin/command and a PR: “Enable pstack as a project-scoped Cursor plugin by poteto – Pull Request #5 – shipbythursday/thursday.”
- Around 4:49:58: navigated to GitHub `cursor/plugins` → `pstack` on `main`. Commit header: “poteto and cursoragent feat (pstack): setup-pstack budget ask (max/xhi...)” (3 days ago). Visible folders include `.cursor-plugin`, `.github`, `advisor`, `agent-compatibility`, `cli-for-agent`, `continuous-learning`, `create-plugin`, `cursor-sdk`, `cursor-team-kit`, `docs-canvas`, `grok-voice`, `orchestrate`, and `pr-review-canvas`; entries suggest pstack is a reusable Cursor plugin with docs/skills/automation assets.
- Around 4:51:09–4:51:14: GitHub `cursor/plugins/pstack/skills/create-verification-skill/SKILL.md`, a concrete verification-skill playbook. Visible points:
  - Helpers must be executable and their invocation shown in the skill body; making the reader reverse-engineer a helper is not a helper.
  - “3. Seed the feature map”: create `.cursor/skills/verify-<app>/features/README.md` plus one file per user-facing feature (start with ~3–5 from routes/commands/menus/docs). Each feature file must explain what it is, how a user reaches it, how to drive it with the harness, and what observable state proves it works; four H2s are Sub-features, How to get to it (user POV), Driving it with `<harness>`, and Gotchas. The map is the repo’s maintained verification source; one convenient entry point is incomplete if the map lists other features.
  - “4. Prove the generated skill before handing it over”: run launch → doctor → drive one mapped feature → capture evidence → clean up; confirm evidence survives cleanup. Test failure/cleanup too, so broken attempts do not strand processes/ports. An unexecuted generated skill is a draft, not deliverable.
  - “5. Offer the maintenance loop”: a `/maintain-verification-skill` path keeps the map honest as the app changes (remaining text was below the viewport).
- Around 4:52:25: Slack `#bug-reports` demo. Lauren joined; Slackbot says the channel was made a default channel for all new `shipbythursday` members and can be removed via workspace admin settings. Matt Palmer says Cursor and Roshan joined (and a rocket-icon member was added). This is the bug-report intake side of the workflow.
- Around 4:52:29 (screen advanced during capture): Cursor Agents page titled `verify-thursday skill + signup…` / “Build waitlist verification skill.” Prompt says work end-to-end in `/workspace`, read `poteto-mode SKILL.md` in full and name principles that materially change decisions; start from current remote `main`, inspect git status, fetch `origin main`, then create a branch exactly `cursor/verify-thursday-1f82` (not on main). Visible plan steps: “Check lockfile drift from playwright install,” “Thought for 6 seconds,” “Push playwright fix and create draft PR,” “Planning next moves.” Footer: “Follow-ups are disabled in subagents,” Auto Balance.
- Around 4:53:43: Grok Bot conversation `steve` ↔ `tater` gave explicit status: verification skill is in a live cloud agent, no PR yet; running `verify-thursday skill + signup E2E`; expected done state is `.cursor/skills/verify-*` in a PR, signup path proven once, link in `#pr-reviews`. pstack PR #5 already merged; open leftovers #2, #6, #7, #8 are lander/prototype-letter work, not this job. When asked if the cloud agent was stuck, response clarified it is using a subagent and “still chasing the PR, not the spinner.”
- Around 4:53:52: Cursor agent progress page advanced: “Verify server readiness and PR template”; “App starts cleanly. Next I’ll draft the skill and helpers from the interview, then prove signup end to end”; searched `/create-skill/**`, used walkthrough-artifacts, planned “Query DB, test duplicate, stop server,” grepped a `name` field, installed Playwright Chromium; “Completed 4 of 10 to-dos,” creating skill/helpers/feature map from interview findings.

## Handoff / window result
- Monitored roughly 12m35s from ~4:41:18 to ~4:53:52 of the live broadcast.
- Engineering did not clearly end during this window. The builders remained on-screen or their live demos/screenshares continued throughout.
- No explicit “builders return,” BRB, Kevin Niparko PM session, or Q&A handoff was observed. The final material was still Engineering agent/verification work (live cloud-agent status and Cursor progress), not a transition.
- Playback remained running and unmuted at the end (player showed Pause and Mute controls).

---
# Engineering remainder 4 — 2026-09-15

Capture window: approximately broadcast 4:54:44–5:07:44 (about 13 minutes; started from the previously noted Ship by Thursday / Cursor GitHub App / `verify-thursday` signup-E2E work). The X broadcast tab was left open and playing; it was not muted.

## New teachable notes

- **Verification work was still live in a cloud agent.** The `verify-thursday skill + signup E2E` run was described as moving in a live cloud agent, with no PR at the first check. The operator was chasing the PR, not a stuck spinner; the run was using a subagent. `hashbrown/fable` was also still running. Existing leftover PR numbers called out were #2, #6, #7 and #8 (lander/prototype leftovers), not this job.
- **Automation actually fired.** Tater posted **#10 to `#pr-reviews`**; the automation fired this time, with a Cursor cloud-agent run link. The side panel showed `grokpot` baking/previewing `admin.html` while tater was the active agent.
- **Poteto Mode prototype request.** While waiting for verification, tater was asked to use Poteto Mode (via a cloud agent) to prototype the platform’s admin features and brainstorm the required surface area.
- **Initial platform requirements.** The operator described event creation with date/time, signups, venue, and staff; for a restaurant popup, the platform should cover staff hiring/assignment, menu, event plan, invitations, attendee management and ticketing.
- **Admin mock decision point.** A new “PLATFORM OPERATIONS” dark admin mock showed a poll: “This admin mock — lock it, iterate, or hold?” Lock means tater builds it against real signups; iterate means grokpot keeps the throwaway; hold leaves the waitlist as-is.
- **Night-of-console scope (explicit in the prototype).** In-scope: public page with menu + RSVP (email and headcount vs capacity), attendee list, staff roster (name/role/contact — explicitly a list, not hiring), and a shareable invite link. Out for now: payments/Stripe, hiring marketplace/payroll, POS/inventory/suppliers, diner-discovery feed, guest CRM across nights, and multi-location. The waitlist is already the top of funnel; this prototype is the “night-of-console.”
- **Product decision:** tater is on it via a Poteto-mode cloud agent; the six surfaces will be PRs; **no payments in this cut** (RSVP vs capacity). The operator explicitly asked people to yell if Stripe is wanted in the first prototype.
- **Verification status before merge:** PR #10 was open, Vercel preview green, and there were no GitHub review comments yet. The run was blocked on the review landing; tater would address it or merge once ready.
- **Proof-file policy and merge:** standing rule became “proof stays on disk, not in git.” The team would merge only after proof was removed from #10; tater confirmed the merge only after that. Final visible status: **PR #10 on main at `026b06f` (1:43pm PT), `proof/` ignored, zero proof files in the tree; verification skill is live; operator-loop prototypes still with tater.**

## Session-change check

A small live-camera panel of the Grok Bot Galaxy stage (three people at the table) appeared during the latter part of the capture, and the final frame showed the merged/live verification milestone. I did **not** see an explicit “Engineering ends,” Kevin Niparko PM session, BRB, builders-only, or Q&A transition during this window. Capture stopped after the clear PR-merged / verification-live milestone, while the operator-loop prototype work remained active.

## Screenshots

Saved under `/workspace/galaxy-day1/shots/`:

- `eng-remainder4-2026-09-15-1632-tater-status.png`
- `eng-remainder4-2026-09-15-1633-tater-poteto-mode.png`
- `eng-remainder4-2026-09-15-1634-poteto-prototypes.png`
- `eng-remainder4-2026-09-15-1635-pr10-automation-adminhtml.png`
- `eng-remainder4-2026-09-15-1636-admin-requirements.png`
- `eng-remainder4-2026-09-15-1637-platform-operations-mock-poll.png`
- `eng-remainder4-2026-09-15-1639-night-of-console-surfaces.png`
- `eng-remainder4-2026-09-15-1641-stage-pip.png`
- `eng-remainder4-2026-09-15-1642-verification-pr10-status.png`
- `eng-remainder4-2026-09-15-1644-verification-live-pr10-merged.png`

---
# Galaxy Day 1 — engineering remainder 5

**Capture window:** Tue Sep 15, 2026, ~1:47–1:59 PT (4:47–4:59 PM UTC-4), continuing the supplied checkpoint.  Livestream tab stayed open and playing; verified video `muted=false`, `paused=false`, volume 1 during the window.

## Screenshots

- `shots/2026-09-15_1647_live_builders-table.png` — builders at table; Host Finder/agent roster visible.
- `shots/2026-09-15_1649_venue-finder-poteto-mode-demo.png` — Steve chat with the venue-finder scope; operator/routines mock visible.
- `shots/2026-09-15_1651_openstreetmap-auth-demo.png` — OpenStreetMap/Leaflet decision and GitHub-only auth draft.
- `shots/2026-09-15_1653_venue-auth-vercel-protection.png` — Vercel team protection vs Clerk decision card.
- `shots/2026-09-15_1655_pr12-venue-auth.png` — PR #12 verification follow-up and deployment-protection notes.
- `shots/2026-09-15_1657_venue-finder-cloud-agent.png` — dogfood venue map/search/click-to-call cloud-agent surface.
- `shots/2026-09-15_1659_pr12-main-two-agents-status.png` — PR #12 on main and two-agent status routine.
- `shots/2026-09-15_1701_signup-ts-role-allowlist-demo.png` — GitHub `api/signup.ts` code view.

## Dense notes / decisions

### Venue-finder became the only engineering track
- Tater’s cloud agent is now the venue finder: map, search, click-to-call, and “who runs this place?” lookup (manager/owner).
- Explicit decision: pause event/menu/RSVP prototypes; this is a few prototypes, not production, not the waitlist, and not the operator dashboard.
- Owner: Tater. Target is at least two PRs so Matt can search a city, tap a place, call, and see who to talk to.
- The dogfood UI was shown as **“venue map + search + click-to-call”** for `shipbythursday/thursday`; agent card was Working and instructed to build in `/workspace` on that repo.

### Maps / access
- Use OpenStreetMap with Leaflet; use OSM tiles plus Overpass/Nominatim for places. No Google Maps billing.
- Nominatim/Overpass polite-use limits were called out; acceptable for the three-person manual dogfood.
- Waitlist stays open; venue tool gets its own Vercel project and team auth.
- Venue-finder prototypes use **Vercel Deployment Protection — team authentication** (Ship by Thursday Vercel team only). Team admin must verify/invite members under Team → Members before protection is enabled, or they will bounce.
- Clerk + GitHub allowlist was considered (Lauren/Matt/Roshan usernames) but deferred: Vercel team protection is the low-setup dogfood choice; Clerk later when in-app identity matters.

### PRs / verification
- Verification follow-up: **PR #12** (role-assert fix + nits), posted to `#pr-reviews`, then merged by Tater.
- Confirmed on main at **commit `1f988c1` (1:53 PM PT)**; verification skill hardened. Main track remained venue-finder.
- GitHub code view showed `api/signup.ts` on `main`, with role allowlist `chef`, `host`, `food-pro`, `operator`, `unspecified`, email-pattern validation, and ESM `.js` import (`../db/client.js`). Commit banner read “cursoragent and potato — Resolve relative imports under Node ESM.”
- Earlier checkpoint still stands: Ship-by-Thursday PR #10 merged at `026b06f`, verification skill live, proof/ gitignored; the sidebar later referenced “#10 Fable (post-mer…)”.

### Agent status / monitoring
- A standing **Venue-finder status** routine was created to report on Tater.
- Snapshot at 1:53 PM PT: both venue cloud agents still running, no PRs yet:
  1. map + search + click-to-call
  2. contact / people lookup
- Plan was to ping when either lands a PR or finishes, plus a standing check every 30 minutes until 6:30 PM PT, quiet if nothing moved.
- Operator mock showed recurring routines (“Routines are recurring tasks this bot runs on a schedule…”), and the roster cycled through Tater, Hashbrown, Steve, Host Finder, Founding Eng, Outreach/Chief.

## Explicit session-change check

- **Engineering did not end** during this capture; builders/agents were still active at the end.
- **PM / Kevin Niparko (~2:30 PT): not observed.**
- **BRB: not observed.**
- **Q&A: not observed.**

---
# Galaxy Day 1 — engineering remainder 6

**Capture window:** Tue Sep 15, 2026, ~5:01–5:14 PM UTC-4 (2:01–2:14 PM PT), continuing the supplied checkpoint. The X livestream tab remained open and playing; final media check: `paused=false`, `muted=false`, volume `1`.

## Screenshots saved

- `shots/eng-remainder6-1701pt-current.png` — live studio panel while the engineering segment continued.
- `shots/eng-remainder6-1704pt-venue-finder-demo.png` — chat/product demo: venue #13/#14 remains the main track and the team is checking for a cloud-agent demo video.
- `shots/eng-remainder6-1707pt-verification-skill-demo.png` — always-on verification skill and PR media rule shown in the operator/chat UI.
- `shots/eng-remainder6-1710pt-pr14-osm-vercel.png` — GitHub draft PR for the internal OSM venue finder and Vercel protection instructions.
- `shots/eng-remainder6-1713pt-agent-heartbeat.png` — agent heartbeat, open PRs, and the missing-PR-media follow-up.

## Dense notes / decisions

### Venue-finder PRs and product scope

- Engineering stayed on the venue-finder track; the on-screen decision was “venue #13/#14 still the main track.”
- A venue-finder chat surfaced the explicit TypeScript decision: stay TS for dogfood; reconsider/refactor tomorrow only if it still itches. No Go hybrid now.
- The demo request was to verify the venue finder working and include a clip/screenshot; the team was checking PRs #13/#14 and the cloud agents for the demo video.
- A GitHub screen showed draft **PR #14, “Add internal OSM venue finder prototype”**. It proposes merging 8 commits into `main` from `cursor/find-venue-prototype-4e7d`.
- PR #14’s internal-only deployment instructions: manually enable Vercel Authentication for Production and Preview on the internal project; optionally set `OSM_CONTACT_EMAIL` to a monitored address. Do **not** enable protection on the existing public waitlist project. `.vercelignore` excludes `tools/`, and no app-level authentication is included.
- Scope is intentionally narrow: people/manager/owner lookup, hiring, payments, ticketing, and admin are excluded. The prior checkpoint’s PR #12-on-main status remains the earlier baseline; this capture showed the separate draft #14.

### Verification / proof policy

- Verification skill is to be always applied (`no disable-model-invocation`). It should cover the whole Thursday app, not just waitlist; the feature map should cover waitlist plus find-venue (map/call + people) at minimum.
- Every PR that can affect the product must include video/screenshots in the PR description, including backend changes: prove the flow still works or show a quick non-regression clip. Media belongs in the PR description, not committed into `proof/`.
- Tater owns the skill and standing-rule update. A visible follow-up said PR #14 currently has no real demo media, only Cursor chrome links; screenshots should be added now and video when the clip lands.

### Agent status

- Tater heartbeat: demo video still running; PRs **#13, #14, #15, #16** open; Hashbrown is on **#15**; “no blockers.”
- Tater’s sidebar status changed to “Adding screenshots to …”; final response was “I’ll ping you when media actually appears on the PR.”
- Other visible operator roster snippets: Hashbrown (`#12 Fable (post-merge)…` earlier), Grokpot (`operator admin mock…`), PlanetScale Bot (`Setup’s done — ready…`), and X (`Pulled the thread for Bot`).

## Explicit session-change check

- **PM session / Kevin Niparko:** did **not** start in this window. The official 2:30–3:30 PT slot was still ahead; the stream remained engineering.
- **BRB:** not observed.
- **Builders-only:** not explicitly announced; content remained a builders/engineering work session.
- **Q&A:** not observed.
- No clear session change by the end of the ~12-minute capture; tab was left open and unmuted.
# Engineering remainder 7 — venue finder / PM transition

**Capture window:** ~2:17–2:30 PM PT (Tue Sep 15; started from the prior ~2:14 PT checkpoint). Stopped at the first clear session change: the **“Grok Bot Galaxy — Be right back”** interstitial.

## New demos / slides captured

- **Venue status / PR review (about 2:17–2:20 PT):** Internal operator/chat view showed the current venue work. `#14` map was clean and green reviews were in flight; a demo video was called out. `#16` app-wide verify had been pushed and core PR was intact, while `#15`’s waitlist-oracle fix had just landed in `#pr-reviews`.
- **Product decision:** The first popup is no longer a restaurant popup. It is a **Grok Bot-themed art exhibition**. Keep the venue finder, but make the venue type generic enough for mixed-use spaces, warehouses, and big open rooms; restaurants can be added later. The accompanying note said to treat the room as a warehouse/open-room space for now.
- **PR/media review:** Two venue prototype PRs were listed:
  - `#13` people / owner lookup — open, changes requested, **no media**.
  - `#14` OSM map + search + click-to-call — open, changes requested, **no media**.
  The video agent finished, but its MP4 was **0 bytes / unusable**. The operator planned to re-record after the exhibition-space retarget and put the video in `#14`, with screenshots/video for `#13` too. Media was made the top unblock before either venue PR lands.
- **Starship/share demo:** X post demo invited one Grok Bot user to a Starship launch: share using the integrated `@Bot` tool, with a plus-one. The post’s media cycled through a rocket clip and a “Want to win a trip to see a Starship” graphic.

## Teachable engineering/product notes

- “No blockers” at the prior checkpoint changed into concrete review gates: both venue PRs remain open with requested changes and lack required PR-body evidence.
- For demos, a rendered UI is not enough: the PR body must carry screenshots/video, and a zero-byte MP4 is treated as missing evidence.
- Scope was deliberately generalized from restaurants to mixed-use/warehouse/open-room venues to match the themed exhibition; defer restaurant-specific support rather than overfit the first demo.
- `#13`’s previously noted fixes remain important: allowlist plus Overpass timeout handling; avoid exposing `/api/venues` publicly on the waitlist project (nomination-ban risk); do not demo real venue phone numbers.
- The stream also showed the app-wide verify push (`92d57e5`) and the instruction to keep protected Vercel tooling separate unless the operator needs to jump in.

## Session-change markers

- **BRB:** Yes — full-screen “Grok Bot Galaxy / Be right back” card appeared at ~2:30 PM PT; this was the stop condition.
- **PM session:** Scheduled for 2:30 PM PT, but no spoken/visual PM-session handoff was captured before the BRB stop condition.
- **Kevin Niparko start:** Not observed in this window.
- **Q&A:** Not observed.
- **Builders handoff:** Not observed.

## Screenshots

- `shots/eng-remainder7-start-venue-finder.png`
- `shots/eng-remainder7-1717-venue-status.png`
- `shots/eng-remainder7-1720-product-decision.png`
- `shots/eng-remainder7-1723-pr-media-blockers.png`
- `shots/eng-remainder7-1727-starship-demo.png`
- `shots/eng-remainder7-1730-brb.png`

The X broadcast tab was left open and the video was verified still playing **unmuted** (volume 1).

---
# Grok Bot Galaxy — Day 1 remainder 8

## Capture result
- Broadcast tab left open at `https://x.com/i/broadcasts/1AxRnZbVpjaxl`.
- The player was no longer on the BRB card when checked; live content had returned.
- Confirmed with the player element: `paused: false`, `muted: false`, `volume: 1`, `readyState: 4`; current time advanced while observed and the live duration extended.
- Session identification: official PM/product session (consistent with the scheduled Kevin Niparko 2:30–3:30 PT slot). Two presenters were on stage; no name lower-third was visible in the captured frames, so Kevin attribution is based on the scheduled session rather than a visible name card.
- Live view count rose from roughly 815.5K to 820.5K during observation.

## First returned slides / notes

### “Why Grok Bot”
- Main point: agents are not quite at home in a chat box.
- Chats are useful for many kinds of interactivity and important use cases, but feel limiting for agents.
- From building agents at SpaceXAI, the team found itself moving up a level of abstraction: away from reading every token and toward prompting for outcomes.
- Slide visual: large blue Grok-style abstract graphic and an orange outlined icon; stage inset showed two presenters.
- Screenshot: `shots/pm-why-grok-bot.png`

### “Agents as colleagues”
Four-panel framing of the product direction:
- **Tie tools together to produce outcomes:** MCPs such as Jira, Notion, Figma, and Slack help gather context, but produce session-scoped output and require re-prompting or knowledgebases for continuous work.
- **Long-running context:** colleagues remember what they previously worked on and learn over time.
- **Independence:** giving agents their own computers and access to services lets them work when the user is not working and set up routines. Example card says “Computer — Sign in to Salesforce” and shows a Working state.
- **Messaging:** “No more ‘wait your turn’ in the chat.” Example Kenny thread discusses whether the Q3 roadmap was brought up and says activation stays the same for the quarter; the reply references a roadmap review expected the first week of August and a Priya-related follow-up.
- Stage inset continued to show two presenters discussing the slide.
- Screenshot: `shots/pm-agents-as-colleagues.png`

## Stop condition
Content had returned, so capture stopped without waiting for the 12-minute BRB timeout. The tab remains open and playing/unmuted.

---
# PM talk remainder — Day 1

- Capture started from the live post-BRB slide “Agents as colleagues”; audio unmuted and playback live.

## ~5:37 PM — live demo begins
- Camera cut from “Agents as colleagues” slide to two presenters on stage (no lower-third names visible).
- Behind them: a workflow/UI demo slide with cards such as “Website launch / Explore / Manage” and “Computer”; visible text references checking whether something is connected, LinkedIn already signed in, and signing in to Salesforce to inspect data.
- Teachability: this appears to illustrate an agent operating across browser/computer workflows, checking connected services and navigating business tools rather than merely answering in chat.

## ~5:38 PM — “PM use cases”
- Slide title: **PM use cases — Three primitives that change how PMs work**.
- **01 Attention List:** emergent signal from Slack, email, and meetings; ordinary priority lists/TODOs go stale. Agents filter noise and surface what actually has your focus; compare stated goals with where time went.
- **02 Research across customer context:** pull together Gong, Granola, Databricks, Notion, support tickets, and user-research databases; agents synthesize across raw sources instead of relying on summaries (slide frames this as a feature of the customer context).
- **03 Shipping:** Grok Bot reportedly represents a double-digit percentage of internally merged PRs. Cloud Agents can decompose, allocate, review, and integrate work (tool-assisted shipping loop).

## ~5:40 PM — “Meet the team”
- Org-chart framing for an agent team: **Cora — Chief of Staff**; **Emily — Engineering Manager**; individual engineering agents **Eileen, Larry, Igor, Nova, and Ethan** (names read from diagram; no speaker lower-third).
- Product claim/framework: agents are presented as a staffed, role-based team with hierarchy/delegation—not a single undifferentiated chatbot. Useful mental model: chief-of-staff triage/orchestration above functional manager and execution agents.

## ~5:41 PM — team diagram expands
- “Meet the team” adds non-engineering roles: **Ashley — Data Analyst**, **Pedro — Product**, **Pixel — Designer**, alongside Cora/Emily and the engineering agents.
- The diagram visually communicates a cross-functional virtual org (chief of staff + engineering manager + engineers + data/product/design), not only coding agents.

## ~5:42 PM — recruiting joins the org chart
- Team diagram adds **Rae — Recruiter** (blue agent) to the cross-functional roster.
- Ongoing visual claim: a PM can compose a persistent virtual company/team by role, with agents covering operational, technical, product, design, data, and hiring functions.

## ~5:43 PM — “Why many agents”
- Subtitle: **“Not one omniscient blank box, but a full roster of teammates.”** Three reasons:
  - **Referenceability:** know who does what; ask Ashley for charts, Emily for shipping status, or Pete for an RFC without re-explaining the world each time.
  - **Scoped memory:** different agents learn different things on the job; the Chief of Staff should not debug computer-use evals, and the eval agent is not reviewing your mail.
  - **Parallelism:** many agents work at once on disparate tasks while coordinating on shared ones—“ship while research runs while recruiting keeps warm.”
- Framework: specialization + bounded context + concurrency are positioned as the answer to the “one giant agent” model.

## ~5:44 PM — computer/messaging demo: Notion-connected PM work
- Demo switches to a desktop-style agent inbox (PM Pike) with a roster/status list for agents (Emily, Rae, Ethan, Igor, Nova, Larry, Eileen, etc.).
- Chat exchange: “Can you access notion?” → agent: **Notion is connected to the Cursor workspace** and can search, read, and create/update pages.
- Agent drafts a Linear-style mobile-purchase spec in Notion, grounded in a Flyo honest-free booking flow; it reports a private Notion draft/PRD and summarizes proposed flow, edge cases, and next step.
- Teachable claim: connected-tool access turns a PM request into an executed artifact in the team’s existing workspace; messaging is the control surface, while the agent performs the multi-step research/writing action.

## ~5:46 PM — computer demo: analytics/research agent
- Same agent-inbox surface now shows an agent-generated KPI summary with a funnel visualization and a short written analysis in the conversation.
- Teachable point: an agent can inspect connected business data, produce a compact metric comparison/funnel, and explain the result in-line—moving from “please investigate” to an evidence-backed PM readout rather than returning raw links.
- No speaker lower-third; presenters remain visible in the small stage camera feed.

## ~5:48 PM — analytics demo produces a chart
- Agent opens a rendered bar chart: **“Yesterday: 1,187 family passengers — largest cohort.”** Visible comparison bars include Solo (~812), Couple (~512), Family (1,187), and Group (~294).
- Product claim: agents can turn an analytical question into a visual artifact/readout and surface the key conclusion (“family” is the largest cohort), not just dump data.

## ~5:49 PM — mobile-purchase funnel diagnosis
- Generated chart title: **“Mobile purchase: fare select is where intent dies.”** Funnel steps include purchase intent → payment → seat & extras → passenger details → fare select → search results → add-ons/visit.
- Agent highlights the fare-selection step as the major intent drop/bottleneck (red annotation), turning the earlier mobile-purchase-spec request into a concrete UX diagnosis and prioritized intervention.
- Framework: ask → inspect connected data → visualize funnel → identify highest-leverage drop-off → draft the product artifact.

## ~5:50 PM — demo wrap-up state
- Inbox view now shows the generated cohort chart, purchase funnel, and written follow-up in one thread; stage camera shows the presenters discussing it (no lower-third names visible).
- The combined artifact demonstrates continuity across turns: the agent retains the PM thread, adds analysis, and leaves a trail of reusable outputs instead of a one-shot answer.

## ~5:51 PM — generated PRD artifact
- The demo opens the resulting Notion document: **“PRD: Improve FlyLo mobile ticket purchase.”** Header says it is grounded in recent mobile-purchase funnel metrics and corrects the original hypothesis: the leak is earlier at **search + fare select**, not seat choice.
- Visible sections: **Recommendation** (make fare selection easy to see/compare/commit to an honest FlyLo fare without leaving context) and **1. Problem** (mobile travelers cannot confidently select a FlyLo fare, so they leave before seat choice/checkout; “mobile searchers cannot confidently select a FlyLo fare”).
- This closes the loop from chat request → connected data analysis → funnel diagnosis → durable PRD in Notion.

## Capture status
- Final capture still shows the presenters and the PM demo; player remains **LIVE/playing** and audio is unmuted. No lower-third speaker names appeared, and no session end or handoff was visible during this ~12-minute window.

## ~5:52 PM — PRD scroll reveals users + insight table
- **Users:** primary = mobile web browsers on iOS/Android searching FlyLo routes (leisure/work); secondary = returning travelers using FlyLo email/manage flows who rebook on phone; out of scope = agency/bulk/multi-PNR tools.
- **Insight:** last-30-day mobile funnel table tracks Home → Search → Fare selected → Extras → Seat & extras → Passenger → Purchase, with step conversion and a highlighted fare-selection bottleneck. The doc explicitly says seat & extras is healthy and not the main leak; overall home→purchase conversion is called out below the table.
- Product-writing point: the agent does not stop at a chart—it populates audience, scope, problem statement, funnel evidence, and recommendation sections in a shareable PRD.

---
