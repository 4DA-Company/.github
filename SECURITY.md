# Security Policy

## Reporting a vulnerability

**Do not open a public issue.** Instead, email **4digitalasset@gmail.com**
with:

- the affected repository and version/commit,
- a description of the problem and its impact,
- steps to reproduce (if possible).

We will acknowledge your report within [3 business days] and keep you informed
until it is resolved.

## Rules for contributors

- Never commit secrets (passwords, API keys, tokens, `.env` files).
- If a secret is committed by mistake, report it immediately: it must be
  revoked and rotated, deleting the commit is not enough.
- Keep dependencies up to date and act on Dependabot alerts.
