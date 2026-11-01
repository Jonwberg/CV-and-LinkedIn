# CV and LinkedIn

A single place to keep the source of truth for my CV and LinkedIn profile, so both stay consistent and easy to update.

## Layout

| Path | Purpose |
|------|---------|
| `cv/cv.md` | Master CV in Markdown. Export to PDF with `pandoc cv/cv.md -o cv.pdf` or any Markdown-to-PDF tool. |
| `linkedin/profile.md` | Current LinkedIn profile text, section by section (headline, About, Experience, Skills). |
| `linkedin/improvements.md` | Review checklist and proposed rewrites for the LinkedIn profile. |

## Workflow

1. Paste the current LinkedIn text into `linkedin/profile.md` (or drop a LinkedIn data export into `linkedin/export/`).
2. Review `linkedin/improvements.md`, apply the accepted rewrites on LinkedIn, and update `profile.md` to match.
3. Keep `cv/cv.md` aligned with the profile. Tailor copies per application rather than editing the master.
