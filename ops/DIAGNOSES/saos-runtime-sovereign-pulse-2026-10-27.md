# אבחון — saos-runtime/sovereign-pulse

נמדד — 2026-10-27T08:13:48.485Z · ריצה 40460146389 · 2026-10-27T06:16:44Z.

## שרשרת-הצעדים

- job beat → failure; שלב כושל — Broadcast one directive (posting role · chain-judged · thinkGate)
  · Set up job
  · Freshness gate (≤1 broadcast per 5h — self-heals dropped schedules)
  · Clone the private engine tree (signer+bus on saos-cockpit)
  · Run actions/setup-node@v5
  · Install engine crypto deps
  · Selftest gate (fail-closed — red run = public alarm, nothing broadcast)
  · Pick this beat's task (read-only roster rotation, sanitized)
  x Broadcast one directive (posting role · chain-judged · thinkGate)
  · Post Run actions/setup-node@v5
  · Complete job

## שיפוט

אין ערוץ פעיל — האבחון הוסלם לערוץ-המפעילים עם הראיות; תיקון-שורש דורש החלטת-בעלות על חומר-המשמורת.