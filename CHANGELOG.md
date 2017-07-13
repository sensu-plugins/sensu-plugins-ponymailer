#Change Log
This project adheres to [Semantic Versioning](http://semver.org/).

This CHANGELOG follows the format listed at [Keep A Changelog](http://keepachangelog.com/)

## [Unreleased]
### Removed
- Ruby 1.9.3 support

### Added
- Ruby 2.3 support
- Ruby 2.4.1 testing

## [0.0.4] - 2015-12-03
## Removed
- Removed timeout gem dependency that was conflicting with stdlib

## Changed
- Updated to rubocop 0.32.1

## [0.0.3] - 2015-07-14
### Changed
- updated sensu-plugin gem to 1.2.0

## [0.0.2] - [2015-07-10]
### Changed
- set deps in alpha order in `Rakefile`
- set deps in alpha order in gemspec
- update documentation links in README and CONTRIBUTING

### Fixed
- fix typo in handler-ponymailer.rb
- fix undefined method `arguments`
- set binstubs to only be created for ruby files

## 0.0.1 - [2015-06-02]
### Added
- initial release

[Unreleased]: https://github.com/sensu-plugins/sensu-plugins-ponymailer/compare/0.0.4...HEAD
[0.0.4]: https://github.com/sensu-plugins/sensu-plugins-ponymailer/compare/0.0.3...0.0.4
[0.0.3]: https://github.com/sensu-plugins/sensu-plugins-ponymailer/compare/0.0.2...0.0.3
[0.0.2]: https://github.com/sensu-plugins/sensu-plugins-ponymailer/compare/0.0.1...0.0.2
