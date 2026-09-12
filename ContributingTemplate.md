# Contributing Guide Template

Use this template as a starting point for a project `CONTRIBUTING.md` file.

Replace bracketed text, remove sections that do not apply and add project-specific setup, testing and review instructions before publishing.

## Welcome

Thank you for taking the time to contribute to [project name].

This guide explains how to get started, open issues, submit pull requests and work with maintainers.

Please also read:
- [README](README.md)
- [Code of Conduct](CODE_OF_CONDUCT.md)
- [Security policy](SECURITY.md), if available
- [License](LICENSE)

## Project Overview

[Briefly describe what the project does, who it serves and where new contributors should start.]

Useful links:
- Documentation:
- Issue tracker:
- Roadmap or project board:
- Community chat or forum:
- Maintainer contact:

## Ways To Contribute

Contributions can take many forms. Useful contributions include:

- code changes;
- bug reports;
- feature requests;
- tests and quality assurance;
- documentation;
- examples and tutorials;
- design or user experience improvements;
- issue triage;
- community support;
- translations;
- release testing.

| Recommended issue labels |
| --- |
| We recommend using clear issue labels so contributors can find approachable work more easily. Useful labels include `good first issue`, `help wanted`, `documentation`, `bug` and `testing`. |

## Before You Start

Before opening a pull request:

1. Read the project `README`.
2. Search existing issues and pull requests.
3. For larger changes, open an issue or discussion first so maintainers can confirm the direction.
4. Check whether the project has a roadmap, project board or milestone plan.
5. Make sure your contribution is compatible with the project license.

## Development Setup

Project requirements:
- language/runtime:
- package manager:
- supported operating systems:
- required services:
- environment variables:

Setup commands:

```sh
# install dependencies

# run tests

# run locally
```

## Issues

### Open A New Issue

If you found a bug or have a feature request, search existing issues first.

When opening a new issue, include:

- a clear title;
- what you expected to happen;
- what actually happened;
- steps to reproduce, if applicable;
- logs, screenshots or links where useful;
- version, commit or environment details;
- whether you are willing to help test or fix it.

### Work On An Existing Issue

If you want to work on an open issue, comment on the issue before starting.

Some projects do not formally assign issues. If that is true for this project, say so here:

> As a general rule, issues are not assigned. If you want to work on one, comment with your plan and open a pull request when ready.

## Pull Requests

When your changes are ready, open a pull request.

Before submitting:

- keep the pull request focused on one change or topic;
- link the related issue, if any;
- describe what changed and why;
- include tests or explain why tests are not needed;
- update documentation when behavior changes;
- allow maintainer edits on your branch when possible;
- make sure CI passes.

Pull request description template:

```md
## Summary

-

## Testing

-

## Notes For Reviewers

-
```

## Commit Style

| Recommended commit style |
| --- |
| We recommend using Conventional Commits so commit history is easier to scan and changelogs are easier to generate. |

This project uses [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) unless the repository states otherwise.

Examples:

```text
fix: handle empty response from indexer
feat: add preview network config
docs: clarify local setup
test: add regression test for parser
chore: update dependencies
```

## Developer Certificate Of Origin

| Recommended contribution signoff |
| --- |
| We recommend using the Developer Certificate of Origin so projects have a clear record that contributors have the right to submit their work. |

This project may require the [Developer Certificate of Origin](https://developercertificate.org/).

If DCO is required, all commits must be signed off. This certifies that you have the right to submit the work and that it is your own work or properly licensed.

Sign off commits with:

```sh
git commit -s
```

or:

```sh
git commit --signoff
```

If the project uses automated DCO checks, pull requests cannot be merged until all commits are signed off.

## Code Review

Maintainers review pull requests for correctness, maintainability, project fit, tests, documentation and license compatibility.

Reviewers may ask questions or request changes before a pull request can be merged.

If the repository has a `CODEOWNERS` file, it identifies people or teams who should review certain areas of the project.

## Tests And Quality

Before requesting review, run the relevant checks:

```sh
# format

# lint

# test

# build
```

If a test cannot be run locally, explain why in the pull request.

## Documentation

Update documentation when your change affects:

- setup;
- configuration;
- public APIs;
- command-line behavior;
- examples;
- troubleshooting;
- security or operational assumptions.

## Security Reports

Do not open a public issue for sensitive vulnerabilities.

Use the project's security reporting process:

- Security policy:
- Security contact:
- Private advisory link:

If no security policy exists yet, maintainers should add one before the project is widely used.

## Licensing

Contributions must be compatible with the project license and will be licensed under the same terms unless the project states otherwise.

Project license:

If the contribution includes third-party code, generated code, media, data or documentation, disclose the source and license.

## Maintainer Notes

Project maintainers should fill in or remove this section before publishing.

**Maintainers / reviewers:**
-

**Merge requirements:**
- required approvals:
- required CI checks:
- required DCO/signoff:
- squash, merge commit or rebase:

**Release process:**

**Where contributors can ask for help:**

## Contributor Checklist

- [ ] I searched existing issues and pull requests.
- [ ] I linked the related issue or explained why there is none.
- [ ] I kept the change focused.
- [ ] I added or updated tests where appropriate.
- [ ] I updated documentation where appropriate.
- [ ] I ran the relevant checks.
- [ ] My commits are signed off if DCO is required.
- [ ] My contribution is compatible with the project license.
