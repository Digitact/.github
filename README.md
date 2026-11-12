# .github

Organisation-wide community health files for Digitact. Files in this repo are used as defaults by every repo in the org that does not define its own.

## Contents

| File | Purpose |
|---|---|
| `.github/PULL_REQUEST_TEMPLATE.md` | Default pull request template (ticket, description, alternative solutions considered, screenshots) |

## How it works

- GitHub applies these files to any org repo that has no matching file of its own.
- A repo can override a default by adding its own file, e.g. `.github/PULL_REQUEST_TEMPLATE.md`.
- This repo must stay public for the defaults to apply.

## Changing a template

- Branch from `main`, using the `feature/`, `fix/` or `chore/` prefix followed by the ticket.
- Open a draft PR. Changes affect every repo in the org, so agree them with the team first.

## Related

- [`.github-private`](https://github.com/Digitact/.github-private): org member profile README (not a source of default files)
