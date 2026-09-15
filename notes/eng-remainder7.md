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
