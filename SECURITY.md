# Security Policy

## Supported Versions

Shinobi Clash is a single-file browser game distributed from the `main`
branch. Only the latest version on `main` is supported with fixes.

| Version | Supported |
| ------- | --------- |
| `main`  | ✅        |
| older commits / forks | ❌ |

## Reporting a Vulnerability

This is a client-side, static HTML/JS game with no backend, no user
accounts, and no server-side data processing — all progress is stored in the
player's own browser via `localStorage`. That said, if you find a security
issue (for example, a way to inject/execute unintended script content, or an
XSS-style vector through a text input), please report it responsibly:

1. **Do not** open a public issue for the vulnerability itself.
2. Open a [private security advisory](../../security/advisories/new) on this
   repository, or contact a maintainer directly.
3. Include steps to reproduce and the potential impact.

We'll acknowledge reports as soon as possible and credit reporters in the
fix's release notes, unless you prefer to remain anonymous.

## Scope

Out of scope: issues that only affect gameplay balance, visual glitches, or
performance — please file those as a normal [bug report](.github/ISSUE_TEMPLATE/bug_report.md) instead.
