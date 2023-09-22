# Contribution Policy

All code created by the MVUP Internet Corporation is Free and Open Source Software unless otherwise
noted. We welcome bug reports and patches from everyone.

One of the best ways you can contribute is to start using our tools for your own projects. This
leads to discovering bugs and helps flesh out use cases, which lead to further design iterations.
Importantly, each issue found this way comes with real world motivations, making it straightforward
to explain the reasoning behind proposals and feature requests.

You will be taken much more seriously on the issue tracker if you work on a project that uses our
tools. The issue label `C-good-first-issue` exists to help find issues that are limited in scope
and/or knowledge of project internals. Look for `C-help-wanted` for more expert issues. Note that
issues that are labelled `S-proposed` are still under consideration so discussion is welcome but
efforts to implement such a proposal have a high risk of being wasted. Check for the `S-accepted`
status and contribute to discussions around who wants to take on the responsibility of working on
implementations. For issues that are under consideration, please express your interest in the issue
tracker, providing extra insights and considerations that others have not yet expressed. The most
highly regarded argument in such a disucssion is a real world use case.

## Issue Tracker

Issues are a place to disclose bugs and discuss new features which should eventually lead to a Pull
Request. The issue tracker is not a place for general discussion and questions about how to use any
of the tools and software, which should instead be discussed in the
[Discussions Forum](https://github.com/orgs/mvup/discussions). Security-critical bugs should not be
disclosed in the public issue tracker or discussion forum. See our [Security Policy](./SECURITY.md)
for more details and how to perform responsible disclosure.

## Pull Requests

Follow the [Pull Request Template](./.github/PULL_REQUEST_TEMPLATE.md) when writing a Pull Request.
Feel free to make draft pull requests whenever you want to fix a bug or build a new feature, but
first create an issue where discussion can take place.

When reviewing a Pull Request, ensure that all required conditions are met before approving any new
changes.

## Code Owners

All our projects use a [CODEOWNERS](./CODEOWNERS) file to track the people responsible for each
component of the system. Whenever you are contributing to a component, the `CODEOWNER`s are
responsible for reviewing and approving your changes. Please follow their guidelines and
suggestions.

## Style

Each programming or markup language adheres to certain style guidelines, and our organization tries
to adhere to the principles of _maximize readability_ and _minimize diff sizes_. All formatting that
can be checked automatically during CI will be, and the provided formating programs should be used
when pushing code for final review in a Pull Request as correct style is a requirement for merge.

