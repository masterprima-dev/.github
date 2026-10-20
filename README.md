# .github

Organization-wide defaults for [Masterprima](https://masterprima.com) engineering.

- **Org profile** shown on the organization page: [`profile/README.md`](profile/README.md)
- **Community health files** (apply to every repo in the org that doesn't have its own): `CONTRIBUTING.md`, `CODE_OF_CONDUCT.md`, `SECURITY.md`, `SUPPORT.md`
- **Issue and PR templates**: [`.github/ISSUE_TEMPLATE`](.github/ISSUE_TEMPLATE), [`.github/PULL_REQUEST_TEMPLATE.md`](.github/PULL_REQUEST_TEMPLATE.md)
- **Brand assets**: [`BRANDING.md`](BRANDING.md), [`assets/`](assets)

This repo must be **public** for the org profile and defaults to take effect.

## How defaults work

GitHub falls back to the files in this repo when a repo in the org has none of its own. A repo can override any file by adding its own copy. Changes here show up across the org without touching individual repos.

See [GitHub docs on default community health files](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file).
