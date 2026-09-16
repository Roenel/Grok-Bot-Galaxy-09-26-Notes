# Grok Bot Galaxy — Day 1 morning backfill

**Replay:** [Day 1: Grok Bot Galaxy](https://x.com/i/broadcasts/1AxRnZbVpjaxl)  
**Captured window:** player `00:00` through `03:38:00` (`13,080s`), paused at the endpoint.  
**Wall-clock conversion:** using the requested ~11:30 ET stream start, ET ≈ 11:30 + player time. Thus `00:00` ≈ 11:30 ET, `00:30` ≈ 12:00 ET, `01:30` ≈ 13:00 ET, `03:00` ≈ 14:30 ET, and `03:38` ≈ 15:08 ET.  
**Method note:** video has no captions. Notes below privilege legible slide/demo text; anything inferred from the visual sequence is labelled as such. The pass is representative 5–10 minute sampling plus denser frames in the 101 demo, not an audio transcript.

## Timeline / teachable notes

### 00:00 (≈11:30 ET) — cold open and setup
- `bf_0000_cold-open.png`: opening/title material for the Galaxy stream.
- `bf_0010_intro.png` and `bf_0020_intro-discussion.png`: intro/conversation frames before the Bot 101 deck. Speaker identity and spoken claims were not captioned, so no attempt is made to over-transcribe them.
- `bf_0030_break.png`: “Grok Bot Galaxy — Be right back” interstitial; useful boundary marker before the 101 segment.

### 00:32–01:00 (≈12:02–12:30 ET) — Grok Bot 101: product framing and demo
- `bf_0032_101-framework.png`: Roman on the 101 framework. The visible slide contrasts **Ask** with **Do a task (Copilots)**; the teachable distinction is moving from asking for an answer to delegating an outcome.
- `bf_0034_intro-grokbot.png`: “Introducing Grok Bot” title/transition slide.
- `bf_0036_101-bot-demo.png`: live product demo; the interface shows bots as named, persistent conversations rather than a single generic chat. (Audio details unavailable.)
- `bf_0038_why-grokbot.png`: “Why Grok Bot” slide. Five visible value propositions:
  1. **Easy as iMessage** — bot conversations fit an existing messaging habit.
  2. **Always-on agents** — shown as `24/7`.
  3. **Uses your tools like you** — example card shows computer/tool work in Salesforce.
  4. **Finishes the work** — create bots for different jobs, give direction, let them figure it out, and set automations/routines.
  5. **Shareable workflows** — an approval-oriented workflow can be shared with others.
- Practical product thesis from the slide sequence: bots are reusable workers with scoped jobs, tool access, automation, and handoffs—not just prompt/answer windows. This is slide-derived, not an audio quote.
- `bf_0040_meet-team.png`: “Meet the team” introduces three named examples: **Data Dan**, **Slide Sonya**, and **Email Ethan**.

### 01:02–01:15 (≈12:32–12:45 ET) — 101 intake, approvals, and execution
- `bf_0042_101-intake-demo.png`: Data Dan’s first-run intake asks what the user mainly needs, with visible choices:
  - **Data & analysis** (spreadsheets, metrics, charts, digging into numbers)
  - **Research & digests** (pulling together/summarizing/keeping tabs)
  - **Workflows & routines** (recurring checks, reminders, automated follow-ups)
  - **Something else** (say it in your own words)
  The demo prompt asks for a Google Form with two coffee questions (daily cups and favorite San Francisco coffee shops), illustrating that a natural-language request can become a concrete workflow.
- `bf_0044_101-approval-demo.png`: Data Dan reports it is building the form and then hits an **Auto-review Paused This Action** checkpoint. The visible controls are **Allow once** and **Deny**, with “approval needed”; the bot can prepare the action but the user remains the gate for an external/computer action.
- `bf_0046_101-approved-run.png`: after approval, the run is marked allowed and the demo shows the Google Form action proceeding. Key pattern: plan → pause at risky/external step → human approval → continue, with an inspectable action detail.
- `bf_0050_slide-sonya.png`: Slide Sonya’s skill is shown editing a deck. The visible instructions include: select the object, open **Insert → Animation (opens Motion)**, add animation, pick the type (example uses Fly In from top), set paragraph/speed, and clean up. Skill guidance also says slide text should be clean and centered (at least ~20 pt), use the deck’s existing colors, do not deviate from the palette, and do not return a screenshot in place of the created slide. The bot can be scheduled (example: a 9 AM daily summary) and can ask for a dry run.
- `bf_0055_email-ethan.png`: Email Ethan intake offers **Work & projects**, **Everyday life stuff**, **Research & writing**, **Coding & tech**, and **Not sure yet**. Demo intent: gather coffee-cup notes, match the user’s usual voice, draft an email, and ask Data Dan for numbers; the screenshot shows the bot-to-bot handoff and an external-email-oriented “Comms Drafter” description.
- `bf_0100_101-continued.png`: Email Ethan continues a connected-service workflow: gather a “Coffee Cups Per Day” sample/Drive sheet, ask Slide Sonya for details on the Bot 101 deck, then pull the deck PDF and include it in a draft for Jason. The useful pattern is a bot coordinating with another bot and a connected service, with a user-visible action trail.
- `bf_0115_101-qr-settings.png`: Data Dan displays a QR code for a coffee-form responder link. The UI text says the link is being made public / “anyone with the link can respond”; multiple **Auto-review Paused This Action** cards show allowed-once and expired states. The side panel explicitly describes routines as recurring tasks run on a schedule. This is a strong concrete example of approval state, public-link sharing, and scheduled work.

### 01:30 (≈13:00 ET) — transition
- `bf_0130_break.png`: “Grok Bot Galaxy — Be right back.” This marks the handoff from the 101 product demo to the builders/guest portion.

### 01:40–01:50 (≈13:10–13:20 ET) — builder panel and research workflow
- `bf_0140_builder-panel.png`: on-camera builder panel with a live bot UI below and a **Team Activity — Last 60 Minutes** card. The UI shows multiple people/bots and a guided intake for work/research; this frames bots as a collaborative operating layer around a live team.
- `bf_0150_market-research.png`: the panel is paired with a **Market Research Master** bot card. Treat this as a visible example of a specialized research worker rather than a generic chat assistant.

### 02:00 (≈13:30 ET) — turning community input into buildable ideas
- `bf_0200_throwaway-ideas.png`: a message says the team is pulling actual replies to choose throwaway prototypes, “not vibe,” and clustering live threads to find real submissions. The visible summary says ~530 replies/quotes were pulled. Five idea buckets shown:
  1. **Dogfood command center** — paste/stream dashboard, e.g. livestream chat + organizer.
  2. **Real non-tech small business** — local service / paint estimates / “bots run the shop.”
  3. **Content factories** — book desk, print-on-demand, fast video.
  4. **X power tools** — follow/top fans/ranking on the API.
  5. **Too big for 3 days** — medical, “Steam killer,” hardware, robotaxi (skip for throwaways).
- The same frame proposes **LiveSignal**: paste/stream chat CSV → LLM clusters → live dashboard of top questions/bugs/feature asks, with the bot ingesting Galaxy chat and feeding the next Q. Teachable heuristic: use real submissions and a constrained timebox to select prototypes, then build a feedback loop from incoming chat.

### 02:10 (≈13:40 ET) — builder ideation / Amuse
- `bf_0210_builder-amuse.png`: on-camera builder group with an **amuse** bot in the UI. A bot asks which of several “fun”/prototype ideas to pursue and shows a selectable list. This is a concrete example of using a bot to turn a broad ideation conversation into a choice screen and an executable next step.

### 02:30 (≈14:00 ET) — Lauren’s stack / ship-small advice
- `bf_0230_lauren-stack.png`: a bot message gives a concise stack take:
  - **Spine:** Vercel + PlanetScale — keep it.
  - **App:** Next.js/TS + Drizzle once out of throwaway.
  - **Auth:** Clerk when dogfood actually needs login.
  - **Money:** Stripe Connect later (operators + platform).
  - Day 1: Grok Bot landing + Sheet waitlist (role / operator / location / pro).
  - Week 1: Next on Vercel, import PlanetScale, and only add login if it blocks dogfood.
  - Delay realtime, messaging, payments, and design system.
- Teachable product-building rule: preserve a boring, proven spine; defer infrastructure and polish until real dogfood creates the need. The frame also shows a **Prioritizer** bot and a live team chat around the recommendation.

### 02:45 (≈14:15 ET) — builder table
- `bf_0245_builder-table.png`: live table discussion with laptops and role cards/notes (including “Chief … Officer” wording visible on the table). A **Creative Director** card and a **Prioritizer** card are visible in the bot overlay, reinforcing role-specific workers coordinating around the build.

### 03:00–03:10 (≈14:30–14:40 ET) — distribution, controversy, and Codie guest segment
- `bf_0300_codie-controversy.png`: split view of the panel and a presentation slide reading **“DON’T BE SCARED OF CONTROVERSY”** (with a Contrarian/controversy-themed reference visible). Distribution lesson captured from the on-screen material: make a point of view that earns attention rather than sanding the idea down into generic content.
- `bf_0305_codie-guest.png`: remote guest video alongside the builders and bot activity panel, marking Codie’s guest/distribution conversation. Exact spoken claims are not transcribed because there are no captions.
- `bf_0310_codie-bot-ops.png`: operations dashboard visibly shows **14 Bots**, **409 Messages**, **0 Working**, **11 Active** (counts are frame-time values). Named bot roles include **Lead Capture**, **Ops**, **Founding Eng**, **dr eggbot**, **Creative Director**, and **Prioritizer**. On-screen chat includes the idea “reach number. Clarity first, then amplify.” The useful operating model is a small swarm of role-specific bots, with activity and messages observable in one control surface.

### 03:20–03:38 (≈14:50–15:08 ET) — break and stop boundary
- `bf_0320_break.png`: another “Be right back” interstitial.
- `bf_0338_endpoint.png`: final capture at player `03:38:00` shows “Grok Bot Galaxy — Be right back.” The replay tab is left paused here, before the already-covered Engineering/Founders/PM material. No Engineering deck was re-captured.

## Screenshot manifest

All files are in `/workspace/galaxy-day1/shots/backfill/`:

- `bf_0000_cold-open.png`
- `bf_0010_intro.png`
- `bf_0020_intro-discussion.png`
- `bf_0030_break.png`
- `bf_0032_101-framework.png`
- `bf_0034_intro-grokbot.png`
- `bf_0036_101-bot-demo.png`
- `bf_0038_why-grokbot.png`
- `bf_0040_meet-team.png`
- `bf_0042_101-intake-demo.png`
- `bf_0044_101-approval-demo.png`
- `bf_0046_101-approved-run.png`
- `bf_0050_slide-sonya.png`
- `bf_0055_email-ethan.png`
- `bf_0100_101-continued.png`
- `bf_0115_101-qr-settings.png`
- `bf_0130_break.png`
- `bf_0140_builder-panel.png`
- `bf_0150_market-research.png`
- `bf_0200_throwaway-ideas.png`
- `bf_0210_builder-amuse.png`
- `bf_0230_lauren-stack.png`
- `bf_0245_builder-table.png`
- `bf_0300_codie-controversy.png`
- `bf_0305_codie-guest.png`
- `bf_0310_codie-bot-ops.png`
- `bf_0320_break.png`
- `bf_0338_endpoint.png`

## Coverage / blockers

- **Covered:** cold open, Grok Bot 101 framing and demos (including intake, approvals, multi-bot handoff, scheduling, QR/public responder link), builder/research portion, community/throwaway idea selection, Lauren’s stack guidance, builder table, controversy/distribution framing, Codie guest transition, and bot-ops dashboard.
- **Stopped:** `03:38:00` / ~15:08 ET, matching the requested live-capture handoff boundary; tab remains open and paused there.
- **Blocker:** replay has no CC, so spoken details and exact speaker attribution outside visible slides are incomplete. The notes intentionally mark visual/slide evidence and avoid presenting guessed audio as fact.
