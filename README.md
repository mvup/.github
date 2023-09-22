# Universal Coordination

This repository details the basic structure of the organization as well as code administration
details for the hosted git platform (currently GitHub, but it may change in the future). The
following includes links to each relevant template, a list of labels, and default workflows that
should be installed in all repositories.

## License

All code belonging to the organization is subject to the [MIT License](./LICENSE) unless otherwise
noted. If code is forked from other projects, the appropriate licenses are attached and contributors
attributed. Contributions to this organization and its projects are always welcome.

## Templates

This repository is a template that contains the following default files that should be present in
every repository:

- [.editorconfig](./.editorconfig)
- [.github](./.github/)
- [.gitignore](./.gitignore)
- [CHANGELOG.md](./CHANGELOG.md)
- [CODEOWNERS](./CODEOWNERS)
- [CONTRIBUTING.md](./CONTRIBUTING.md)
- [LICENSE](./LICENSE)
- [README.md](./README.md)
- [SECURITY.md](./SECURITY.md)

Except for legacy repositories or the [monorepo](https://github.com/mvup/monorepo), all other
repositories should be template instances of this repository (or instances of templates of
templates). Unless otherwise noted, files should follow the syntax guidelines for the given language
linters that are specified in the repository and should follow the default
[.editorconfig](./.editorconfig) file to ensure uniformity in the codebase.

## Reviewing Guidelines

When reviewing, ensure that you follow the rules layed out in the `CONTRIBUTING.md` document in the
corresponding repository. Generally, each repository will have Issue and Pull Request templates that
must be followed for valid contribution.

## Labels

Labels come in a few different forms:

- Category (`C-`): describes the type of Issue or Pull Request
- Status (`S-`): describes the status of a new feature Issue
- Dependency (`D-`): describes Pull Requests that involve updating a certain dependency

The following are the labels present in the global namespace and should be used by all repositories:

| Type       | Name                 |
|:----------:|:--------------------:|
| Category   | `C-bug`              |
|            | `C-cleanup`          |
|            | `C-duplicate`        |
|            | `C-enhancement`      |
|            | `C-experiment`       |
|            | `C-good-first-issue` |
|            | `C-help-wanted`      |
|            | `C-proposal`         |
|            | `C-stale`            |
|            | `C-tracking-issue`   |
| Status     | `S-proposed`         |
|            | `S-accepted`         |
| Dependency | `D-cargo`            |
|            | `D-docker`           |
|            | `D-github-actions`   |
|            | `D-gitsubmodule`     |
|            | `D-gomod`            |
|            | `D-npm`              |

Repositories may use their own custom labels as well, but they should be clearly documented in the
development documentation (the `CONTRIBUTING.md` file) for that repository.

## Default Workflows

This repository includes default workflows for release automation and `CHANGELOG.md` validation as
well as workflows for the common programming languages used by repositories in this organization.

### Release Automation

Certain Pull Requests can be tagged as _Release Pull Requests_ which the release workflow can detect
causing a tag creation and publication of a release with `CHANGELOG.md` validation. These kinds of
releases only mark a point in the history of the repository, they do not automatically cause
production code to be released. Production releases are still done manually using the relevant
authentication mode for each production platform. There may be exceptions to this process, and they
are clearly documented in those cases.

