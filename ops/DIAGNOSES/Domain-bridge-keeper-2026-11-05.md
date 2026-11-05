# אבחון — Domain/bridge-keeper

נמדד — 2026-11-05T17:33:06.921Z · ריצה 42028114791 · 2026-11-05T12:33:15Z.

## שרשרת-הצעדים

- job keep → failure; שלב כושל — commit receipts (only when the beat changed truth)
  · Set up job
  · Run actions/checkout@v5
  · Run actions/setup-node@v5
  · run the keeper beat
  x commit receipts (only when the beat changed truth)
  · Post Run actions/setup-node@v5
  · Post Run actions/checkout@v5
  · Complete job

## שיפוט

אין ערוץ פעיל — האבחון הוסלם לערוץ-המפעילים עם הראיות; תיקון-שורש דורש החלטת-בעלות על חומר-המשמורת.