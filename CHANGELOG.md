Change log for PC Engines fork of SeaBIOS
=========================================

Fourth digit in release number means PC Engines patch.

## [Unreleased]
## [rel-1.9.2.4] - 2016-01-23
###Changed
- change debug output of version string to show, when using the sgabios and
  also serial output

## [rel-1.9.2.3] - 2016-01-03
### Fixed
- fix the issue that 2 banner messages with version are shown on
  default debug level

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

[Unreleased]: https://github.com/pcengines/seabios/compare/rel-1.9.2.4...coreboot-4.0.x
[rel-1.9.2.4]: https://github.com/pcengines/seabios/compare/rel-1.9.2.3...rel-1.9.2.4
[rel-1.9.2.3]: https://github.com/pcengines/seabios/compare/rel-1.9.2.2...rel-1.9.2.3
[rel-1.9.2.2]: https://github.com/pcengines/seabios/compare/rel-1.9.2.1...rel-1.9.2.2
[rel-1.9.2.1]: https://github.com/pcengines/seabios/compare/rel-1.9.2...rel-1.9.2.1
