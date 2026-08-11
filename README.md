# polygon-badges

CI status badges for [`rozklad/polygon`](https://github.com/rozklad/polygon).

The SVGs here are written by CI over the GitHub Contents API — CircleCI's
`build` job publishes `unit`, `feature`, `arch`, `browser` and `coverage`,
GitHub Actions' `static-analysis` workflow publishes `phpstan` and `phpcs`.
They live in their own repository so badge updates never land in polygon's
own history.

Renderer: `scripts/ci/publish-badges.mjs` in polygon.

Do not edit by hand — the next pipeline overwrites it.
