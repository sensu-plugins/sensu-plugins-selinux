# Change Log
This project adheres to [Semantic Versioning](http://semver.org/).

This CHANGELOG follows the format listed [here](https://github.com/sensu-plugins/community/blob/master/HOW_WE_CHANGELOG.md)

## [Unreleased]
## [2.0.0] - 2018-12-08
### Security
- updated rubocop dependency to `~> 0.51.0` per: https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2017-8418. @jaredledvina

### Breaking Changes
- removed < ruby 2.1 support which was pulled as part of security updates @jaredledvina
- Update sensu-plugin to 3.0: https://github.com/sensu-plugins/sensu-plugin/blob/master/CHANGELOG.md#300---2018-12-04 @jaredledvina

## [1.0.1] - 2017-06-14
### Fixed
- Fix homepage link (@eheydrick)

## [1.0.0] - 2017-06-07
### Added
- Support for Ruby 2.3 and 2.4 (@eheydrick)

### Removed
- Support for Ruby 1.9.3 (@eheydrick)

### Changed
- Relax `sensu-plugin` dependency to `~> 1.2` (@mattyjones)
- Rubocop upgrade and cleanup

## [0.0.4] - 2016-01-05
### Fixed
- fixed gem name in gemspec, no functional changes

## [0.0.3] - 2016-01-05
### Changed
- rubocop update and cleanup

## [0.0.2] - 2015-07-14
### Changed
- updated sensu-plugin gem to 1.2.0

## 0.0.1 - 2015-07-04
### Added
- initial release

[Unreleased]: https://github.com/sensu-plugins/sensu-plugins-selinux/compare/2.0.0...HEAD
[2.0.0]: https://github.com/sensu-plugins/sensu-plugins-selinux/compare/1.0.1...2.0.0
[1.0.1]: https://github.com/sensu-plugins/sensu-plugins-selinux/compare/1.0.0...1.0.1
[1.0.0]: https://github.com/sensu-plugins/sensu-plugins-selinux/compare/0.0.4...1.0.0
[0.0.4]: https://github.com/sensu-plugins/sensu-plugins-selinux/compare/0.0.3...0.0.4
[0.0.3]: https://github.com/sensu-plugins/sensu-plugins-selinux/compare/0.0.2...0.0.3
[0.0.2]: https://github.com/sensu-plugins/sensu-plugins-selinux/compare/0.0.1...0.0.2
