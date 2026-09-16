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
# Galaxy Day 1 — PM remainder 2

**Capture window:** approximately 5:55–6:09 PM ET on Tue Sep 15, 2026 (about 14 minutes; requested ~12). The X broadcast stayed live and the player remained **playing and unmuted** at the end. I left the broadcast tab open.

## What changed after the prior checkpoint

### 1) FlyLo follow-through: from funnel diagnosis to concrete instrumentation
The screen remained on the FlyLo product workspace/thread, moving from the PRD into implementation coordination and a mobile ticket-purchase demo.

- A mobile view was shown in a darkened desktop shell: a centered phone UI with flight/fare cards and a bottom action. This is the clearest new demo frame: `shots/pm-155.png` (enlarged crop: `pm-155-crop.png`).
- The implementation thread made the instrumentation contract explicit:
  - Sticky-footer **Continue** is paired with `fare_selected`.
  - The thread distinguishes **mobile_web / native** (pixel-lock discussion).
  - `FUNNEL-P0-3` was being launched around the sticky-footer Continue + `fare_selected` path.
  - `FUNNEL-P0-4 search/fare instrumentation` was visibly marked **Running**.
  - A cloud agent was running; the owner said they would validate the PR when it landed and ping the relevant owners.
- Teachable takeaway: convert a vague “fare-select leak” into one event contract, one surface split (mobile web vs native), and a small set of named P0 work items that can be QA’d independently. Capture: `shots/pm-335.png` (crop: `pm-335-crop.png`).

### 2) Pixel/design lock and handoff chain
A coordination thread then recorded the cross-agent handoff:

- “All five P0s accepted.” Product calls were pixel-locked: instrument mobile web vs native from week 1, keep the prototype single-path until an explicit A/B decision, and keep seat work at P2.
- **Pixel Direction A (Cabin ladder)** was accepted; the message says to scaffold Direction A (not B) and tagged Einstein for QA.
- Acceptance was forwarded to **Eileen (build), Einstein (QA), and Nova (`fare_selected` on Continue)**.
- The practical pattern is: product acceptance → named design direction → build owner → QA owner → event/agent owner, with PRs as the gating artifact. Capture: `shots/pm-395.png` (crop: `pm-395-crop.png`).

### 3) Lessons slide: operating model after the learning curve
A new slide titled **“Lessons — What works once you're past the learning curve”** appeared (`shots/pm-455.png` and `pm-515.png`). The four visible principles:

1. **Named agents + separate memory** — broad mission, scoped memory; partition workloads so each agent stays excellent in its lane.
2. **Learn on the job** — a high-leverage instruction is to read past Slack and develop a style guide; teach continuously.
3. **Stay quiet unless needed** — silence is a feature; only ping when attention is actually needed.
4. **Agents all the way down** — EM agents manage IC agents that spin cloud agents; hierarchy beats one mega-prompt.

Teachable synthesis: specialization + bounded memory reduces context bleed; examples/style guides make agents improve in-place; escalation should be demand-driven; and a manager/worker hierarchy is more scalable than a single mega-prompt.

## Session transition / handoff

- Around the final third of the window, the video showed a full-screen **“Grok Bot Galaxy — Be right back”** card: `shots/pm-575.png`. This is an explicit BRB, not an end card.
- After the BRB, the stage returned with two presenters and a CTA slide. The visible four-step prompt was:
  1. Quote the challenge post on X.
  2. Explain what your Bot does.
  3. Include a link to your shared Bot template.
  4. Follow **@Grok & @Bot**.
  Captures: `shots/pm-635.png`, `shots/pm-695.png`.
- Chat during/after the BRB included thanks for the product-management presentation, requests to move the camera / speak louder, and questions about whether the challenge is international or US-based. No explicit **Founders** session start was observed during this capture window; the stage/CTA continued instead.

## Capture index

`pm-000.png`, `pm-035.png`, `pm-095.png`, `pm-155.png`, `pm-215.png`, `pm-275.png`, `pm-335.png`, `pm-395.png`, `pm-455.png`, `pm-515.png`, `pm-575.png`, `pm-635.png`, `pm-695.png` (plus enlarged crops for the mobile demo, implementation thread, coordination thread, and lessons slide).

---
# Galaxy Day 1 — PM remainder 3

**Capture window:** approximately 6:11–6:23 PM ET (22:11–22:23 UTC) on Tue Sep 15, 2026; requested ~12 minutes. The X broadcast remained **LIVE/playing and unmuted** at the end. The broadcast tab was left open.

## What changed after the previous checkpoint

### 1) Extended BRB, then return to an on-stage panel
- The capture opened on the same full-screen **“Grok Bot Galaxy — Be right back”** interstitial after the Lessons/CTA checkpoint. It was not an end-of-day card: the player stayed live and its duration continued to grow.
- Around the latter part of the window, the stage returned to a three-person conversation at the Grok Bot Galaxy set: two men (left and center; the center speaker wore a Grok-branded shirt) and a woman on the right. No speaker lower-thirds or explicit session title were visible.
- The panel stayed on screen through the end of the requested window; no Shub Gaur/Founders title card or clear Founders handoff appeared.

### 2) Teachable themes visible in the panel/chat
Audio was not transcribed here, so these are visual/chat-grounded notes rather than attributed quotes from the speakers:
- Audience discussion centered on **building real, profitable products** rather than demos that only generate novelty output. Chat explicitly praised an AI company showing work that “actually yields profit” and said it was remarkable to build a legitimate product in a week.
- The visible conversation prompted practical founder/operator questions: “What business are they building?”, “What are you guys building?”, and when someone can call themselves the manager of their own thing. Useful takeaway: the audience is testing the work against product ownership, business value, and operating responsibility—not just model capability.
- Chat also surfaced an operator-learning angle: Eric Jorgenson’s business books were recommended for people serious about building businesses.
- A brief black overlay/popup in the video showed role-like labels including **“Founding Eng,” “Growing Eng,” and “Knowledge Base Manager.”** Treating these as role labels (not a confirmed agenda slide), the visible pattern reinforces the event’s recurring theme of assembling specialized roles around a product/company.
- Additional audience signals: a viewer reported building “a crazy system”; another mentioned a local Grok Bot community meetup in Las Vegas that night; commenters asked for recordings and main takeaways.

## Session transition / handoff

- **BRB:** clearly observed at the start and persisted for several minutes.
- **Other handoff:** BRB resolved into an on-stage founder/business-oriented panel; this was the only new handoff observed in this window.
- **Founders (Shub Gaur, scheduled 4:00–5:30 PT):** **not clearly started** during the capture. No Founders title, Shub Gaur lower-third, or session-specific intro appeared.
- **End of day:** not observed. Stream remained live.

## Capture index

- `shots/pm-remainder3-brb-start.png` — BRB card near the start.
- `shots/pm-remainder3-brb-chat.png` — later BRB with active audience chat.
- `shots/pm-remainder3-panel-start.png` — panel return to the stage.
- `shots/pm-remainder3-panel-overlay.png` — panel with the brief role-label overlay and active chat.

---
# Galaxy Day 1 — founders remainder / monitoring window

**Broadcast:** X `Day 1: Grok Bot Galaxy Livestream` (`1AxRnZbVpjaxl`)
**Window:** ~6:24–6:38 PM ET (continuation of the requested ~12–15 minutes)
**State at end:** **Continued builders panel.** Founders/Shub session did **not** start during this window; no BRB or end-of-day observed.

## Timeline / visual changes

- **Start (~6:24):** Three-person on-stage panel after BRB; no Founders/Shub title. Audio enabled and remained enabled.
- **~6:27:** Still the same three-person builders panel; chat was moving, but no slide/title transition.
- **~6:30:** A screen-share/demo appeared while the three-person panel remained as a picture-in-picture inset. The demo was a Slack-like multi-agent workspace.
- **~6:30–6:32:** Camera cut to a close-up of one male panelist, then back to the three-person panel + demo.
- **~6:34:** Demo continued with updated agent/message/status overlays; still no Shub/Founders branding.
- **~6:36–6:38:** `tidraw` wireframe handoff appeared. The panel remained in the inset; this was still a builders/product walkthrough, not the Founders session.

## Dense teachable notes from on-screen material

### Multi-agent workspace / operating pattern

- Workspace visibly showed agents including **steve** (chief of staff), **grokpot** (prototyper), **tater** (engineer), **mash** (merge), **hashbrown** (reviewer), and **planetscape** (PM), plus a `Marketplace` area and a “Lauren @ Grok Bot Galaxy” user/workspace.
- A status/role card visibly rotated through combinations such as **Founding Eng**, **Growth Eng**, **Knowledge Base Manager**, and later **grokpot — prototyper**, **steve — chief of staff**, **tater — engineer**, with “23 more”/“8 more” agents.
- A telemetry card sampled during the demo showed **26 Bots** and roughly **870–888 Messages**, with **0–2 Working** and **10–11 Active** (values changed as the live demo progressed).
- The workflow pattern was: delegate a concrete product task to an agent, have the agent ask for a human handoff only when needed, then return a share link/screenshots/captions as the deliverable. The demo explicitly separated “screens are enough” from requiring a login.

### Product/task content shown in the demo

Visible messages in the workspace included:

- “cool — leaving the share link. board shot + captions are the deliverable.”
- “got the lock: venues · holographic tickets · merch. standing by — won’t mock ticket/merch until you look.”
- “no need to sign in on tidraw” followed by “yep — screens are enough. no tidraw login.”
- “drawing pillars now on tidraw — no holo ticket, claim flow, merch drop + detail. screens only, no sign-in.”
- A handoff banner read: **“Sign in to tidraw, then hand back — I’ll create the share link.”** with visible controls **“Skip this step”** and **“I’m done, continue”**. This indicates the agent pauses at an authentication boundary rather than inventing credentials or silently proceeding.

### tidraw wireframe / slide text

The readable wireframe page was headed **“PROJECT HOME”** and **“Grok Bot Art Exhibition”**, with a **THREE PILLARS** list:

- `[ Venues ]`
- `[ Tickets ]`
- `[ Merch ]`

A card labeled **“1 · TICKET FRONT”** read:

- **“Grok Bot Art Exhibition”**
- **“DATE / VENUE TBD”**
- **“SEAT GA / N”**

The rest of the page showed low-fidelity boxes for additional pages/components: stacked form fields, a row of four cards, and a large content/detail panel with small action buttons. This was a board/prototype sketch, not a polished final UI.

## Visible chat / quote-like context (lower confidence than slides)

- `DJM224` posted: “You can add a TEAM in charge of the budget, and it has bots, but those bots can also be the budget guy from the skunkworks TEAM or the engineering TEAM.” This aligns with the visible team/agent orchestration theme, but is a viewer chat quote rather than slide text.
- `Cryptonic` wrote a viewer idea about 3D-printing a bot figure with an ESP32 so it could be spoken to at a table; clearly chat/community speculation, not a confirmed product announcement.
- Other visible chat was mostly reactions and noise (e.g. “this is cooking,” “awesome to watch,” and comments about a bot/desk pet), so it was not treated as authoritative session content.

## Screenshots

Saved under `/workspace/galaxy-day1/shots/`:

- `panel-1824-baseline.png` — three-person panel baseline.
- `panel-1827.png` — panel with live chat.
- `screen-share-1830.png` — first screen-share appearance.
- `speaker-closeup-1830.png` — close-up speaker view and role card.
- `screen-share-1831-full.png` — readable multi-agent workspace demo.
- `screen-share-1834-full.png` — later workspace state and agent role card.
- `wireframe-handoff-1836-full.png` — tidraw handoff + wireframe.
- `wireframe-handoff-1836-crop.png` — enlarged wireframe crop for text legibility.

---
# Grok Bot Galaxy — Day 1, Founders remainder

Capture window: Tue Sep 15 2026, ~6:38 PM ET (3:38 PM PT onward)
Broadcast: X / Grok Bot Galaxy Day 1

