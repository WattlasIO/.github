# Contributing to Wattlas open repositories

Contributions are welcome across all public repositories under [`WattlasIO`](https://github.com/WattlasIO).

## Guidelines

1. **Verifiable public links only.** Every portal, standard, tool, or reference added to a directory or schema must point to a live, publicly accessible URL.
2. **State limits honestly.** When documenting a public portal or metric, include what it does *not* prove (for example, a regional load forecast is not site-level committed IT load; a permit application is not active construction).
3. **Keep descriptions plain and neutral.** Sentence-case headings, factual descriptions, no marketing superlatives.
4. **Run local tests before opening a PR.** Repositories with Python tests run `python3 -m unittest` in GitHub Actions on every pull request.

## Opening a pull request

1. Fork the target repository and create a short descriptive branch.
2. Keep changes focused on one topic per pull request.
3. Verify any URLs you add return HTTP 200 and use `https://`.
4. Submit the pull request with a brief note explaining what changed and why.
