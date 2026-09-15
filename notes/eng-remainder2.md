# Engineering remainder 2 — Lingxi Li / FlyLo workflow follow-on

**Source:** X broadcast `1AxRnZbVpjaxl` (same open tab). The observed window began around video `4:22:53` and ran past `4:39:00` (about 16 minutes; the live duration kept extending). The player remained playing and unmuted.

## New material after the workflow-rules section

### 1) Workflow enforcement became concrete in the FlyLo demo
- The projected FlyLo/Slack-like workspace showed the rules being assigned to named bots and routines, rather than left as prose:
  - Steve was renamed/briefed as the **Nightly Audit Engineer**. The bot was told to stay quiet until a tree is named/armed, use one cleanup cloud agent per area, board when a PR opens, never merge, and never touch another engineer’s PR.
  - The nightly pass is **research first** across four front-end trees—`booking-frontend`, `web`, `crew-app`, and `factory`—with cleanup agents only after the research aggregates. Four research-only CQ-audit items were shown as done, each with an “Open in Web” action.
  - A demo check for a recent 5xx was explicitly gated: use Operations Control/live status and capture evidence; do not touch it early. A sign-in page was shown as “Continue—no credentials” rather than entering credentials.
  - Head-of-Ops ownership was made explicit: Jenny alone owns playbook updates; engineer bots do not edit it. Ops consolidates changes into one source of truth.
- The FlyLo homepage demo (“The quiet way to fly”) was used as the test surface; a live presenter inset showed Lingxi narrating the workflow.

### 2) P0 incident: previously booked-flight lookup
- A user reported that a previously booked flight could not be checked. The bot boarded it as **“Trip lookup broken”**, treated it as **P0 / In-Ready**, and checked `flylo-air.com` and `book.flylo-air.com` in parallel.
- The failure was confirmed: `/trips` is a stub (“lookup lands in a later iteration”) while navigation still points users there. A P0 fix agent was started and put on a five-minute watch (shown as “Watching 1/3” at first; the fleet board later showed the trip-lookup row as **Working**, PR **#76**).
- The demonstrated operating policy was: board first, run a cloud agent, watch it, and only proceed with cleanup/PR handling when evidence and the board state justify it.

### 3) Five-minute interrupt watch and playbook fan-out
- A new P0 routine was requested: check cloud agents every five minutes for off-track behavior such as a long `sleep 300`, stalling, excessive conservatism, or drifting from the goal; interrupt and nudge immediately when found.
- The complete pattern was sent to Jenny: board-first + cloud agent + five-minute interrupt watch (sleep/conservative/stall) + set/delete at Watching 1/3. Jenny baked it into the playbook as the **P0 / urgent path**.
- Jenny was then asked to announce the P0 playbook to every engineer bot. The screen reported the announcement was sent to the engineer bots and pointed them at the P0/urgent path; the Chief-of-Staff Bot was explicitly skipped.
- Live statuses shown afterward:
  - Factory dead-API cleanup: Steve, PR **#37**, **Watching 1/3**.
  - Crew-app cleanup agent: already running; board it when its PR opens.
  - Trust polish: PR **#72**, **Watching 3/3**, next CLEAN pick and ready for review.

### 4) Fleet board / source of truth demo
- A Notion-like **“FlyLo Engineering Fleet”** board appeared. The subtitle described it as an empty text board for the Engineer Bot with a schema where agents write **Task name, Owner, Stage, PRs, Cloud agent, Last comment**.
- The visible rows were Factory dead API cleanup (Steve, #37, Watching 1/3), Trip lookup broken (Craig, #76, Working), and Trust polish (Lingxi’s Engineer Bot, #72, Watching 3/3). This makes board state, ownership, PR link, and stage the operational handoff surface.

### 5) Engineering summary slide (“What we learned”)
- **Treat them like interns:** ask Grok Bots to do homework, study new areas, and learn from other engineers; simply chat—no skill invocation or long prompts required.
- **Think one level further:** if a bot repeatedly needs a human for the same task, automate the flow instead of manually unblocking it each time.
- **Start with a feedback loop:** design for the bot to observe and receive signals about the work being done.

## Handoff status
- No explicit “builders return,” BRB, PM-session announcement, Kevin Niparko (~2:30 PT), or Q&A handoff was visible during this capture.
- At the end of the observed window (around video `4:39:00`), Lingxi was still presenting the Engineering “What we learned” slide with the stream still live/playing. **Engineering remained on-screen for the entire remainder window; no transition out of Engineering was observed.**

## Screenshots saved
- `shots/eng_remainder2_flylo_homepage.png`
- `shots/eng_remainder2_workflow_demo_speaker.png`
- `shots/eng_remainder2_head_of_ops_playbook.png`
- `shots/eng_remainder2_jenny_head_ops_assignment.png`
- `shots/eng_remainder2_research_only_audits.png`
- `shots/eng_remainder2_live_audit_and_p0.png`
- `shots/eng_remainder2_p0_trip_lookup_continued.png`
- `shots/eng_remainder2_p0_five_minute_watch.png`
- `shots/eng_remainder2_p0_interrupt_watch_jenny.png`
- `shots/eng_remainder2_p0_fanout_and_agents.png`
- `shots/eng_remainder2_flylo_engineering_fleet_table.png`
- `shots/eng_remainder2_what_we_learned.png`
