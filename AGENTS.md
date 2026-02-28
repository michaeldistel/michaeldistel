# Agent Notes

This repo is a GitHub profile. Keep changes lightweight and curated.

- README: concise profile with current projects, curated repos, and contact links.
- Curation: exclude forks unless explicitly requested.

## Repo list format

When adding a repo to `interesting-repos/*.md`, follow the existing house style:

- One line per entry: `- [Name](url) — comment. <labels>`
- Use the full repo name in the link text only when it improves clarity; otherwise use the repo project name.
- Comments: first-person allowed, no "you/your" tone, no "My take:" prefix; keep it concrete (what it is, why it matters, sharp caveats).
- Prefer repos over websites in `interesting-repos/industrial-automation.md`.

Verification

- When adding a repo or company, fetch the URL and scan the README (and licence/metadata where relevant) so the comment reflects what the project actually does.
- If GitHub is the source, prefer `gh api` / `gh repo view` to pull README, licence, stars/forks, and last push quickly.

Labels

- 🟩 [OSS]: open-source licence.
- 🟥 [No licence]: no clear licence.
- 🟧 [Maintained?]: no push in ~12 months.
- 🟦 [Popular]: >= 1,000 stars or >= 500 forks.

Maintenance rule

- If 🟧 applies, move the entry into the `## Archive` section.
- `## Archive` has a cut-off line (date); keep it consistent and keep all Archive items tagged 🟧.

## Interesting companies (optional)

If you add `interesting-companies/` later, treat it as a lightweight watchlist.

- Prefer companies shipping product (not just "labs").
- Link the primary website plus GitHub org if public.
- Keep notes short: what they do, why it matters, what to watch.

Entry template

- Company Name - https://example.com - https://github.com/example
  - What:
  - Why:
  - Watch:
