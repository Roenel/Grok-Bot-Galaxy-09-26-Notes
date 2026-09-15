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
