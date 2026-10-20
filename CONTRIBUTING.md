# Contributing

Thanks for helping out. This is the default guide for all Masterprima repositories. A repo's own `CONTRIBUTING.md` takes precedence.

## Workflow

1. Check existing issues before opening a new one.
2. Branch off the default branch. Keep one change per branch.
3. Make the change, with tests where the repo has them.
4. Run the repo's lint and test commands locally before pushing.
5. Open a pull request and fill in the template.

## Branches and commits

- Branch names: `type/short-description`, e.g. `feat/login-sso`, `fix/payment-timeout`.
- Commit messages in imperative mood, short subject (≤72 chars): `Fix timeout on payment callback`.
- Prefer [Conventional Commits](https://www.conventionalcommits.org) prefixes (`feat:`, `fix:`, `docs:`, `chore:`) if the repo already uses them.

## Pull requests

- Keep them small and focused. Large PRs get slower reviews.
- Describe **what** changed and **why**. Link the issue.
- Add screenshots for UI changes.
- Never commit secrets, credentials, `.env` files, or personal data of students or staff.

## Reporting problems

- Bugs and feature requests: open an issue using the templates.
- Security issues: do **not** open a public issue. See [SECURITY.md](SECURITY.md).
- Questions: see [SUPPORT.md](SUPPORT.md).

By contributing you agree to follow the [Code of Conduct](CODE_OF_CONDUCT.md).
