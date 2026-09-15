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