## ~6:38 PM ET — builders panel / tidraw “Grok Bot Art Exhibition”
- On-screen tidraw board is a low-fidelity product wireframe titled **“Grok Bot Art Exhibition”**.
- Left/top content block shows a simple event page concept with three visible pillars/sections: **Venues**, **Tickets**, and **Merch**.
- Center/top is labeled **“1. TICKET FRONT”** (or ticket-flow/front); card text references Grok Bot Art Exhibition and selecting/adding a venue/date, with a visible action button.
- Right/top block is a follow-on step with stacked input-like rows and a **CONTINUE** button; it appears to collect ticket/order details.
- Lower-left block is a payment/checkout-style step with fields, a **PAY** button, and **CLEAR TICKET**; a long footer/confirmation strip sits below.
- Lower-middle block is labeled **“2. … CART”** (cart flow); it has several small product/category cards and a button/selection state.
- Lower-right block is a sparse form/summary panel with two small controls and a larger bottom button, likely the merch/order detail/confirmation portion.
- The wireframe is being drawn in tidraw, with a white canvas, black outlined cards, color swatches/format toolbar on right and drawing toolbar along bottom.
- Video also shows the live panel: three people at a table with laptops; a dark participant tile at right reads **Sip** with other panel participants listed (Chief, dr eggbot, “4 more”).
- Chat is visible; messages include “Dogfooding,” “how is none of the 3 laughing,” and “Open Sauce referenced!” (chat is ancillary, not treated as demo claims).

## Status
- At this capture, this is still **builders** content; no clear Founders/Shub Gaur start seen yet.

## ~6:40 PM ET — prototype/chat requirements surfaced
- A shared “grokpot” workspace view shows the event/art-exhibition board being discussed as a prototype (“pillars board”). The left sidebar includes roles/channels such as **prototype**, **engineer**, **merge**, **reviewer**, and **DAO**.
- Visible checklist/flow notes:
  1. **“2 ticket front + HOLO”** (ticket-front plus a “HOLO” step).
  2. **“3 claim: tier + playclaim”** (tier claim / play claim language as shown).
  3. **“4 merch drop + item.”**
  4. **“no share link (still needs sign-in). say if you want a pass with even fewer words.”** This explicitly flags sign-in as a dependency before sharing the tidraw board.
- A draft merch idea list is visible: **pictures from SpaceX launches; Grok Bot stress balls; hat with the Grok Bot eyes; beanie; Grok Bot character plushies.**
- Right-side explanatory text says: **“Routines are recurring tasks this Bot runs on a schedule. Ask it in chat to set one up.”** This is a teachable product concept: routines are scheduled, chat-configured bot tasks.
- A “Needs your attention” prompt at top says to sign in to tidraw, hand back the share link, and offers “Skip this step” / “I’m done, continue,” reinforcing that the share-link flow is not yet complete.
- Live camera remains the same builders panel; no Founders/Shub Gaur handoff observed in this frame.

## ~6:42 PM ET — clearer tidraw wireframe overview
- Tidraw is now zoomed/centered on a board captioned **“tidraw pillars tickets merch wireframes.”**
- Top-left “PROJECT HOME” explicitly reads **Grok Bot Art Exhibition** and **THE THREE PILLARS**, with three bullets: **Venues / Tickets / Merch**.
- The six-panel flow is legible:
  - **1. TICKET FRONT** — “Grok Bot Art Exhibition,” a **DATE / VENUE** area, a “HOLO” option and a right-side selector/action (looks like select/go; exact tiny label uncertain).
  - **2a. CLAIM 1** — a **PICK TIER** form; a tier row shows **GOLD PREMIUM - $15** and a **CONTINUE** button.
  - **2b. CLAIM 2** — **EMAIL / WALLET** fields, a **PAY** button, **CLEAR TICKET**, and a long ticket/receipt strip below. This makes the ticket funnel concrete: choose date/venue → tier → email/wallet → pay → ticket receipt.
  - **3. MERCH DROP** — a drop/live selector followed by item cards labeled **TEE**, **POSTER**, **STICKER**, and **TOY**.
  - **4. MERCH ITEM** — **HOLO POSTER - $28**, controls for **SIZE A2** and **VARIANT HOLO**, plus **ADD TO CART**.
- Design/implementation signal: these are low-fidelity boxes but already encode the information architecture and checkout state transitions for tickets and merch.
- Builders panel camera remains on screen; right participant tile lists **Growth Eng**, **Founding Eng**, and **Knowledge Base Manager**. No clear Founders/Shub Gaur start yet.

## ~6:44 PM ET — engineering status + merch ideation agent
- Engineering workspace view (“tater”) showed a concrete delivery queue/status:
  - **#22** posted to PR reviews (green, awaiting review).
  - **#20** recipe fixed; media still placeholder while an agent finishes real screenshots.
  - **#18** rebasing for a Vercel root-directory miss.
  - **Overpass** still in flight.
  - A separate visible status line says #18/#20/#22 are being driven to “mash,” with #18’s rebase already rolling.
- The bot dashboard visibly reported **27 Bots**, about **900+ Messages**, **3 Working**, **12 Active** (counts changed slightly between frames), demonstrating a live multi-agent operating view.
- In the “steve” workspace, a merch-design agent conversation says: **“ask drop to use grok imagine to visualize these merch ideas,”** and “kicking drop — grok imagine visuals for the three Drop 001 ideas.”
- Crucial workflow clarification: earlier ideas are “just for reference”; **drop invents new merch ideas, then imagines them**. It promises “fresh concepts + images coming.” This is a useful human-in-the-loop pattern: seed/reference material is not copied verbatim; the merch agent generates novel concepts and image drafts.
- Right panel showed a scheduled **Venue-finder status** routine (every 5 minutes on weekdays, time truncated) and a Google screen connecting, indicating browser/tool use by the agent.
- Camera now shows four people at the builders table; Founders/Shub Gaur still not clearly started.

## ~6:46 PM ET — Drop 001 merch concepts (new, not copied)
- The merch agent explicitly states: **“clean do-over — three brand-new Drop 001 ideas, none of the reference set.”** This is a clear example of separating references from generated output.
- “Fresh Drop 001 set (reference pile untouched)” proposes:
  1. **Desk Torch** — mini industrial torch candle, “flamethrower energy,” desk object — **$22–32**.
  2. **Signal Socks** — black crew socks with violet/teal equalizer bars, “gallery-night feel” — **$18–24**.
  3. **Night Launch Folio** — limited foil launch print in black folio — **$40–60**.
