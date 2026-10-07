# Minn Khant Thu — Portfolio

Live: https://minnkhantthuu.github.io/

Static mirror of https://minnkhantthu.up.railway.app/, built with TanStack Start and React. Includes the PerseusTV+ engineering case study, store links, and the phone-free public CV.

This repository contains generated public website files only. The source repository remains private. Country-aware availability uses a public Railway endpoint; if unavailable, the page retains its New Zealand message. No visitor-facing selector is used.

Published from the root of `master` using GitHub Pages. `.nojekyll` preserves static build assets. Both `/` and `/work/perseus/` have prerendered HTML for direct navigation.

For updates, run the private portfolio repository's `npm run build:pages`, then its `scripts/export-github-pages.mjs` with this checkout as the target. Review the generated diff before committing and pushing. This is a published snapshot, not automatic cross-repository syncing.

The previous website remains recoverable in Git history; its unused assets have been preserved.
