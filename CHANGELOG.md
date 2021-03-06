# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]


## [0.3.0] - 2021-04-07

### Added
- Allow filtering searches by temporal extent and publication date
- Add ordering of search results
- Add Changelog to the online documentation
- Further improve the look of search results

### Changed
- All HTTP requests are now done in a background thread to avoid blocking QGIS UI
- Load layers in a background thread in order to avoid blocking QGIS UI
- Improve feedback shown when searching and loading layers
- Move Title search filter out of the collapsible group, so that it is easier to access

### Fixed
- Improved error handling
- Fix incorrect visibility of the Search/Next/Previous search buttons
- Reset pagination when pressing Search button
- Remove unused Add/Close buttons on datasource manager dialogue


## [0.2.0] - 2021-02-28

### Added
- Add initial support for earlier GeoNode versions
- Initial support for search filters
- Add support for applying a vector layer's default SLD style when loading

### Changed
- Improve look of search results

### Fixed
- Fix invalid update date for versions released via custom plugin repo


## [0.1.1] - 2021-02-02

### Fixed
- Invalid tag format in previous version prevented automated distribution to our custom QGIS repo


## [0.1.0] - 2021-02-02 [YANKED]

### Added
- Load GeoNode layers into QGIS
- Load a GeoNode metadata into the corresponding QGIS layer
- Manage GeoNode connections through the plugin GUI
- Improve plugin metadata and documentation

### Fixed
- Current connection settings are now always up-to-date with the GUI


## [0.0.9] - 2021-01-11

### Fixed
-  Invalid plugin zip name


## [0.0.8] - 2021-01-08

### Fixed
-  Remove pycache files from plugin zip


## [0.0.7] - 2021-01-08

### Fixed
-  Invalid CI settings


## [0.0.6] - 2021-01-08

### Fixed
-  Invalid CI settings


## [0.0.5] - 2021-01-08

### Added
-  Initial project structure
-  Add infrastructure for automated testing
-  Add infrastructure for managing releases
-  Add geonode API client


[unreleased]: https://github.com/kartoza/qgis_checklist_checker/compare/v0.3.0...main
[0.3.0]: https://github.com/kartoza/qgis_checklist_checker/compare/v0.3.0...main
[0.2.0]: https://github.com/kartoza/qgis_checklist_checker/compare/v0.2.0...main
[0.1.1]: https://github.com/kartoza/qgis_checklist_checker/compare/v0.1.1...main
[0.1.0]: https://github.com/kartoza/qgis_checklist_checker/compare/v0.1.0...main
[0.0.9]: https://github.com/kartoza/qgis_checklist_checker/compare/v0.0.9...main
[0.0.8]: https://github.com/kartoza/qgis_checklist_checker/compare/v0.0.8...main
[0.0.7]: https://github.com/kartoza/qgis_checklist_checker/compare/v0.0.7...main
[0.0.6]: https://github.com/kartoza/qgis_checklist_checker/compare/v0.0.6...main
[0.0.5]: https://github.com/kartoza/qgis_checklist_checker/compare/v0.0.5...main
