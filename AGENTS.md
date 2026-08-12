# Mestryx-dev — GitHub profile README repo

Special repository: `<username>/<username>` renders as the GitHub profile page banner. This repo is intentionally tiny — its only content is the profile README and its assets.

## Conventions

- `README.md` is bilingual (FR section first, then EN) — keep the existing structure and anchors (`#fr` / `#en`).
- Visible copy: no AI-isms (see `copy-ai-audit` skill): no "preuve", "seamless", "de bout en bout", em-dashes in prose. Keep the tone short, concrete, human, pro.
- Banner: `assets/banner-infra.svg` (dark slate `#020617` + teal `#22d3ee`, hub-and-spoke network motif — matches the portfolio palette).
- Badges: shields.io; verify logo slugs against cdn.simpleicons.org before adding a new one (linkedin/playwright currently unavailable — use text-only badges for those).
- Profile data (bio, links) mirrors `portfolio` repo content: `docs/Projet/01-contenu.md` is the copy source of truth.

## Build / test

No build. Validation: render at `https://github.com/Mestryx-dev`, grep README for banned AI tells, spot-check badge SVG responses (icon embedded = `viewBox="0 0 24 24"` in the base64 data URI).

## Do-not-touch

- Do not delete or rename this repo (it is the profile repo).
- Do not add code to this repo — README + assets only.
