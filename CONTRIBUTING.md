# Contributing

Thanks for helping out. These rules apply to every JWU NCSA repo unless the repo has its own
`CONTRIBUTING.md`.

## Before you start

- Check the open issues. If nobody has filed what you want to work on, open an issue first so an officer can
  confirm it fits the project.
- For anything larger than a small fix, say in the issue that you are working on it so work is not doubled.

## Making a change

1. Create a branch from `main`. Do not push directly to `main`.
2. Keep each pull request to one change. Small pull requests get reviewed faster.
3. Write commit messages that say what changed and why.
4. Open a pull request and fill in the template. At least one officer must approve it before it is merged.

## Secrets

Our repos are public. Never commit passwords, API tokens, tunnel tokens, SSH keys or `.env` files. Put example
values in a `.env.example` file instead. If you commit a secret by mistake, tell an officer right away: the
secret must be rotated, because deleting the commit does not remove it from forks or caches.

## CTF challenges

Never commit flags or challenge solutions to a public repo.

## Conduct

Everyone taking part must follow the [Code of Conduct](CODE_OF_CONDUCT.md).
