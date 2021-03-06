# Change Log

All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## 1.10.1 - 2017-08-30
### FIxed
- GeoJSON export now contains the same data as the visual map display
### Optimized
- 'Regenerating Indexes' only takes ~60% as long as before!

## 1.9.5 - 2017-07-17
### Fixed
- Fixed electron version bundling issue that was causing the Windows installer to crash
- Re-enabled `npm prune` during Windows packaging (results in smaller EXE sizes)
- Fixed Windows builds by forcing Appveyor to use npm@5.2.0

## 1.9.4 - 2017-07-17
**BROKEN BUILD**
### Notes
- Tried to fix build by disabling `npm prune` during Windows packaging

## 1.9.3 - 2017-07-17
**BROKEN BUILD**
### Fixed
- Add missing dependencies

## 1.9.2 - 2017-07-17
**BROKEN BUILD**
### Fixed
- App no longer crashes when a GeoJSON export is performed

## 1.9.1 - 2017-07-14
**BROKEN BUILD**
### Fixed
- Fixed 'unknown entity' errors caused by osm-p2p-server omitting deleted nodes

## 1.9.0 - 2017-07-11
**BROKEN BUILD**
### Added
- Added versioning information to osm-p2p-db indexes
- Added an "indexes generating" dialog when index generation is in progress on
  start-up
### Removed
- Took out old (unused) data migration logic

## 1.8.3 - 2017-07-06
### Fixed
- App no longer crashes when no presets are present

## 1.8.2 - 2017-05-19

## 1.8.1 - 2017-05-17
### Fixed
- Fixed 'Export as GeoJSON..' menu option

## [1.8.0] - 2017-05-06
### Changed
- Removed 255 char restriction on text fields

## [1.7.0] - 2017-04-30
### Added
- Add deforking to GeoJSON export
- Add GeoJSON Export menu item
### Fixed
- Use latest metadata.json for displaying dialogs
- Removed unused dev dep: browserify


## [1.2.3] - 2016-10-30

### Changed
- Use osm-p2p-geojson for export

### Added
- Cloud build scripts for Mac & Windows
- Create DMG installer for Mac

## [1.2.2] - 2016-09-22

### Changed
- Update dep to osm-p2p-server-veta3

## [1.2.0] - 2016-08-17
### Added
- Custom icons

### Changed
- Import settings / configuration from a single file

## 1.1.0 - 2016-08-05

Start of Change Log

[1.8.0]: https://github.com/digidem/mapeo-desktop/compare/v1.7.0...v1.8.0
[1.7.0]: https://github.com/digidem/mapeo-desktop/compare/v1.2.3...v1.7.0
[1.2.3]: https://github.com/digidem/mapeo-desktop/compare/v1.2.2...v1.2.3
[1.2.2]: https://github.com/digidem/mapeo-desktop/compare/v1.2.0...v1.2.2
[1.2.0]: https://github.com/digidem/mapeo-desktop/compare/v1.1.0...v1.2.0
