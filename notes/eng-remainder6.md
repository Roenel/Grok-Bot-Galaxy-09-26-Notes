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