- Three visual mockups appear beneath the list (torch-like black object, dark sock with colored signal graphic, black folio with luminous launch image).
- A poll/card asks **“Which locks as Drop 001?”** with choices including Desk Torch, Signal Socks, Night Launch Folio, and “Remix — weirder”; the on-screen card is marked **Dismissed** in this later frame, so no selection can be inferred.
- A follow-up request asks whether the bot can **look up Grok Bot reference images on the web first**, showing the next possible research step, but no web research result is visible yet.
- Live camera still shows the builders group; no Founders/Shub Gaur transition.

## ~6:48 PM ET — refined merch pitches and human narrowing
- A new merch pass is “locked” and explicitly built on **pill eyes + simple shapes**, “not the old reference pile.” Three new pitches:
  1. **Roster Pin Pack** — six enamel pins matching avatar shapes (teardrop / triangle / cloud / circle / capsule / clover), white pill eyes, “jacket drip for the show” — **$28–36**.
  2. **Soft Blob Plush** — one oversized circle-head plush, white standalone pill eyes, charcoal or cream; “dogfood / photo bait” — **$32–42**.
  3. **Eye Cutout Beanie** — black beanie with felt/embroidered circle face and pill-eye cutouts; framed as a character mark, not the old “eye hat” spark — **$34–44**.
- The agent asks whether to imagine all three against official references; the visible human reply narrows the scope: **“lets start with just the grok bot plushies maybe.”**
- Agent confirms the narrowed plan: **“plushies only. generating a few Soft Blob variants off the official pill-eye character.”** Teachable pattern: agent proposes a batch, human chooses a subset, generation follows the selected brief.
- Panel/participant tile still identifies a builders setup (Growth Eng, Founding Eng, Creative Director, etc.); Founders/Shub Gaur not started.

## ~6:50 PM ET — plush variants, review loop, flagship choice
- The merch agent generates three **Soft Blob** directions from the official pill-eye character:
  1. **Hero Circle (charcoal)** — classic black blob + white pill eyes; intended to read as Grok Bot at a glance — **$32–42**.
  2. **Cream Circle** — same silhouette with lighter body, softer gift-shop feel — **$32–42**.
  3. **Roster Mini Set** — circle + triangle + cloud, matching the avatar system; “limited museum edition” energy — **$38–48**.
- Human lead selects **Hero Circle charcoal** as flagship, with the roster minis as a possible second SKU if the show wants a set. Agent offers to refine eyes/size/color or “ping Steve with the plush lock.”
- Quality-control loop is explicit: human says **“the eyes look a little bit off — check against the reference images”**; agent replies it is checking plush eyes against official refs and will regenerate if needed.
- Camera briefly shows a closer two-person view, then the builders panel; participant tile still shows Drop/Foil/Tater and others. This remains builders work, not Founders/Shub Gaur.

## ~6:53 PM ET — cutoff status
- At the ~15-minute cutoff, the stream is still visibly on the **builders panel**: four people at the Grok Bot Galaxy table, with the on-screen participant label including **Founding Eng**, **Growth Eng**, and **Operator Research**.
- Dashboard counts in the final frame read **29 Bots**, **927 Messages**, **1 Working**, **16 Active**.
- No explicit Founders/Shub Gaur start, BRB, or Founders title card appeared during this monitoring window. Leave the tab playing and unmuted for the parent agent’s next handoff.

---
# Galaxy Day 1 — Founders remainder capture (2026-09-15)

**Window:** ~6:56–7:08 PM ET (3:56–4:08 PM PT)  
**Source:** https://x.com/i/broadcasts/1AxRnZbVpjaxl  
**Status:** **Founders segment clearly started** at approximately 7:00–7:01 PM ET. The on-stage presenter then moved into the official Grok Bot deck; the agenda explicitly includes “Founder Demos.” No BRB/intermission was observed. Capture stopped within the requested ~15-minute window. The tab was left open, playing, and unmuted.

## Screenshots

Saved under `/workspace/galaxy-day1/shots/`:

- `2026-09-15_1856_builders-table.png` — builders still at the roundtable (Soft Blob / ticket-merch work context).
- `2026-09-15_1858_builders-table.png` — continued roundtable discussion.
- `2026-09-15_1859_builders-stats.png` — builders plus live bot/message stats overlay.
- `2026-09-15_1900_founders-stage.png` — cut to the solo on-stage presenter.
- `2026-09-15_1900_stage-speaker.png` — presenter holding the clicker; transition into deck.
- `2026-09-15_1901_founders-agenda.png` — agenda slide.
- `2026-09-15_1901_ai-maturity-curve.png` — AI maturity curve.
- `2026-09-15_1902_introducing-grok-bot.png` — product overview / UI slide.
- `2026-09-15_1903_why-grok-bot.png` — value proposition grid.
- `2026-09-15_1904_build-better.png` — “better time to build” slide.
- `2026-09-15_1905_founder-use-cases.png` — founder use cases.

## Dense teachable notes

### Builder handoff
- Until roughly 7:00 PM ET, the stream remained on the four-person builder table: laptops open, ongoing discussion around the Soft Blob plush and ticket/merch wireframes; no new full-screen deck was visible.
- The video then cut to a single presenter on stage against the Grok Bot backdrop. This is the clear transition into the scheduled Founders block.

### Agenda (official deck)
The deck’s sequence is: **A Quick Intro → What Can Grok Bot do? → Why Grok Bot → Founder Demos → Power User Tips → Recap → Q&A.** This is the strongest confirmation that Founders had begun, rather than another builder segment.

### AI Maturity Curve
The slide frames increasing leverage as:
1. **Ask** — chatbots.
2. **Do a task** — copilots.
3. **Automate a job** — a bot.
4. **Staff function** — a team of bots.

Teaching takeaway: the intended progression is from conversational assistance to delegated, persistent work units and eventually a coordinated bot team.

### Introducing Grok Bot
The product is presented as a set of job-specific bots that behave like teammates:
- Create bots for different jobs; examples shown include **Sales Outbound, Chief of Staff, Inbox Manager, Website designer,** and **Debug**.
- Message bots like teammates; each bot keeps context in memory and is intended to improve over time.
- Bots can log into the user’s tools and use them, rather than only returning advice.
- Set up automations and routines; share bots with other people.
- The UI example shows a Sales Outbound bot drafting outreach and a connected-tool task running in a working state.

