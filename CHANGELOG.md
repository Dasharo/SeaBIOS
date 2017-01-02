Change log for PC Engines fork of SeaBIOS
=========================================

Fourth digit in release number means PC Engines patch.

## [Unreleased]
## [rel-1.9.2.2] - 2016-12-13
### Changed
- simplify version displayed during boot

### Fixed
- remove screen control character by disable screen cleaning when loading
  sgabios

## [rel-1.9.2.1] - 2016-10-04
### Added
- allowed for one-time `PXE ` boot with `N` key
- enable/disable option for `USB` boot
- enable/disable option for `PXE` boot

### Fixed
- prevented from printing character multiple times

[Unreleased]: https://github.com/pcengines/seabios/compare/rel-1.9.2.2...coreboot-4.0.x
[rel-1.9.2.2]: https://github.com/pcengines/seabios/compare/rel-1.9.2.1...rel-1.9.2.2
[rel-1.9.2.1]: https://github.com/pcengines/seabios/compare/rel-1.9.2...rel-1.9.2.1
