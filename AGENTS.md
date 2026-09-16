# AGENTS.md — machine nav for this repo

## Read order

1. `TIMELINE.md` — coverage + time spine  
2. `TAKEAWAYS.md` — distilled lessons (check citations)  
3. `notes/INDEX.md` → relevant `notes/*.md`  
4. `shots/INDEX.md` → open specific PNGs under `shots/`  
5. `notes/NOTES.md` only when you need the full rolling compile

Humans: start at `README.md`.

## Coverage rules (non-negotiable)

- **Never** treat TLDR material in `NOTES.md` as a primary transcript. For morning → ~3:08 PM ET, prefer `notes/backfill-morning.md` (`replay-backfill`) over TLDR sections.
- Label and respect statuses: `gap` | `tldr-only` | `live` | `replay-backfill` | `visual-only`.
- **Do not invent** audio claims or **Q&A substance** (no CC on replay; Q&A is visual-only).
- When unsure whether a claim is live vs TLDR, cite the note file and mark coverage.

## Conventions

| Topic | Rule |
|-------|------|
| Times | Prefer **ET**; PT = ET−3. Filenames often embed ET (`…_1901_…`, `…T2022ET-…`) or PT (`…-1710pt-…`). |
| `NOTES.md` | Rolling compile — long, append-only history; may duplicate remainder content. Banner points to TIMELINE. |
| Remainders | `eng-remainderN.md`, `pm-remainderN.md`, `founders-remainderN.md` — chronological capture windows after the main NOTES sections. Prefer **keeping filenames**; update indexes if renaming. |
| Shots | Many more files than `shots/INDEX.md` lists. Prefer curated index; don’t mass-rename shot files. |
| Persona | README keeps light Holmes “unwilling stenographer” tone — preserve when editing. |

## How to extend

1. Append a new `notes/*-remainderN.md` (or a dated section) for the new window.  
2. Update **`TIMELINE.md`** row(s) and **`notes/INDEX.md`**.  
3. Add 3–8 useful shots to **`shots/INDEX.md`** for that segment (don’t dump every PNG).  
4. If lessons are durable, add a bullet to **`TAKEAWAYS.md`** with a citation.  
5. Lightly refresh README coverage status if Day state changes.  
6. `git add` → commit with a clear message → `git push origin main`.

## Known gaps

| Gap | Detail |
|-----|--------|
| Morning → ~3:08 PM ET | Filled via **`replay-backfill`**: `notes/backfill-morning.md` + `shots/backfill/bf_*.png`. Slide-first; **still no audio transcript / no CC**. |
| Q&A | Visual scenes only; no readable captions → no Q&A substance. |
| Full audio transcript | HLS / signed-URL capture blocked by Auto-review; replay also has no captions. Notes are visual + teachable-point synthesis, not verbatim audio. |
| Speaker IDs | Lower-thirds often missing (esp. PM); don’t invent names beyond what’s on slides/OCR notes. |

## Safety

Public repo: never commit secrets, tokens, `.env`, private keys, or internal IPs. See README safety blurb.

## Day 2

- Broadcast: https://x.com/i/broadcasts/1PKqrNyvmYwGb
- Always capture from player **0:00**, not live join.
- Notes: `notes/day2/remainder*.md` · Shots: `shots/day2/` · Spine: `TIMELINE-day2.md`
- No CC — slide/UI-first; do not invent spoken Q&A.
