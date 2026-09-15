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
