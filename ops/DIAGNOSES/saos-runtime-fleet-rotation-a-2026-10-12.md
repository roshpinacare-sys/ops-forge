# אבחון — saos-runtime/fleet-rotation-a

נמדד — 2026-10-12T23:49:44.351Z · ריצה 38311269195 · 2026-10-12T21:32:28Z.

## שרשרת-הצעדים

- job rotate → failure; שלב כושל — Verdict law (green only with real rotated accounts and custody)
  · Set up job
  · Run actions/checkout@v4
  · Checkout steem main (custody branch — vault of record) + engine overlay (saos-cockpit)
  · Run actions/setup-node@v4
  · Install deps (pinned)
  · Preflight + selftest (zero network)
  · Match (open vault archives env-only, chain-judge, 0600 files)
  · Rotate phase A (broadcast, verify, incremental custody)
  · Seal ROT2 archive + meta v4 + push steem (push verified, false-OK law)
  · Public receipt (fingerprints only)
  · Commit receipt to saos-runtime (push verified)
  x Verdict law (green only with real rotated accounts and custody)
  · Post Run actions/setup-node@v4
  · Post Run actions/checkout@v4
  · Complete job

## קבלת-הרוטציה (נמדדה)

- steem:cashmachine — ROTATED-VERIFIED — custodyError
- steem:haran — ROTATED-VERIFIED — custodyError
- steem:israelnews — ROTATED-VERIFIED — custodyError
- steem:lsa — ROTATED-VERIFIED — custodyError
- steem:macrame — ROTATED-VERIFIED — custodyError
- steem:siq — ROTATED-VERIFIED — custodyError
- steem:tov — ROTATED-VERIFIED — custodyError
- steem:wic — ROTATED-VERIFIED — custodyError
- steem:wog — ROTATED-VERIFIED — custodyError
- steem:woq — ROTATED-VERIFIED — custodyError
- steem:hcsoldier4 — ROTATED-VERIFIED — custodyError
- steem:hcsoldier5 — ROTATED-VERIFIED — custodyError
- steem:hcsoldier6 — ROTATED-VERIFIED — custodyError
- hive:israelnews — ROTATED-VERIFIED — custodyError
- hive:lsa — ROTATED-VERIFIED — custodyError
- hive:siq — ROTATED-VERIFIED — custodyError
- hive:wic — FAIL-BROADCAST — fetch failed
- hive:wog — ROTATED-VERIFIED — custodyError
- hive:woq — ROTATED-VERIFIED — custodyError

## שיפוט

אין ערוץ פעיל — האבחון הוסלם לערוץ-המפעילים עם הראיות; תיקון-שורש דורש החלטת-בעלות על חומר-המשמורת.