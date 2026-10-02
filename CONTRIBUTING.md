# Contributing to 4 Digital Asset

Thank you for working with us. These rules apply to every repository in the
organization unless a repository has its own `CONTRIBUTING.md`.

## 1. Access

- You only have access to the repositories assigned to your team or to you.
- Two-factor authentication (2FA) is required for all members.
- Never share credentials, tokens or `.env` files — not in code, issues, PRs or chat.

## 2. Workflow (fork + pull request)

1. **Fork** the repository into your own GitHub account.
2. Create a branch from `main`:
   - `feat/short-description` — new feature
   - `fix/short-description` — bug fix
   - `docs/short-description` — documentation
   - `chore/short-description` — maintenance
3. Make small, focused commits (see section 3).
4. Keep your fork up to date with `main` before opening the PR.
5. Open a **Pull Request** against `main` of the original repository and fill in the template.
6. A maintainer reviews it. Address the comments by pushing new commits to the same branch.
7. Only maintainers merge. **Nobody pushes directly to `main`.**

## 3. Commit messages

We use [Conventional Commits](https://www.conventionalcommits.org/):

```
<type>(optional scope): <short summary in imperative mood>
```

Examples:

```
feat(auth): add password reset endpoint
fix(api): return 404 when user does not exist
docs: update setup instructions
```

Types: `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`, `ci`.

## 4. Pull requests

- One topic per PR. Small PRs get reviewed faster.
- Link the related issue (`Closes #123`).
- Describe **what** changed and **why**; add screenshots for UI changes.
- The CI checks must pass before review.
- Write so that a reviewer in another time zone understands it without a call.

## 5. Code and documentation

- Code, comments, branch names and technical docs are written in **English**.
- Update the `README.md` or `docs/` when you change behavior or setup.
- Add or update tests for the code you change.

## 6. Issues

Use the issue templates (bug report / feature request). Search existing issues first.

## 7. Security

Do **not** open public issues for security problems. See [SECURITY.md](SECURITY.md).
