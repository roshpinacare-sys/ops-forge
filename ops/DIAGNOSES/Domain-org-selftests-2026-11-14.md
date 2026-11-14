# אבחון — Domain/org-selftests

נמדד — 2026-11-14T08:40:20.914Z · ריצה 43013921166 · 2026-11-11T11:40:44Z.

## שרשרת-הצעדים

- job selftest (saos-control-center, bun-tsc) → failure; שלב כושל — Run bun-tsc on saos-control-center
  · Set up job
  · Checkout saos-control-center
  · Python 3.11
  · Bun
  x Run bun-tsc on saos-control-center
  · Post Bun
  · Post Checkout saos-control-center
  · Complete job
- job selftest (saos-jummper, python-signingcontract) → success; שלב כושל — אין
  · Set up job
  · Checkout saos-jummper
  · Python 3.11
  · Bun
  · Run python-signingcontract on saos-jummper
  · Post Python 3.11
  · Post Checkout saos-jummper
  · Complete job
- job selftest (roshpina, bun-kernel-smoke) → success; שלב כושל — אין
  · Set up job
  · Checkout roshpina
  · Python 3.11
  · Bun
  · Run bun-kernel-smoke on roshpina
  · Post Bun
  · Post Checkout roshpina
  · Complete job
- job selftest (saos-sovereign-foundry, bun-tsc) → success; שלב כושל — אין
  · Set up job
  · Checkout saos-sovereign-foundry
  · Python 3.11
  · Bun
  · Run bun-tsc on saos-sovereign-foundry
  · Post Bun
  · Post Checkout saos-sovereign-foundry
  · Complete job
- job selftest (saos-sovereign-platform, bun-tsc) → success; שלב כושל — אין
  · Set up job
  · Checkout saos-sovereign-platform
  · Python 3.11
  · Bun
  · Run bun-tsc on saos-sovereign-platform
  · Post Bun
  · Post Checkout saos-sovereign-platform
  · Complete job
- job selftest (saos-dex, bun-typecheck) → success; שלב כושל — אין
  · Set up job
  · Checkout saos-dex
  · Python 3.11
  · Bun
  · Run bun-typecheck on saos-dex
  · Post Bun
  · Post Checkout saos-dex
  · Complete job

## שיפוט

אין ערוץ פעיל — האבחון הוסלם לערוץ-המפעילים עם הראיות; תיקון-שורש דורש החלטת-בעלות על חומר-המשמורת.