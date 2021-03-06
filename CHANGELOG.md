# Change log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [3.0.4] - 2015-08-31

### Fixed

* Removed default margin from elements to make r-margin work everywhere
* Fixed default legend styling
* Fix to make popovers work inside overflow hidden

### Added

* Added pop-under variant of popovers
* Added utility class to make grid columns snap to fullwidth when printing
* Added fullwidth class to labels

### Breaking changes

* Bugfix for popovers necessitates slightly different markup

## [3.0.1] - 2015-08-07

### Fixed

* Fix syntax error in the minified version
* Fix legend layout and behaviour for misc groups
* Fix better clearfix on print
* Fix font-weight and line-heigth to .h1-.h4 and .t1-.t4

## [3.0.0] - 2015-06-15 [YANKED]

### Added:

* Use PostCSS as packer and pre/postprocessor.
    * Add css-variables and custom-media queries
    * Add autoprefixer, and remove inline prefixed declarations and functions
    * Images optimized with imageoptim

### Changed

* Only *.min.css is minified

### Breaking changes

* Package does not include src directory. Use dist instead.
* Remove images (that are likely not in use)
* Remove third party css folder
* Do not generate dist/spaden-{version} anymore
