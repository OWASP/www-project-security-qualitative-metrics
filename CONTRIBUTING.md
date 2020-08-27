# Contributing [![GitHub contributors](https://img.shields.io/github/contributors/owasp/github-template.svg)](https://github.com/owasp/github-template/graphs/contributors) [![Stories in Ready](https://badge.waffle.io/owasp/github-template.svg?label=ready&title=Ready)](http://waffle.io/owasp/github-template) [![JavaScript Style Guide](https://img.shields.io/badge/code%20style-standard-brightgreen.svg)](http://standardjs.com/)

[![Build Status](https://travis-ci.org/owasp/github-template.svg?branch=master)](https://travis-ci.org/owasp/github-template)
_**TODO:** Add other crucial overall status badges here. Context
specific badges should go next to their section title or into
[CONTRIBUTING.md]()._

Found a bug? Crashed the tool? Propose a new feature?

Feel free to
[create an issue](https://github.com/owasp/github-template/issues) or
[post your ideas in the chat](https://gitter.im/owasp/github-template)!
Pull requests are also highly welcome - please follow the guidelines
below to make sure your PR can be merged and doesn't break anything.

## Code & Dependency Analysis Results

_**TODO:** Optional section where you can add code quality status
badges._

## Git-Flow

_**TODO:** Optional section in case you use the Git-Flow branching
model._

This repository is maintained in a simplified
[Git-Flow](http://jeffkreeftmeijer.com/2010/why-arent-you-using-git-flow/)
fashion: All active development happens on the `develop` branch while
`master` is used to deploy stable versions and later create tagged
releases from.

### Pull Requests

Using Git-Flow means that PRs have the highest chance of getting
accepted and merged when you open them on the `develop` branch of your
fork. That allows for some post-merge changes by the team without
directly compromising the `master` branch, which is supposed to hold
always be in a release-ready state.

## Style Guide

_**TODO:** Briefly explain your expectations regarding code style._

## Testing

Pull Requests are verified to pass all of the following test stages
during the
[continuous integration build](https://travis-ci.org/owasp/github-template).
It is recommended that you run these tests on your local computer to
verify they pass before submitting a PR. New features should be accompanied by an
appropriate number of corresponding tests to verify they behave as intended.

### Unit Tests

_**TODO:** Briefly explain your expectations regarding automated unit
tests._

```
replace with your unit test command
```

### Integration Tests

_**TODO:** Briefly explain your expectations regarding automated
integration tests._

```
replace with your unit test command
```

### End-to-end Tests

_**TODO:** Briefly explain your expectations regarding automated
end-to-end tests._

```
replace with your e2e test command
```

## ...

_**TODO:** Add further sections for other topics, e.g. Localization,
Testing of release artifacts etc._
