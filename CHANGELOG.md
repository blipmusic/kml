# Changelog

## Unreleased

## [v0.4.2](https://github.com/georust/kml/releases/tag/v0.4.2)

- Updates `quick-xml` to [v0.22](https://github.com/tafia/quick-xml/blob/master/Changelog.md#0220) which doesn't expose any breaking changes for this API
- Fix compilation issue when `zip` feature is disabled ([#22](https://github.com/georust/kml/pull/7)) from [@vilaureu](https://github.com/vilaureu)

## [v0.4.1](https://github.com/georust/kml/releases/tag/v0.4.1)

- Fix issue with sibling `kml:Folder` or `kml:Document` elements nesting ([#19](https://github.com/georust/kml/pull/19))

## [v0.4.0](https://github.com/georust/kml/releases/tag/v0.4.0)

- Clippy cleanup ([#3](https://github.com/georust/kml/pull/3))
- Add support for `kml:Location` ([#7](https://github.com/georust/kml/pull/7)) from [@Nadhum](https://github.com/Nadhum)
- Add support for `kml:Scale` ([#8](https://github.com/georust/kml/pull/8)) from [@Nadhum](https://github.com/Nadhum)
- Add support for `kml:Orientation` ([#8](https://github.com/georust/kml/pull/9)) from [@Nadhum](https://github.com/Nadhum)
- Require clippy and rustfmt in CI ([#14](https://github.com/georust/kml/pull/14))
- Add support for `hotSpot` element within `kml:IconStyle`, including a new `Units` enum and `Vec2` struct ([#13](https://github.com/georust/kml/pull/13)) from [@ardouglas](https://github.com/ardouglas)

## [v0.3.1](https://github.com/georust/kml/releases/tag/v0.3.1)

- Handle UTF-8 decoding issues without a panic, fixing [#1](https://github.com/georust/kml/issues/1)

## [v0.3.0](https://github.com/georust/kml/releases/tag/v0.3.0)

- Cleaned up method names (i.e. "parse*" to "read*")
- Added `KmlWriter::from_writer`
- Update license to MIT/Apache-2.0
- Transfer to georust

## [v0.2.0](https://github.com/georust/kml/releases/tag/v0.2.0)

- Initial functionality for reading, writing, and conversion
