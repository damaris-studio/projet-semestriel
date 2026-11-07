# Contributing

Thank you for considering a contribution to **[PROJECT NAME]**. This guide is a
starting point, replace the placeholders and commands with the ones used by
your project.

## Before you start

1. Read the [Code of Conduct](./CODE_OF_CONDUCT.md), if available.
2. Search existing issues and pull requests.
3. For substantial changes, open an issue or discussion before implementing it.
4. Never include credentials, personal data, or proprietary material.

## Development setup

```shell
# Replace these commands with the project's setup steps.
git clone https://github.com/aaimeraud/REPOSITORY.git
cd REPOSITORY
# install dependencies
# run the development command
```

Document required runtimes, environment variables, services, and platform
constraints here. Keep secrets in local environment files that are not
committed.

## Making changes

- Keep pull requests focused and easy to review.
- Prefer small, composable commits.
- Add or update tests for behavior changes.
- Update documentation and examples when the public behavior changes.
- Follow the existing formatting, naming, and error-handling conventions.
- Do not add generated files unless the repository requires them.

## Commit messages

Use [Conventional Commits](https://www.conventionalcommits.org/):

```text
<type>(<optional scope>): <imperative description>
```

Common types:

| Type       | Use for                                |
| ---------- | -------------------------------------- |
| `feat`     | A new user-facing capability           |
| `fix`      | A bug fix                              |
| `docs`     | Documentation-only changes             |
| `refactor` | Code changes without behavior changes  |
| `test`     | Adding or updating tests               |
| `build`    | Build system or dependency changes     |
| `ci`       | Continuous integration changes         |
| `chore`    | Maintenance that does not affect users |
| `perf`     | Performance improvements               |
| `revert`   | Reverting a previous commit            |

Examples:

```text
feat(api): add pagination to the resource endpoint
fix(parser): handle empty input
docs: clarify the local development setup
```

Use the same convention for pull request titles. Keep titles short, specific,
and written in the imperative mood. Add `!` after the type or scope for a
breaking change, for example `feat(api)!: change the response format`.

## Pull requests

Use the repository pull request template. A good pull request includes:

- a clear summary and motivation;
- the related issue or discussion;
- tests and validation steps;
- documentation for user-visible changes;
- migration notes for breaking changes.

Maintainers may request changes, squash commits, or adjust labels before
merging. Please keep discussions constructive and resolve review comments
explicitly.

## Reporting bugs and requesting features

Use the issue forms in [`.github/ISSUE_TEMPLATE/`](./.github/ISSUE_TEMPLATE/).
Include a minimal reproduction for bugs and explain the underlying problem for
feature requests. Report security vulnerabilities through the private channel
described in [`SECURITY.md`](./SECURITY.md), when that file exists; do not
publish exploit details in a public issue.