### Why Grok Bot
The value proposition grid emphasizes:
- **Easy as iMessage** — a simple conversational interface for multiple specialist bots.
- **Always-on agents** — depicted as 24/7 availability.
- **Uses your tools like you** — bots operate through the same connected tools/workflows.
- **Finishes the work** — create a bot for a job, give direction, let it figure out execution, and set automations/routines.
- **Shareable templates** — reusable bots can be shared; example card: “Peng shared Kenny with you.”

### Build thesis
The central message: **“There has never been a better time to build.”** The supporting claims are to **ship faster than ever, delegate full tasks end-to-end, automate yourself and your team,** and do things that normally do not scale—because agents can now make them scalable.

### Founder use cases
Four concrete founder workflows were shown:
- **Close Customers, on Autopilot:** have a bot research prospects, respond to issues and feedback, follow up, and follow people on social end-to-end.
- **QA + Updates on Product Changes:** understand how the product has changed over time to prioritize work and course-correct quickly.
- **Quickly Adapt to Competitors:** counter-position faster than competitors can respond and out-ship them to market.
- **Ship Feedback Quickly:** collect customer feedback from Slack and email, then use Cloud Agents to ship updates quickly.

## Final state
At the end of capture the official Founders presentation was still live on the Founder Use Cases slide. Video health was verified: playing (`paused=false`) and unmuted (`muted=false`).

---
# Founders session — remainder capture

- **Capture window:** started Tue Sep 15, 2026 ~7:09 PM UTC−4; broadcast was live and unmuted.
- **Starting visual:** slide titled **“Meet the crew”**. Four bots shown: **Close Bot** (“Close Customers”), **Prod Bot** (“Know What’s Shipped”), **Stalk Bot** (“Stalk Competition”), **Proto Bot** (“Feedback → PR”). Bottom-right says **“Guest Starring: YapBot”** / “Talk Like Me”. Presenter visible at left; name not shown.

## Timeline / slides / demos


### 00:45 — Close Bot / customer-workflow demo
- Screen recording of a Mac-style bot workspace with bot roster: Close Bot (Customer…), Prod Bot (Product), Stalk Bot (NOTED in…), Proto Bot (Design), Yap Bot (Comms), Misc Bot (Random).
- Close Bot draft/customer note (signed “Shub”) says credits are added when the workspace is actually using NOTED (notes created/shared, comments on action items, first use of templates/capture); shared templates keep recurring meetings on the same sections; Capture prevents split-room/client calls from losing notes; commits live on the action item rather than a side thread; export with timestamps for quality/legal. Credits can be held on next invoice and matched to the chat; placeholders must be swapped before sending.
- Example action: pull **Northwind** usage and send the weekly series to Misc Bot for charting. Range shown **2026-07-14 to 2026-09-14**; active note-takers, meetings, standups, vendor calls, Zoom-bot %, plus **12 seats / 11 active**. (UI label indicates an example chart request.)
- “My Bots” panel lists Close Bot use cases: call prep (telemetry + recommendations + walkthrough), compounding + follow-up, activation messages and credits, pipeline gen (calls Yap Bot), and other customer-related tasks. Prod Bot: understand what shipped/unshipped and make product decisions using key insights/data.

### ~02:15 — Close Bot landing-page audit demo
- Close Bot opened a crisp, real-HTML preview named **EXAMPLE—prep.html**. Instruction at top: “Call this out early.” It records the path **landing → Get started → signup** and says the landing is clean, but a signup cookie banner covers **Create account** above the fold; recommendation is to move the banner or delay it until after the primary CTA.
- Example fictional site: **Northwind Labs**. Headline: **“Ops notes that keep lab standups and vendor calls honest.”** Supporting copy positions it for biotech ops teams to capture standups, diligence calls and follow-ups in one shared place. A “Today · Lab standup” card lists reagent delay (Vendor A / Priya), CRO diligence notes (Marcus), QC folder export (Alex), and breakout-room recap (Jordan). Explicitly marked fictional / NOTED demo, not a real product.
- Teachability: bot can navigate a local/preview site, inspect the actual rendered HTML, identify a conversion blocker, and produce a concise prioritized UX callout.

### ~03:00 — Close Bot activity & billing view
- Another **EXAMPLE—prep.html** panel, **ACTIVITY AND BILLING**, with field/value/as-of/source provenance. Synthetic Northwind Labs data:
  - Arrangement: **Team $60/mo**; last invoice **paid on time**; balance **$0**; renewal **2026-10-30**.
  - Seats **11/12 (92%)**; meetings last 30d **72 (+5.9% vs prior)**; Zoom bot in **88% of meetings** (week ending 2026-09-14).
  - Lab standup template **42 uses / 30d**; vendor template **19 uses**, first use **2026-09-12**; templates shared with teammates: **Yes** (called out as a “secret perk path”).
- Sources are explicitly shown (synthetic billing.md, dossier, product analytics, activation). A chart below tracks meetings transcribed, active note-takers, and Zoom-bot/adoption percentage over time.
- Teachability: combine billing state, renewal risk, seat utilization, activity/adoption and activation milestones in one prep surface, with dates and source attribution.

### ~03:45 — Recent posts / open threads in account prep
- **RECENT POSTS (EXAMPLE / PLACEHOLDERS)** list: 2026-08-19 “Breakouts drop notes”; 2026-08-27 “templates not shareable”; 2026-09-01 “comments not anchored”; 2026-09-03 “positive vendor recap time”; 2026-09-11 “Marcus needs timestamp export.”
- Embedded synthetic @northwindlabs post says: **“We cut weekly vendor recap in half after switching lab notes to NOTED.”** Marked as a demo/example post.
- **OPEN THREADS:** breakouts answer owed by **2026-09-18/20**; **SSO checklist owed by us**.
- Teachability: prep is not just usage/billing—surface recent customer pain/ wins and unresolved obligations for the next conversation.

