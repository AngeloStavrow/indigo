# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.0.6]
### Fixed
- Fixed some copy/paste errors in CSS `font-family` definitions per [#38](https://github.com/AngeloStavrow/indigo/issues/38)
- Fixes `<h1>` font-sizing per [#41](https://github.com/AngeloStavrow/indigo/issues/41)

## [1.0.5]
### Fixed
- Cleaned up some errant whitespace thanks to [@dixonge](https://github.com/dixonge)!

## [1.0.4]
### Added
- Users can now add their Medium and LinkedIn accounts as social networks, thanks to [@RicardoBelchior](https://github.com/RicardoBelchior)!

### Changed
- Clearer process for contributing to the project ([#28](https://github.com/AngeloStavrow/indigo/issues/28))

### Fixed
- Better instructions for users that prefer a little more YAML in their lives, thanks to [@zwbetz-gh](https://github.com/zwbetz-gh)!
- Fix for broken content div in 404.html ([#21](https://github.com/AngeloStavrow/indigo/issues/21))
- The `src` URL for the site logo had an extra `/`, and now it doesn't, thanks to [@michimani](https://github.com/michimani)!

## [1.0.3]
### Added
- Users can now add their Reddit account as a social network, thanks to [@sauerj](https://github.com/sauerj)!

### Fixed
- The 404.html page now properly links back to the homepage, thanks to [@sauerj](https://github.com/sauerj)!
- Custom fonts are now loaded correctly, hopefully speeding up rendering ([#23](https://github.com/AngeloStavrow/indigo/issues/23))
- The site expected fonts to load from the site root, even if your site was installed to a subdirectory. Now they don't. ([#27](https://github.com/AngeloStavrow/indigo/issues/27))

## [1.0.2]
### Fixed
- Broken link to compare v1.0.1 against v1.0 in this change log.
- Updated example site theme name.

## [1.0.1] - 2018-10-14
### Fixed
- The Fira Code font is now part of the theme download, rather than downloading from rawgit ([#17](https://github.com/AngeloStavrow/indigo/issues/17)).

## 1.0.0 - 2018-09-30
### Added
- The first public release of the indigo theme for Hugo, along with related project documentation (including this changelog).

[Unreleased]: https://github.com/AngeloStavrow/indigo/compare/v1.0.6...HEAD
[1.0.6]: https://github.com/AngeloStavrow/indigo/compare/v1.0.5...v1.0.6
[1.0.5]: https://github.com/AngeloStavrow/indigo/compare/v1.0.4...v1.0.5
[1.0.4]: https://github.com/AngeloStavrow/indigo/compare/v1.0.3...v1.0.4
[1.0.3]: https://github.com/AngeloStavrow/indigo/compare/v1.0.2...v1.0.3
[1.0.2]: https://github.com/AngeloStavrow/indigo/compare/v1.0.1...v1.0.2
[1.0.1]: https://github.com/AngeloStavrow/indigo/compare/v1.0...v1.0.1
