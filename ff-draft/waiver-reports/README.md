# Waiver reports — format + process

One file per week (`2026-wkN.md`). `2026-wk2.md` is the first example —
judge the format against that, not a spec written in the abstract.

## What Alex feeds in each week

Either a fresh full roster paste (like Sept 15) or just the deltas (adds/
drops since last time) for all 8 teams, whatever's easier. That updates
`rosters.md`, which is the only way to know who's actually available —
there's no live connection to the Yahoo league itself, so a stale
`rosters.md` means a stale report.

## Locked format (as of Week 2)

Two sections, in order:

1. **"Around the wire"** — a short, by-position scan of what's actually out
   there (2-4 names each for QB/RB/WR/TE), so Alex sees the market before
   it's narrowed. Explicitly flags anything already owned in the league
   (e.g. Kaelon Black turned out to be Sara's) rather than silently dropping
   it, so he can see the cross-check working.
2. **"Your moves this week"** — **1 to 3 recommendations, endpoint, not a
   quota.** Some weeks that's one strong pick, some weeks three; never pad
   to hit 3, never trim a real second option to look tidy. Each rec gets a
   little more depth than a one-liner: the actual stat line, why it beats
   what's on his bench specifically, a bid $, a competition read, and a drop
   candidate.

Plus a short **"Skipped"** line only when there's something worth explicitly
ruling out (a position he doesn't need, an injury that's someone else's
problem) — not a mandatory section.

## What the report always does

1. **Cross-checks every suggestion against `rosters.md`** — never suggest
   someone already rostered in this league; call it out when a hot name
   turns out to be taken.
2. **Targets Alex's team specifically** — reads his actual bench weaknesses,
   not a generic top-10 list.
3. **FAAB $ sized to the $100 season pool**, not standard 100s-scale FAAB
   advice — always convert. Adjust for known competition: Joe, Hai, and Kyle
   are the aggressive waiver managers in this league (see `league-notes.md`),
   so a name they'd also want gets bid up; a Zach/Steph-caliber target can
   go cheap.
4. **Names a drop candidate** whenever recommending an add — Yahoo requires
   one and it should already be reasoned about, not left for Alex to figure
   out.

## Still open

- Delivery mechanism (email vs. in-chat) — deliberately not built yet, per
  Alex: nail the report content first.
- OJ's roster is missing from `rosters.md` — get it before it matters for a
  suggestion overlap.
- No real FAAB bid history for this league yet — bid sizes are modeled off
  public FAAB guides (roughly 20%+ of remaining budget for a clear-role
  breakout early in a full season, single digits for a speculative dart).
  Once Alex reports what things actually cost to win in this room, recalibrate
  to that instead of the generic guide — same principle as the draft values.