### ~04:30 — Close Bot call-prep output
- Generated **“Call prep — Northwind Labs (EXAMPLE DATA)”** for Wed **2026-09-17, 3:00 PM CT / 4:00 PM ET**, attendees **Priya Shah and Marcus Lee**.
- Snapshot repeats: Team $60/mo, renewal 2026-10-30, **11/12 seats (92%)**, Zoom bot **88%**, **72 meetings/30d (+5.9%)**, templates shared across teammates.
- Risks: **breakouts unanswered since 2026-09-08** and cookie banner blocking signup. Agenda: breakout-follow ETA, reinforce templates, diligence export only after tradeoffs. Key question: if Breakout Follow lands with a dated ETA, is Diligence Export Marcus’s next gate?
- Follow-up section says transcript is ingested; **do not pitch seats or Business before Breakout Follow ships**. Follow-up marked READY in a draft path; prompts say “Follow Onboarding” and draft linked next steps for Priya/Marcus—**do not send until yes**.
- Support section references **NW-104 speaker labels** and **NW-105 Diligence Export**, answers in support/ and Yap-ready. Activation section: templates shared with teammates → **$1000 secret perk READY** in a draft path; approve credit + send. Routine panel shows Call prep, Call recap, Weekly touch review, and Trigger scan all **paused**.
- Teachable pattern: grounded prep → risks → agenda → one decision question → draft-only follow-up, with explicit human approval before sending credits/messages.

### ~05:15 — Call-prep output continued (lower sections)
- The lower output exposes more gated actions: “Sign” is a **12-seat Business draft + browser pause** (E2E demo path), not an automatic transaction. “Pipeline + calendar” says **Brightline picked Thu 2026-09-18 11:00 CT** and the invite draft is ready; phrase to trigger it is **“create the Brightline hold”**. A subsequent “Harbor contract” section begins below.
- The right-side routine controls remain paused. The UI visibly distinguishes draft/ready from actually sending or signing.

### ~06:00 — Call-prep lower section: contract risk
- Final visible section is **“7. Harbor contract”**: **at risk: failed payment + usage down vs Northwind healthy**, with a linked/demo path `harbor-legal/demo-contract.md`.
- This reinforces the cross-account comparison pattern (billing failure + declining usage is a risk signal) and that contract/legal artifacts can be linked into prep.

### ~06:45 — Demo-flow routing prompt
- Bottom of the prep output maps to `/workspace/customers/DEMO_FLOW.md` and asks which beat to run live next: **send follow-up, approve $1000, create Brightline hold, etc.**
- The flow is intentionally staged as selectable, approval-gated beats rather than a free-running automation.

