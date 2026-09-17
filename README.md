# clearcut-assets

Public build assets for **clearcutauto.ca**.

The site builder fetches these at build time and verifies each one
against a pinned SHA-256 before using it. If a file's bytes change,
the build fails loudly rather than deploying something unexpected.

## Rules

- **Public repo.** Anything committed here is world-readable, permanently.
- **Client-facing downloads only** — material already published on the site.
- **Never commit:** Client Service Agreement, Schedule A, Reserve Package,
  client data, API keys, or anything sent via DocuSign.
- Changing a file here means the pinned hash in the builder must be
  updated in the same session, or the next build fails.

## Contents

| File | Used by |
|---|---|
| `before-you-sign-checklist.pdf` | `/downloads/before-you-sign-checklist.pdf` on the live site |
