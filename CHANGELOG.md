## [0.2.2](https://github.com/nicklockwood/Consumer/releases/tag/0.2.2) (2018-03-08)

- Added support for matching Foundation `CharacterSet`s, along with several new character-based convenience methods (see README for details)
- Deprecated the old character-matching methods in favor of `character(in: ...)` variants
- Added ~2x performance improvement when using the new character consumers

## [0.2.1](https://github.com/nicklockwood/Consumer/releases/tag/0.2.1) (2018-03-06)

- Added fast-paths when using `flatten`, `replace` and `discard` transforms
- Improved performance of JSON example, and added performance tips section to README
- Fixed infinite loop bug with nested optionals inside zeroOrMore consumer
- Added handwritten JSON parser for benchmark comparison

## [0.2.0](https://github.com/nicklockwood/Consumer/releases/tag/0.2.0) (2018-03-05)

- Fixed a bug where the character offset reported in an error message was wrong in some cases
- Transform function values argument is now an array. This solves a consistency issue where an `.optional(.string(...))` consumer would return a string if matched but an empty array if not matched

## [0.1.1](https://github.com/nicklockwood/Consumer/releases/tag/0.1.1) (2018-03-03)

- Significantly improved parsing performance

## [0.1.0](https://github.com/nicklockwood/Consumer/releases/tag/0.1.0) (2018-03-01)

- First release
