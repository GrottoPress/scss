# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [0.5.2] - 2023-04-12

### Fixed
- Fix divisor (`/`) [deprecation warning](https://sass-lang.com/documentation/breaking-changes/slash-div)

## 0.5.1 - 2019-04-17

### Added
- Set `files` attribute in npm config
- Add `.security.txt`
- Add `.gitattributes`

## 0.5.0 - 2019-04-16

### Added
- Add `.editorconfig`
- Show screen reader text on keyboard focus

### Changed
- Rename `LICENSE.md` to `LICENSE`

## 0.4.1 - 2018-07-27

### Added
- Added `columns` argument to grid mixin.

## 0.4.0 - 2018-07-26

### Removed
- All vendor-prefixed rules. You may use [postcss](https://www.npmjs.com/package/postcss) with [autoprefixer](https://www.npmjs.com/package/autoprefixer) for those.

### Changed
- Refactor `grid()` mixin to use padding (instead of margin) for gutter

## 0.3.1 - 2018-07-23

### Fixed
- Override previously set `nth-child()` margins for grid children

## 0.3.0 - 2018-07-23

### Added
- Flex box mixins
- `_all.scss` that imports all scss files.

### Changed
- Rename `full-screen()` mixin to `full-width()`
- Redo `grid()` mixin using flex box and margins

## 0.2.1 - 2018-07-16

### Changed
- Ensure children inherit box-sizing of their parent

## 0.2.0 - 2018-04-27

### Added
- More font stacks

## 0.1.11 - 2018-01-05

### Changed
- Reimplemented grid mixin to use padding instead of margin

## 0.1.10 - 2018-01-04

### Changed
- Applied horizontal padding to all children of grid

## 0.1.9 - 2018-01-04

### Fixed
- Added back inline-block whitespace fix mistakenly removed from grid mixin

## 0.1.8 - 2017-12-27

### Added
- Added opacity mixin
- Added inline-block whitespace fix mixin

## 0.1.6 - 2017-12-09

### Changed
- Removed option to apply grid width float.

## 0.1.5 - 2017-12-09

### Changed
- Added `columns` option to grid mixin

## 0.1.0 - 2017-12-07

### Added
- Initial public release
