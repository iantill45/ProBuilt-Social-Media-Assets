# ProBuilt-Social-Media-Assets

**Public image host for ProBuilt social posts. This repo must stay public** — Buffer (and any
scheduler) stores only the image URL at post creation and fetches it again **at publish time**, so
every image here must remain reachable, unauthenticated, forever-ish.

Use the raw URL pattern in scheduled posts:

```
https://raw.githubusercontent.com/iantill45/ProBuilt-Social-Media-Assets/main/<file>.png
```

Rules (from the 18 Aug 2026 incident — posts scheduled with expiring Adobe presigned URLs all
failed at publish):

- Only **finished, approved** social images belong here — they're headed for public feeds anyway.
- Never delete a file that a scheduled or historical post references.
- Descriptive filenames for new work (e.g. `tms-accounting-one-1080x1350.png`); the numbered
  files (`01.png`, `s06.png`, …) are the pre-Aug-17 sync from the main repo and stay as-is.
- Masters, working files, and everything else live in the private `ProBuilt-Software` repo
  (`marketing/`); process docs in `marketing/social/WORKFLOW.md` there.
