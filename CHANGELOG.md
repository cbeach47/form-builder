# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased][]

## [1.3.2][] - 2019-06-21

### Fix

- Pin react json schema form to version 1.2.1 (#68).

## [1.3.1][] - 2019-06-20

### Fix

- Ensure IE and Edge are included in babel `browserslist` (#67)

### Chore

- update dependencies (#62)


## [1.3.0][] - 2019-05-21

### Feature

* add `styles` option for custom form styling 

### Chore

* Update dependencies (#52, #61)

## [1.2.1][] - 2018-10-29

### Fix

- Include random number as query param to prevent Safari from caching unexpectedly (#60).

## [1.2.0][] - 2018-10-23

### Feature

- Support custom validation messages (#58).

```js
{
  "example": {
    "type": "string",
    "pattern": "^[A-Z]{3}$",
    "messages": {
      "pattern": "Must be three upper case letters"
    }
  }
}
```

## [1.1.2][] - 2018-10-10

### Fix

- Add `safeRenderCompletion` to support rendering on Firefox (#56).
- Set icon size directly on font awesome icon (#57).

## [1.1.1][] - 2018-10-10

### Fix

- Remove embedded polyfills the can conflict with other polyfills (#55).

## [1.1.0][] - 2018-10-09

### Feature

- Support web component spec version 1 (#50).
- Don't show submit button when no input is requested (#51).

## [1.0.3][] - 2018-09-21

### Fix

- Form builder iterator now loops through data correctly (#49)

## [1.0.2][] - 2018-09-20

### Fix

- Correctly pass version number into the JSON Schema Form builder

## [1.0.1][] - 2018-09-11

### Fix

- allow form builder to be run in Internet Explorer 11 (#44).

## [1.0.0][] - 2018-09-07

### Feature

- display success messages after form submission (#42)

## [0.2.5][] - 2018-09-07

### Fix

- Use state instead of prop for mutable context (#43).

## [0.2.4][] - 2018-08-07

### Fix

- 0.2.3 release lost files during upload, this is a re-release of 0.2.3 with all the expected files.

## [0.2.3][] - 2018-08-07

### Fix

- prevent unexpected page scrolls

## [0.2.2][] - 2018-08-06

### Fix

- Keep form values when validation fails (#37).

## [0.2.1][] - 2018-08-01

### Fix

- Hide validation errors when issues have been resolved (#36).

### Build

- Automatically generate web component during `npm publish` (#35).

### Docs

- NPM, Maven Central and Travis CI status badges added to _README.md_

## [0.2.0][] - 2018-07-30

### Feature

- Show validation messages sent back from server (#33).

### Fix

- Add web component polyfill for Firefox and IE (#34).
- Ensure `error` is defined before reading error messages (#34).

### Build

- Move font awesome react to dev dependency, it is not directly included but is built into the bundle (#31)
- Include build in release (#31)

### Chore

- Update font awesome and font awesome react (#31).
- Remove unused files (#31).
- Reactive elements updated to version 0.10.0 (#32).

## [0.1.2][] - 2018-07-17

### Chore

- Update font awesome and font awesome react (#31).
- Remove unused files (#31).

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

[unreleased]: https://github.com/uPortal-contrib/form-builder/compare/v1.3.2...HEAD
[1.3.2]: https://github.com/uPortal-contrib/form-builder/compare/v1.3.1...v1.3.2
[1.3.1]: https://github.com/uPortal-contrib/form-builder/compare/v1.3.0...v1.3.1
[1.3.0]: https://github.com/uPortal-contrib/form-builder/compare/v1.2.1...v1.3.0
[1.2.1]: https://github.com/uPortal-contrib/form-builder/compare/v1.2.0...v1.2.1
[1.2.0]: https://github.com/uPortal-contrib/form-builder/compare/v1.1.2...v1.2.0
[1.1.2]: https://github.com/uPortal-contrib/form-builder/compare/v1.1.1...v1.1.2
[1.1.1]: https://github.com/uPortal-contrib/form-builder/compare/v1.1.0...v1.1.1
[1.1.0]: https://github.com/uPortal-contrib/form-builder/compare/v1.0.3...v1.1.0
[1.0.3]: https://github.com/uPortal-contrib/form-builder/compare/v1.0.2...v1.0.3
[1.0.2]: https://github.com/uPortal-contrib/form-builder/compare/v1.0.1...v1.0.2
[1.0.1]: https://github.com/uPortal-contrib/form-builder/compare/v1.0.0...v1.0.1
[1.0.0]: https://github.com/uPortal-contrib/form-builder/compare/v0.2.5...v1.0.0
[0.2.5]: https://github.com/uPortal-contrib/form-builder/compare/v0.2.4...v0.2.5
[0.2.4]: https://github.com/uPortal-contrib/form-builder/compare/v0.2.3...v0.2.4
[0.2.3]: https://github.com/uPortal-contrib/form-builder/compare/v0.2.2...v0.2.3
[0.2.2]: https://github.com/uPortal-contrib/form-builder/compare/v0.2.1...v0.2.2
[0.2.1]: https://github.com/uPortal-contrib/form-builder/compare/v0.2.0...v0.2.1
[0.2.0]: https://github.com/uPortal-contrib/form-builder/compare/v0.1.2...v0.2.0
[0.1.2]: https://github.com/uPortal-contrib/form-builder/compare/v0.1.1...v0.1.2
[0.1.1]: https://github.com/uPortal-contrib/form-builder/compare/v0.1.0...v0.1.1
[0.1.0]: https://github.com/uPortal-contrib/form-builder/compare/bc446238d1735b424bd2a004d9b737c380592b2e...v0.1.0
