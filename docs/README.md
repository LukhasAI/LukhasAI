# GitHub Pages and wiki-source package

The `docs/` directory contains a static documentation site and Markdown wiki source for the public `LukhasAI/LukhasAI` repository.

## Publishing (manual GitHub settings prerequisite)

This PR **does not enable GitHub Pages** or deploy the site. Once the publication gate and PR review are complete and the branch is merged, the repository owner may enable Pages at **Settings → Pages → Deploy from a branch → main → /docs**. Confirm the actual published URL inside GitHub after the deploy; do not infer one from the repository name.

- `docs/index.html`: research landing page.
- `docs/assets/site.css`: self-contained theme; graphite, silver, aquamarine and midnight blue.
- `docs/wiki/index.html`: navigable documentation hub.
- `docs/wiki/*.md`: canonical Markdown source that can be mirrored into a GitHub Wiki **only after a separate wiki sync**. No GitHub Wiki API write has been performed.
- `docs/.nojekyll`: bypass Jekyll; the site is self-contained HTML/CSS.

## Verification / controls

The site has no external JavaScript, tracking code, cookies, forms, login or API requests. All outbound links target known GitHub repositories and `lukhas.ai`. It does not claim production status or OpenAI endorsement.

**Verification still required:** render at phone/desktop widths, keyboard-only links, HTML validation, link check, external Page build and independent publication claims review. Keep private engineering documents out of public Pages.

**Document owner:** LUKHΛS founder; publication candidate, 29 October 2026. No claim that GitHub Wiki pages or GitHub Pages are already live.