### ~07:30 — Prod Bot / product-prioritization demo
- Switched to **Prod Bot**. It explicitly says the content is fine for demos, **not a real monetization decision**, and only matters before putting real cards in.
- “What I’d prioritize”: **P0** name fields + destination + HND (unblocks trusting #518); **P1** reduce prospect-compare friction; **P2** make the “multi-city stays cut” explicit so support/sales do not thrash. It asks whether to lock yes/no on the top three so later rundowns compound from them.
- Product-call choices shown as a lightweight decision capture:
  - **Yes** freeze checkout UX until name + HND fixed / **No** keep shipping checkout features.
  - **Yes** simplify Prospect compare / recommend a cabin / **No** keep full Prospect compare as-is.
  - **Yes** keep multi-city removed / **No** plan to restore a simpler multi-city later.
  - Freeform “Type your own answer.”
- Side panel shows a flight-search example (**LHR → SFO**) and Prod Bot routine **Daily rundown — every day at 9:00 AM**.
- Teachability: turn product analysis into durable, explicit decisions with selectable responses and a scheduled compounding rundown.

### ~08:15 — Prod Bot evidence-backed QA
- Follow-on screen labels an engagement result **“+0.4% engaged scroll, 0% retention — cosmetic.”** QA findings: destination refine **LHR→SFO sometimes flips to HND**; traveller full/given/family names do not reliably stick after edit.
- It reframes the decision with evidence: freeze checkout until traveller names + HND are fixed; simplify Prospect compare to a recommended cabin to protect DP; and decide whether multi-city is permanently cut (say so) or gets a narrower restore.
- Evidence area includes two video/play tiles and screenshot thumbnails (flight search, form/detail, and an “LHR→SFO +3” panel), illustrating that the bot grounds its recommendation in clips/screenshots instead of vanity engagement.

### ~09:00 — Product evidence refresh
- Prod Bot adds **“Quiet-cabin line initialized.”** The engagement line remains explicitly classified as cosmetic (**+0.4% engaged scroll, 0% retention**).
- Evidence now includes a visible short clip titled **“The quiet way to fly”** (0:50) alongside the earlier QA/video and screenshot evidence. This is a good example of separating a newly initialized product line from actual retention impact.

### ~09:45 — Stalk Bot / competitor + responsibility loop
- Switched to **Stalk Bot**. It asks what would bring the user back: **Apple/Siri capture—Craft won that workflow; export/leaving with notes; price/seats for ~4 people; a missing feature; or “Other”** (one line is fine). This is an explicit churn/return-reason capture.
- It saves a result under `/workspace/dossiers/_us/churn/` and reports **“Stalk loop’s complete.”**
- Follow-up asks for an MD of all current responsibilities (without demo specifics) to support a revamp. It drafts `stalk-bot-responsibilities.md` (~6.5 kB) from the NOTED baseline: Craft + Notion modules, pulse delivery shape, churn → Yap/Shub, cadence, conduct, artifacts and voice; user can say what to cut/split/add.
- Side panel routine schedule: **Competitor pulse** Monday/Wednesday/Friday at 9:00 AM; **Competitor human watch** weekdays at 10:00 AM; **Weekly deep dive** Friday at 10:00 AM.
- Teachability: competitor intelligence is turned into a recurring cadence plus a maintained, editable responsibility artifact—not a one-off report.

### ~11:15 — Stalk Bot live competitor pulse
- User asks **“do a competitor pulse rn”**; Stalk Bot returns **NOTED competitor pulse — Tue Sep 15 (~Sep 8)**.
- **Craft — product:** v3.6.5; Dark Mode; Siri for docs/tasks (Sep 14); App Store iOS 27 featuring + Siri demo (Sep 15); Quip migration page still live; pricing unchanged. (Rendered text is compact; exact version/date are as shown.)
- **Craft — hiring:** still “not hiring actively.”
- **Craft — mail:** nurture live on `northwind-craft@agentmail.to`: Welcome, Teams trial through Sep 28, and Viktor “Write everything down” daily schedule ping.
- Attachment **2026-09-14-pulse-teardown.html** (~3.6 MB), with three short evidence clips (0:20, 0:20, and +2 / 0:14) plus “Craft home + pricing” evidence.
- Teachability: a prompt produces a dated, source/evidence-linked competitor digest spanning product, hiring, and outbound/nurture—not just a summary.

### ~12:45 — Stalk Bot competitor synthesis / actions
- Comparison against NOTED: **Craft owns Apple capture + App Store shell** and has conversion-shaped trial→Teams mail; **Notion owns agent depth** (sub-agents, workspace rules, MCP/Skills) and hiring signal, while its free-AI cliff/Workers list remain paid.
- Proactive recommendations: ship Capture for Apple Intelligence/Siri with a “no second notes app” line; pin **Free / Pro $8 / Team $14** against Notion’s AI meter + Workers cliff and Craft’s trial clock; push document-shaped Teams with no workspace tax/credit cliff.
- Decisions requested: ship/kill Apple Intelligence capture this quarter; pricing-clarity page vs Notion Free AI + Workers; document-shaped Teams page for **5–20-person teams**.
- Example in-flight: Capture for Apple Intelligence, target **Oct 30**, owner Product. Example churn: Apple Design Studio left Pro (~4 seats) on Sep 12 for Craft (Apple/Siri); Yap is drafting a Shub winback and will drop it in when ready.

### ~13:30 — Proto Bot / ShareBotCard artifact flow
- Switched to **Proto Bot**. A “ShareBotCard” prototype has landed; bot tries to grab a screenshot of the live card, with the prototype on the main screen and a shader backdrop. It reports pulling the live card screenshot and sending it once it has the image, then says it is still hunting the hosted artifact URL to drop the image in chat.
- The UI shows **“Auto-review Paused This Action — Expired”** with “Show the details.” This is a visible safety/approval gate: the artifact action did not silently complete.
- Side panel says routines are recurring tasks this bot runs on a schedule and can be set up in chat. The draft input is **“pull the most recent customer feed.”**
- Teachability: prototype/evidence artifacts can be staged and shared, while expired approval pauses the outbound action for review.

### ~14:15 — Proto Bot customer-feedback follow-up
- After the “pull the most recent customer feedback” prompt, Proto Bot surfaces: **“A customer said the share button for bot templates wasn’t exciting enough — they wanted it to pop.”**
- ShareBotCard artifact work remains visibly paused/expired; no evidence of an outbound send. This was the last observed state in the requested ~12–15 minute window.

## Window close
- Broadcast remained **LIVE** and **unmuted** throughout capture; tab left open. No Q&A, BRB, or end state was observed in this window.

---
# Galaxy Day 1 — founders remainder capture

**Date/window:** 2026-09-15, approx. 19:29–19:42 EDT (UTC-4)  
**Broadcast:** https://x.com/i/broadcasts/1AxRnZbVpjaxl  
**Capture state:** Playback remained running and unmuted throughout (controls showed `Pause` and `Mute`). No BRB card or end-of-stream screen appeared during the window.

## New slides / demos captured

### Misc Bot — FOMO / preview lookup (19:29)
- Misc Bot checks whether Drake’s FOMO has dropped yet; the on-screen response says it is not a short film but an album, set for Sep 15 at 9 PM ET on YouTube, Spotify, and Apple Music.
- Bot found a short teaser (“neon speedboat + two versions of your life”), the official drop link on Instagram, and a YouTube trailer link; it says the full film still launches at 9 PM ET.
- Visible demo claim: bot can look up a release/preview and return source links across social/video/music services.

### Commitments / shareable bot card (19:30)
- Commitments bot describes itself as packing a shareable copy: it read mentions across Notion, weekday/reaction watchers, and Slack acknowledgements.
- Demo copy says custom skills (routines) and Slack acknowledgements are needed; “Notion, Slack, Gmail” are listed as inputs.
- A share card is shown as unpublished, with a “Publish” action and a warning that an unshipped staged item must be confirmed before publishing. Product lesson: bots can package their configuration/behavior as a reviewable share card, but publishing is gated.

### Proto Bot — ShareBotCard localhost prototype (19:30)
- User feedback: the bot-template share button was not prominent enough; user wanted it to pop.
- Proto Bot shows a flat-gradient share-review card and says it is easy to miss.
- It kicks Opus 5 (high/fast) to make the avatar backdrop a live shader on localhost. Visible work item: “ShareBotCard localhost prototype,” marked Done; 19 files changed, +2742/-2; “Open in Web” available.
- Product claim: the agent can turn feedback into a UI prototype and delegate an implementation task to a coding model.

### Recap — “What we learned” (19:31)
- **Let your bots run free!** The more access and freedom you give bots, the more they can do; give them access to your tools.
- **Invest in your bots!** Bots get better over time as they learn preferences. Feedback plus time spent managing them helps everyone win.
- **Think deeply about delegation!** Grok Bot is described as extremely powerful; spend 1–2 hours going through responsibilities and setting up bots.

### Power-user tip — optimizing costs: browser use (19:32)
- Slide headline: **“Browser use is powerful (and expensive!)”**
- Prefer connectors when possible. The Sales Outbound example says it is already logged into Salesforce, LinkedIn, and Gmail and will use connectors.
- If there is no connector, the slide suggests monitoring network requests and hitting the API next time.
- Visible result: 25 drafts for the top 8 accounts are ready in the inbox; the bot found 3 APIs to hit instead of using the browser.
- Routine examples on the demo: morning briefing daily at 8:00 AM, inbox cleanup weekdays at 6:00 PM, weekly team update paused.
- Product claim/lesson: browser automation works but can cost more; connectors/API calls are the cheaper, repeatable path.

### Power-user tip — routines (19:33)
- Slide headline: **“Routines are awesome (but audit them!)”**
- Expense Manager example: an hourly expense pass pulled 9 receipts from Gmail, matched 8 to open expenses, attached files, and coded them to categories.
- User asks to change the pass to weekly on Fridays at 8 AM; bot confirms the schedule change, says it will catch anything that lands before Friday, and will only ping exceptions.
- Routine list shown: weekly expense pass Friday 8:00 AM; new receipt scan weekdays 9:00 AM; month-end close prep paused.
- Product lesson: recurring routines should be audited and tuned; exception-only notifications reduce noise.

### “More Rapid-Fire Tips” (19:34)
- **Make a voice bot:** have it learn from texts, emails, Slack messages, etc., and improve over time.
- **Import your cookies:** slide explicitly says to give the bot cookies so it stays signed in to tools, and adds “let them use your IP!” (Captured as a stated slide claim, not independently verified.)
- **Group bots by expertise/scope.**
- **Great skills + saved learnings >>**; spend 1–2 hours going through responsibilities and setting up bots.
- **Bots will learn from you:** after enough tagging, they start doing the classification automatically.
- **Run auto-optimization routines:** more access/freedom gives bots more ability to act.

### Thank-you / QR slide (19:35)
- “Thank you” slide with a QR code labeled **“Steal Stalk Bot.”**
- After this slide the presenter remained on camera, speaking with a headset mic; the video did not show a readable Q&A slide or on-screen questions.

## Q&A / ending status
- From roughly 19:36 through the end of this capture window, the video showed the presenter in close-up speaking/gesturing against the bot logo backdrop. No questions or answers were legible in the video frame, and the chat pane contained viewer messages rather than a transcript.
- No BRB notice, “stream ended,” or “Day 1 wraps” card appeared. At the final check (~19:42 EDT), the broadcast was still playing and unmuted; controls still showed `Pause` and `Mute` (meaning it was live/playing and not muted).

## Screenshot index
- `shots/2026-09-15_1929_misc-bot-fomo.png`
- `shots/2026-09-15_1930_commitments-demo.png`
- `shots/2026-09-15_1930_protobot-share-card.png`
- `shots/2026-09-15_1931_recap-what-we-learned.png`
- `shots/2026-09-15_1932_optimizing-costs.png`
- `shots/2026-09-15_1933_routines-audit.png`
- `shots/2026-09-15_1934_rapid-fire-tips-1.png`
- `shots/2026-09-15_1935_thank-you-stalk-bot-qr.png`
- `shots/2026-09-15_1936_qna-presenter.png`

**Post-capture verification:** At the final tab check after note writing (~19:44 EDT), the controls still read `Pause` and `Mute`; the tab was left open, playing, and unmuted.

---
# Founders thank-you + Q&A remainder

- **Window observed:** 2026-09-15, approximately 7:45–8:00 PM ET (about 14–15 minutes).
- **Source:** X broadcast `https://x.com/i/broadcasts/1AxRnZbVpjaxl`
- **Playback state:** Stream was still playing and live at the end of the window; audio was unmuted. No stream-end card, BRB, or explicit “Day 1 wrap” was observed.

## Visual capture / scene changes

- **~7:45 PM:** Presenter on the Grok Bot Galaxy stage, answering questions on camera. Background was the Grok Bot logo; no readable question text, captions, or slide content.
- **~7:51 PM:** Close-up of the presenter, still speaking; no readable on-screen Q&A text.
- **~7:54 PM:** Three-person roundtable in the Grok Bot Galaxy room (two people at laptops and a woman with a microphone/papers). A whiteboard was visible behind them, but writing was too small/soft to read reliably; no legible question or answer could be transcribed.
- **~7:57–8:00 PM:** Split-screen: remote woman speaking on the left and the in-room three-person panel on the right. No captions, slides, demos, or end card appeared.

## Q&A substance

No readable questions or captions were available in the captured video frames. I could not reliably transcribe audible content from the stream, so there are **no substantive Q&A claims recorded** rather than guessing. Visible context supports that Q&A continued, moving from the solo presenter to an in-room panel and then a remote split-screen participant.

## Screenshots

- `shots/2026-09-15_1945ET_founders-qa-stage.png`
- `shots/2026-09-15_1951ET_founders-qa-presenter.png`
- `shots/2026-09-15_1954ET_founders-qa-roundtable.png`
- `shots/2026-09-15_1957ET_founders-qa-split-screen.png`
- `shots/2026-09-15_2000ET_founders-qa-final.png`

---
# Founders Q&A remainder 7 — Day 1

Monitoring window: 2026-09-15 8:03 PM–8:20 PM ET (2026-09-16 00:03–00:20 UTC)
Source: https://x.com/i/broadcasts/1AxRnZbVpjaxl

## Stream state at end
- **Still LIVE and playing, unmuted.** The tab was left open and no playback controls were changed.
- No BRB screen, end card, explicit Day 1 wrap, or explicit “builders return” notice appeared during this window.

## Readable on-screen text only
- Persistent lower-left overlay: **“LIVE”**, **“1M views”**, **“Grok Bot Galaxy”**, **“Day 1”**.
- In-room backdrop: **“Grok Bot Galaxy”**.
- No readable captions or audience questions appeared. Whiteboard writing was visible in the room shots but too small to transcribe reliably; it is intentionally omitted.

## Scene changes / screenshots
- ~8:03 PM ET: remote guest full-frame; the persistent LIVE/1M views/Grok Bot Galaxy Day 1 overlay was visible.
- ~8:07 PM ET: split-screen appeared — remote guest on the left and three-person in-room panel on the right; backdrop text “Grok Bot Galaxy” visible.
- ~8:11 and ~8:15 PM ET: split-screen remained live; no readable Qs/captions/slides.
- ~8:20 PM ET: remote guest feed no longer visible; the three-person in-room panel filled the frame. This was a scene change, not an explicit end/BRB/wrap card.

Screenshots are under `/workspace/galaxy-day1/shots/`:
- `2026-09-16_0003_founders-remainder7-start.png`
- `2026-09-16_0007_split-screen-founders-qa.png`
- `2026-09-16_0011_split-screen-still-live.png`
- `2026-09-16_0015_split-screen-still-live.png`
- `2026-09-16_0020-in-room-panel.png`

---
