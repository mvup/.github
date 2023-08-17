# Universal Coordination

This repository details the basic structure of the organization as well as code administration
details for GitHub activity.

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

...

## Labels

Labels come in a few different forms:

- Category
- Dependency

The following are the labels present in the global namespace and should be used by repositories:

| Type       | Name                 |
|:----------:|:--------------------:|
| Category   | `C-bug`              |
|            | `C-cleanup`          |
|            | `C-duplicate`        |
|            | `C-enhancement`      |
|            | `C-experiment`       |
|            | `C-good-first-issue` |
|            | `C-help-wanted`      |
|            | `C-stale`            |
|            | `C-tracking-issue`   |
|            | `C-wontfix`          |
| Dependency | `D-cargo`            |
|            | `D-docker`           |
|            | `D-github-actions`   |
|            | `D-gitsubmodule`     |
|            | `D-gomod`            |
|            | `D-npm`              |

## Default Workflows

...

