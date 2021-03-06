# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
## [0.4.9] - 2020-12-17
### Fixed
- Tax id validation for testing mode was fixed due to the fact that api sometimes failed

### Added
- Pre api validation mechanism / with regex expressions based on the information on https://ec.europa.eu/taxation_customs/vies/faq.html#item_15
## [0.3.1] - 2020-12-17
### Fixed
- Validation checking mechanism adapted to handle the vat checking flow correctly
## [0.3.0] - 2020-12-16
### Added
- Support for vat_eu_if:field,compare_value
- Support for vat_eu_address_and_if:countryfield,field,compare_value
## [0.2.2] - 2020-10-04
### Fixed
- Remove composer.lock from source code.
## [0.2.1] - 2020-09-09
### Added
- Added support for Laravel 8
## [0.2.0] - 2020-07-10
### Changed
- Changed the structure and make the soap calls mockable to ensure that tests works.

## [0.1.0] - 2020-06-28
### Added
- Added Facade
- Added validation rule for validation purpose

