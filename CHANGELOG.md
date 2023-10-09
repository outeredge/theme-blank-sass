# Changelog

## [1.3.10] - 2019-10-28
- added patch from https://github.com/SnowdogApps/magento2-theme-blank-sass/pull/224 to show tooltips correctly


## [1.3.8] - 2019-10-25
- remove icon font and image display variable

## [1.3.5] - 2019-10-24
- icon font and image display variable

## [1.3.4] - 2019-10-17
- added border radius and text transform to `lib-button-reset()`

## [1.3.3] - 2019-09-19
- added border radius variable to button mixin
- added text-transform variable to button mixin
- added border radius to pager mixin
- added optional background icon and colour choise for ratings summary stars (as we needed to have outlines of the stars for unselected state)


## [1.3.2] - 2019-08-07
- removed concatination from `Magento_Catalog/styles/module/_listings.scss` (starting to remove concatination wherever it appears, in favour of css that is meant for a human to read, not a computer)


## [1.3.1] - 2019-07-18
Removed lib-css mixins

## [Unreleased]

## [1.5.0] - 2020-10-26
### Changed
- Removed Magento framework dependency from `composer.json` to simply maintenance and add Magento 2.4 support (#241)

## [1.4.0] - 2020-03-10
### Added
- PageBuilder support (#235)

### Changed
- Reorganise `styles/vendor/magento-ui/_lib` Imports (#226)
- LESS fade mixin for rgba (#225)

## [1.3.0] - 2019-07-06
### Added
- Email styles support (#84)

### Changed
- Reorganize imports of Magento UI SASS related files to match less theme structure (#204)

### Removed
- XML decleration that were removed in Magento 2.3 sass blank theme (#208)
