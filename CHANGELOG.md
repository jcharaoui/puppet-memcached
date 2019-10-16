# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [3.4.0]
### Fixed
- factor should be a string or number, not boolean
### Added
- Add Puppet 6 to travis checks
### Changed
- Update Puppet version requirement to include version 6 (< 7.0.0)
- Unpin firewall module in fixtures
- Require puppetlabs_spec_helper >= 2.11.0
### Removed
- Drop Ruby 2.1 from travis checks