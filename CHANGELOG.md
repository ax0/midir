# Changelog

All major changes to this project will be documented in this file.

## [0.9.0] - 2023-01-08

- Upgrade `alsa` and `windows` dependencies (the latter now requires `rustc 1.64`)
- [winrt] Fix received data buffer size ([#116](https://github.com/Boddlnagg/midir/pull/116))
- [alsa] Fix port listing ([#117](https://github.com/Boddlnagg/midir/pull/117))
- [alsa] Send messages without buffering ([#125](https://github.com/Boddlnagg/midir/pull/125))

## [0.8.0] - 2022-05-13

- Migrate Windows backends to Microsoft's `windows` crate
- Upgrade `coremidi` and `alsa` dependencies
- Implement `PartialEq` for ports

## [0.7.0] - 2020-09-05

- Update some Linux dependencies (`alsa`, `nix`)
- Improve error handling for `MMSYSERR_ALLOCATED` (Windows)

## [0.6.2] - 2020-07-21

- Remove deprecated usage of `mem::uninitialized`
- Switch from `winrt-rust` to `winrt-rs` for WinRT backend

## [0.6.1] - 2020-06-04

- Implement `Clone` for port structures
- Add trait that abstracts over input and output

## [0.6.0] - 2020-05-11

- Upgrade to winapi 0.3
- Add WinRT backend
- Add WebMIDI backend
- Use platform-specific representation of port identifiers instead of indices

## [0.5.0] - 2017-12-09

- Switch to absolute μs timestamps

## [0.4.0] - 2017-09-27

- Add CoreMIDI backend
- Use `usize` for port numbers and counts

## [0.3.2] - 2017-04-06

- Use `alsa-rs` instead of homegrown wrapper

## [0.3.1] - 2017-03-21

- Fix crates.io badges

## [0.3.0] - 2017-03-21

- Fix compilation on ARM platforms