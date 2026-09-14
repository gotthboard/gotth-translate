# Changelog

This repository records user-visible and compatibility-relevant changes here.
Released sections use Semantic Versioning; unreleased work remains under
`Unreleased` and does not imply a tag.

## Unreleased

### 2026-09-13 19:05 CDT — Adopt the MIT license

Commit: current commit; hash assigned by Git after commit

Affected files:

- `LICENSE`
- `README.md`
- `docs/distribution.md`
- `docs/CHANGELOG.md`

Explanation:

Record Danny's explicit MIT licensing decision for the owner-authored contents
of this repository. Third-party dependencies and assets retain their existing
licenses. This closes only the license-selection gate; it does not create a
release, compatibility promise, support promise, tag, or deployment.

Verification:

- standard MIT text compared with the already admitted GOTTH repositories
- stale current-state no-license statements removed from the tracked documentation
- tracked third-party and dependency boundaries inspected

Risks / non-goals:

- no runtime, API, dependency, tag, release, or deployment changes

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
