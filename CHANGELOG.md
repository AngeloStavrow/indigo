# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Added
- Added entrypoints config section as described in [#73](https://github.com/AngeloStavrow/indigo/issues/73)

## [1.3.2] - 2019-10-17

### Added

- A _Support and Maintenance_ section has been added to the README, per [#64](https://github.com/AngeloStavrow/indigo/issues/64)

### Changed

- Updated the Hugo minimum version to 0.58.3

## [1.3.1] - 2019-10-03

### Fixed

- Taxonomy-based lists (e.g., lists of tags or categories) now only show posts within the selected taxonomy per [#56](https://github.com/AngeloStavrow/indigo/issues/56)

## [1.3.0] - 2019-09-30

### Added

- Adds a `mainSection` configuration parameter to set preferred content name per [#56](https://github.com/AngeloStavrow/indigo/issues/56)

### Changed

- Updated **CONTRIBUTING.md** to reflect new contributions process per [#28](https://github.com/AngeloStavrow/indigo/issues/28)
- Bumped the minimum Hugo version requirement to 0.58 to account for [#52](https://github.com/AngeloStavrow/indigo/issues/52)

### Fixed

- As part of an audit of the theme's code per [#57](https://github.com/AngeloStavrow/indigo/issues/57)
  - Removed forward slashes (`/`) in URLs for better compatibility with sites that don't live at a domain root
  - Fixed the location from which the theme's fonts are loaded

### Removed

- GitHub issue and pull request templates removed from the repo per [#28](https://github.com/AngeloStavrow/indigo/issues/28)

## [1.2.0] - 2019-08-31

### Added

- You can now import custom CSS from `<YOUR_HUGO_SITE>/static/css/custom.css` per [#48](https://github.com/AngeloStavrow/indigo/issues/48)

## [1.1.0] - 2019-08-28

### Changed

- Metadata now shows page title and description per [#50](https://github.com/AngeloStavrow/indigo/issues/50), thanks to [@infominer33](https://github.com/infominer33)!

### Fixed

- Breaking changes in article lists introduced in Hugo 0.57 per [#52](https://github.com/AngeloStavrow/indigo/issues/52)
- Newer/Older links in article footers now work as expected in Hugo 0.50 and later per [#54](https://github.com/AngeloStavrow/indigo/issues/54)

## [1.0.6] - 2019-06-24

### Fixed

- Fixed some copy/paste errors in CSS `font-family` definitions per [#38](https://github.com/AngeloStavrow/indigo/issues/38)
- Fixed `<h1>` font-sizing per [#41](https://github.com/AngeloStavrow/indigo/issues/41)

## [1.0.5] - 2019-06-05

### Fixed

- Cleaned up some errant whitespace thanks to [@dixonge](https://github.com/dixonge)!

## [1.0.4] - 2019-10-25

### Added

- Users can now add their Medium and LinkedIn accounts as social networks, thanks to [@RicardoBelchior](https://github.com/RicardoBelchior)!

### Changed

- Clearer process for contributing to the project ([#28](https://github.com/AngeloStavrow/indigo/issues/28))

### Fixed

- Better instructions for users that prefer a little more YAML in their lives, thanks to [@zwbetz-gh](https://github.com/zwbetz-gh)!
- Fix for broken content div in 404.html ([#21](https://github.com/AngeloStavrow/indigo/issues/21))
- The `src` URL for the site logo had an extra `/`, and now it doesn't, thanks to [@michimani](https://github.com/michimani)!

## [1.0.3] - 2019-10-21

### Added

- Users can now add their Reddit account as a social network, thanks to [@sauerj](https://github.com/sauerj)!

### Fixed

- The 404.html page now properly links back to the homepage, thanks to [@sauerj](https://github.com/sauerj)!
- Custom fonts are now loaded correctly, hopefully speeding up rendering ([#23](https://github.com/AngeloStavrow/indigo/issues/23))
- The site expected fonts to load from the site root, even if your site was installed to a subdirectory. Now they don't. ([#27](https://github.com/AngeloStavrow/indigo/issues/27))

## [1.0.2] - 2019-10-15

### Fixed

- Broken link to compare v1.0.1 against v1.0 in this change log.
- Updated example site theme name.

## [1.0.1] - 2018-10-14

### Fixed

- The Fira Code font is now part of the theme download, rather than downloading from rawgit ([#17](https://github.com/AngeloStavrow/indigo/issues/17)).

## 1.0.0 - 2018-09-30

### Added

- The first public release of the indigo theme for Hugo, along with related project documentation (including this changelog).

<!-- [Unreleased]: https://github.com/AngeloStavrow/indigo/compare/v1.3.0...HEAD -->

[1.3.2]: https://github.com/AngeloStavrow/indigo/compare/v1.3.1...v1.3.2
[1.3.1]: https://github.com/AngeloStavrow/indigo/compare/v1.3.0...v1.3.1
[1.3.0]: https://github.com/AngeloStavrow/indigo/compare/v1.2.0...v1.3.0
[1.2.0]: https://github.com/AngeloStavrow/indigo/compare/v1.1.0...v1.2.0
[1.1.0]: https://github.com/AngeloStavrow/indigo/compare/v1.0.6...v1.1.0
[1.0.6]: https://github.com/AngeloStavrow/indigo/compare/v1.0.5...v1.0.6
[1.0.5]: https://github.com/AngeloStavrow/indigo/compare/v1.0.4...v1.0.5
[1.0.4]: https://github.com/AngeloStavrow/indigo/compare/v1.0.3...v1.0.4
[1.0.3]: https://github.com/AngeloStavrow/indigo/compare/v1.0.2...v1.0.3
[1.0.2]: https://github.com/AngeloStavrow/indigo/compare/v1.0.1...v1.0.2
[1.0.1]: https://github.com/AngeloStavrow/indigo/compare/v1.0...v1.0.1
