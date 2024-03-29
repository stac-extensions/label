# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.0.1] - 2021-08-23
### Changed
- `label:properties` as array needs at least one item
- `name` in `label:classes` must be non-empty for vector label items
- `name` in `label:classes` must be `null` for raster label items (#8)
- `label:description` must be non-empty

### Fixed
- Fixed invalid examples
- JSON Schema checks `label:assets` in links

## [v1.0.0] - 2021-03-8
### Changed
- assets should use role `labels` instead of an asset name of `labels`
- Clarified the role of geometries on items. [#875](https://github.com/radiantearth/stac-spec/pull/875)
- `label:description` now allows CommonMark for rich-text representation ([#950](https://github.com/radiantearth/stac-spec/issues/950))

### Fixed
- Cleaned up examples

[Unreleased]: https://github.com/stac-extensions/label/compare/v1.0.1...HEAD
[1.0.1]: https://github.com/stac-extensions/label/compare/vv1.0.0...v1.0.1
[v1.0.0]: https://github.com/stac-extensions/label/tree/v1.0.0
