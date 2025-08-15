# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.1.55](https://github.com/rust-lang/cmake-rs/compare/v0.1.54...v0.1.55) - 2025-08-15

### Other

- Make sure that cmake generate build files in current dir ([#194](https://github.com/rust-lang/cmake-rs/pull/194))
- Set the MSRV to 1.65 and test this in CI
- Canonicalize the build directory
- Use `eprintln` instead to print the command running next ([#191](https://github.com/rust-lang/cmake-rs/pull/191))
# Changelog

## [Unreleased]

## [0.1.54](https://github.com/rust-lang/cmake-rs/compare/v0.1.53...v0.1.54) - 2025-02-10

### Other

- Remove workaround for broken `cc-rs` versions ([#235](https://github.com/rust-lang/cmake-rs/pull/235))
- Be more precise in the description of `register_dep` ([#238](https://github.com/rust-lang/cmake-rs/pull/238))

## [0.1.53](https://github.com/rust-lang/cmake-rs/compare/v0.1.52...v0.1.53) - 2025-01-27

### Other

- Disable broken Make jobserver support on OSX to fix parallel builds ([#229](https://github.com/rust-lang/cmake-rs/pull/229))

## [0.1.52](https://github.com/rust-lang/cmake-rs/compare/v0.1.51...v0.1.52) - 2024-11-25

### Other

- Expose cc-rs no_default_flags for hassle-free cross-compilation ([#225](https://github.com/rust-lang/cmake-rs/pull/225))
- Add a `success` job to CI
- Change `--build` to use an absolute path
- Merge pull request [#195](https://github.com/rust-lang/cmake-rs/pull/195) from meowtec/feat/improve-fail-hint
- Improve hint for cmake not installed in Linux (code 127)

## [0.1.51](https://github.com/rust-lang/cmake-rs/compare/v0.1.50...v0.1.51) - 2024-08-15

### Added

- Add JOM generator support ([#183](https://github.com/rust-lang/cmake-rs/pull/183))
- Improve visionOS support ([#209](https://github.com/rust-lang/cmake-rs/pull/209))
- Use `Generic` for bare-metal systems ([#187](https://github.com/rust-lang/cmake-rs/pull/187))

### Fixed

- Fix cross compilation on android armv7 and x86 ([#186](https://github.com/rust-lang/cmake-rs/pull/186))

