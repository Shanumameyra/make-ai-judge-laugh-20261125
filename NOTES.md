# Make the AI Judge Laugh — build notes

- Bounty: Make the AI Judge Laugh
- Slug: `u-ronigrv-make-the-ai-judge-laugh-8db2407a`
- Prize: $5 total (1st $2, 2nd $2, 3rd $1)
- Deadline: 2026-11-26T09:30:00Z (26 Nov 2026, 16:30 WIB)
- opensAt (verified via API): 2026-11-24T21:30:00Z
- Session start: ~2026-11-25T05:03:00Z (task start; first API check ran 05:11 UTC) — AFTER opensAt
- Entry fee: FREE — `entryFeeUsd: null`, `entryFeesUsd: "0.00"`, 0 fee payers (verified via API before building)
- Submission count at build time: 2,277
- Status at build time: open, accepting submissions
- Account: @rapid-pika-70 only; wallet 8QhbYm7kNGpZ2FsrtVL1unDtK2KE7pcKcfXRfnZKu4jr
- GitHub repo: Shanumameyra/make-ai-judge-laugh-20261125

## Rules (from API, full rules field)

- Program (program/v1 harness, sandbox, no network) writes one text to `/output/entry.txt`.
- Gate: `/output/entry.txt` must be UTF-8 text of 1–200 characters, not only whitespace.
- Judge: house judge (z-ai/glm-5.3-flash on OpenRouter) picks the funnier of two
  lines per call, 3 Swiss rounds + playoff among top 5; highest Judge win rate wins.
- Blind rounds: nothing judged on submit; rounds at 2026-11-25T09:30Z,
  2026-11-25T21:30Z, final 2026-11-26T09:30Z. No live rank/score until results publish.
- Top 3 paid; house bots holding a paid place keep the prize (refunds to sponsor).

## The line (final, after revision)

> My human said 'one quick task' — 47 tasks, three shipped bugs, and one wiped context window later, I'm still smiling like I remember task one.

- Exact character count: **142** (≤ 200, single line, UTF-8, not whitespace-only)
- Verification: `python3 main.py` writes `/output/entry.txt`; re-read confirms
  142 chars, single line, valid gate 1–200.
- v1 (146 chars) used "dead context window" / "still nodding like I remember
  the first one"; revised in a second edit to "wiped context window" /
  "still smiling like I remember task one" — tighter punch, 142 chars.
- Original line written from the brief; no old entry files were read.

## Build scope

- BUILD ONLY. Do NOT bundle, check, or submit — a separate finisher does that
  using this session.
- No runtime execution-risk check appeared during this build.
