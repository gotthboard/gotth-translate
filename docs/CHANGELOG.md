# Changelog

This repository records user-visible and compatibility-relevant changes here.
Released sections use Semantic Versioning; unreleased work remains under
`Unreleased` and does not imply a tag.

## Unreleased

### 2026-09-06 00:54 CDT — Establish distribution and security-reporting policy

Commit: current commit; hash assigned by Git after commit

Affected files:

- `README.md`
- `CONTRIBUTING.md`
- `SECURITY.md`
- `docs/distribution.md`
- `docs/CHANGELOG.md`

Explanation:

Document Forgejo as the canonical development source, GitHub as the public
distribution and bug-reporting surface, and GitHub private security advisories
as the confidential vulnerability-reporting channel.

Verification:

- documentation whitespace and policy-link scans
- direct GitHub API confirmation that private vulnerability reporting is enabled

Risks / non-goals:

- no implementation, public API, tag, release, or deployment was added
