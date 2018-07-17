# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased][]

### Build

- Move font awesome react to dev dependency, it is not directly included but is built into the bundle (#31)
- Include build in release (#31)

### Chore

- Update font awesome and font awesome react (#31)
- Remove unused files (#31)

## [0.1.1][] - 2018-07-16

### Refactor

- Move `react-scripts` to `devDependencies` reducing dependencies included in production install (#30)

### Docs

- Add changelog (#27)
- Add license (#25)
- Add html flag to example in readme (#28)

### Chore

- Configure continuous integration (#22)
- Configure renovate dependency manager (#21)

## [0.1.0][] - 2018-07-10

### Added

- Add react app template
- Wrap as web component
- Leverage Open ID Connect (OIDC) for authorization
- Support loading templates
- Support loading previous answers
- Support form forwarding

### Docs

- Create README
- Add Committers

[unreleased]: https://github.com/uPortal-contrib/form-builder/compare/v0.1.1...HEAD
[0.1.1]: https://github.com/uPortal-contrib/form-builder/compare/v0.1.0...v0.1.1
[0.1.0]: https://github.com/uPortal-contrib/form-builder/compare/bc446238d1735b424bd2a004d9b737c380592b2e...v0.1.0