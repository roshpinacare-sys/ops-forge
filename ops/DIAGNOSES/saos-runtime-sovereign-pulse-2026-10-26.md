# אבחון — saos-runtime/sovereign-pulse

נמדד — 2026-10-26T05:49:12.337Z · ריצה 40250738909 · 2026-10-26T00:43:37Z.

## שרשרת-הצעדים

- job beat → failure; שלב כושל — Selftest gate (fail-closed — red run = public alarm, nothing broadcast)
  · Set up job
  · Freshness gate (≤1 broadcast per 5h — self-heals dropped schedules)
  · Clone the private engine tree (signer+bus on saos-cockpit)
  · Run actions/setup-node@v5
  · Install engine crypto deps
  x Selftest gate (fail-closed — red run = public alarm, nothing broadcast)
  · Pick this beat's task (read-only roster rotation, sanitized)
  · Broadcast one directive (posting role · chain-judged · thinkGate)
  · Post Run actions/setup-node@v5
  · Complete job

## שיפוט

אין ערוץ פעיל — האבחון הוסלם לערוץ-המפעילים עם הראיות; תיקון-שורש דורש החלטת-בעלות על חומר-המשמורת.