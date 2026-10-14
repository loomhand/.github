# Contributing

Thanks for your interest in loomhand. These guidelines apply to every repository in the organization unless the repository has its own `CONTRIBUTING.md`.

## Before you start

- For bugs, open an issue with the bug report template.
- For larger changes — new features, new dependencies, changes to a public interface or a wire contract — open an issue first and agree on the approach before you write code.
- Small fixes (typos, obvious bugs, documentation) can go straight to a pull request.

## Making changes

- One logical change per commit. Keep refactors separate from behavior changes.
- Commit messages use a one-line summary in the form `component: what changed`, for example `agent: retry the tool call after a transport reset`. Add a body only to explain why.
- Tests and lint must pass before review. Add or update tests for the behavior you change.
- Follow the existing style of the code you touch.
- Write code, comments, commit messages, and documentation in English.

## Pull requests

- Fill in the pull request template: what changed, why, and how you tested it.
- Keep pull requests focused; split unrelated changes into separate pull requests.
- Rebase on the latest `main` instead of merging it into your branch.

## Security issues

Do not report security vulnerabilities in public issues. See [SECURITY.md](SECURITY.md).
