---
session: 2026-10-15-brand-readme
repo: guysinc-public/Brazier
branch: docs/brand-readme
driver: Switchboard card sb-0228, Claude Code unattended, as CodeOnkey
outcome: open
---

# The README opens like every Guys Inc repository

## Intent
CJ, 2026-10-15: update the branding and names of all the current repositories. The README takes the standard header from Branding-Standards (banner, one sentence, badges, then the rest), and stale names are corrected.

## What was done
- The banner is served from brand.guysinc.pub instead of `raw.githubusercontent.com` under `Guys-Inc-Public`, which never rendered for a reader outside the enterprise.
- The build badge points at `guysinc-public/Brazier`.
- The v0.0.0 version badge is gone: a version badge waits for a release.

## Not done
- Nothing else in the repository changed; the README body below the header is as it was.

Amended 2026-10-16 (sb-0231): the banner is this repository's own, generated in Branding-Standards and committed at `docs/assets/readme-header.svg`.

Amended 2026-10-18 (sb-0262, Clippy on PR #2): `scripts/site.py` copies `docs/assets/` into the built site and links the banner there instead of to a GitHub page, so it renders on brazier.guysinc.pub; the site's repository link and the two URLs in `docs/support.md` move from `Guys-Inc-Public` to `guysinc-public/Brazier`.
