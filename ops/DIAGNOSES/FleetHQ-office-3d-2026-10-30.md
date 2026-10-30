# אבחון — FleetHQ/office-3d

נמדד — 2026-10-30T18:44:25.400Z · ריצה 41064482999 · 2026-10-30T13:35:13Z.

## שרשרת-הצעדים

- job bake-and-publish → failure; שלב כושל — Bake the 3D room (vite build + serve :3210 + headless WebGL frames)
  · Set up job
  · Checkout (full history — branch worktree + rebase needed)
  · Setup Bun
  · Install (frozen lockfile — puppeteer + vite for the room build)
  x Bake the 3D room (vite build + serve :3210 + headless WebGL frames)
  · Fleet digest (read-only GitHub API + public raw docs)
  · Render office window page (embeds the baked frames + their real stamps)
  · Publish dist + 3D frames to office-pages (rebase-first, no force-push)
  · Commit honest receipts (latest.json pointer + log) back to main
  · Honest job summary
  · Post Setup Bun
  · Post Checkout (full history — branch worktree + rebase needed)
  · Complete job
- job deploy-room → skipped; שלב כושל — אין

## שיפוט

אין ערוץ פעיל — האבחון הוסלם לערוץ-המפעילים עם הראיות; תיקון-שורש דורש החלטת-בעלות על חומר-המשמורת.