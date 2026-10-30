# אבחון — saos-runtime/escrow-payroll

נמדד — 2026-10-30T06:14:24.697Z · ריצה 40848623039 · 2026-10-29T09:18:38Z.

## שרשרת-הצעדים

- job canary → failure; שלב כושל — Resolve live fleet keys from the sealed GEN-2 bundle (in-run, 0600, never logged)
  · Set up job
  · Run actions/checkout@v5
  · Run actions/setup-node@v5
  · Install signer lib (house pattern)
  · Confirm friction
  · Checkout the grids home (saos-dex — engine of record)
  · Selftest gate (offline vectors — red selftest never reaches the chain)
  x Resolve live fleet keys from the sealed GEN-2 bundle (in-run, 0600, never logged)
  · Canary cycle (transfer -> approve to -> approve agent -> release; idempotent, key-gated per leg)
  · Cleanup key material
  · Commit receipts to the grids home (evidence = commit; FF-only with yield)
  · Post Run actions/setup-node@v5
  · Post Run actions/checkout@v5
  · Complete job

## שיפוט

אין ערוץ פעיל — האבחון הוסלם לערוץ-המפעילים עם הראיות; תיקון-שורש דורש החלטת-בעלות על חומר-המשמורת.