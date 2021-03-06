# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Added

### Changed

## [0.10.0] - 2018-03-16
### Added
-- Stucts for combining multiple hyper services

### Changed

## [0.9.0] - 2018-01-25
### Added
- Connector functions for instantiating easy-mode clients
- The ability to pass in a `slog::Logger` with Context

## [0.8.1] - 2017-12-20
### Changed
- Fix build error and clippy warning.

## [0.8.0] - 2017-12-15
### Added
- Asynchronous HTTP client/server support

### Removed
- Synchronous HTTP client/server support - if you're still using synchronous swagger-codegen, stay at 0.7.0

### Changed
- `AllowAllMiddleware` (an Iron middleware) has been replaced by `AllowAllAuthenticator` (a Hyper Service wrapper)

## [0.7.0] - 2017-10-02
### Added
- `ContextWrapper` - wraps an `Api` with a `Context`

## [0.6.0] - 2017-09-25
### Changed
- Authorization struct now has new field `issuer`.

## [0.5.0] - 2017-09-18
- Start of changelog.

[Unreleased]: https://github.com/Metaswitch/swagger-rs/compare/0.10.0...HEAD
[0.10.0]: https://github.com/Metaswitch/swagger-rs/compare/0.9.0...0.10.0
[0.9.0]: https://github.com/Metaswitch/swagger-rs/compare/0.8.1...0.9.0
[0.8.1]: https://github.com/Metaswitch/swagger-rs/compare/0.8.0...0.8.1
[0.8.0]: https://github.com/Metaswitch/swagger-rs/compare/0.7.0...0.8.0
[0.7.0]: https://github.com/Metaswitch/swagger-rs/compare/0.6.0...0.7.0
[0.6.0]: https://github.com/Metaswitch/swagger-rs/compare/0.5.0...0.6.0
[0.5.0]: https://github.com/Metaswitch/swagger-rs/compare/0.4.0...0.5.0
