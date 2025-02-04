# Changelog
All notable changes to this project will be documented in this file.

The format is loosely based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.6.5] - 2023-02-13
- Fixed effects not being generated due to missing level (#19)

## [1.6.4] - 2023-01-23
- Added setting to control/disable the "shift+click" feature (#17)

## [1.6.1] - 2023-01-08
- Changed feat effects to signify time left to recharge after being expended (#15), thanks @xdy!
- [1.6.2] Fixed bug introduced after merging this new feature (#16)

## [1.6.0] - 2022-11-06
- Removed "hidden effects" feature - migrated to core "Unidentified" effect functionality

## [1.5.2] - 2022-10-29
- Fixed slight metagame leak of hidden effect existence (#13)

## [1.5.1] - 2022-10-24
- Added full localization support for French

## [1.5.0] - 2022-10-23
- Added keyboard shortcut and setting to make effects hidden
- Added basic localization support (french)

## [1.4.2] - 2022-10-22
- Added hidden effects feature (#8)

## [1.3.2] - 2022-10-21
- Improved the Shift+click code stability (credit to reonZ/Idle)

## [1.3.1] - 2022-10-05
- Fixed Ctrl+Shift+E error when striking (bad slug name) (#8)

## [1.3.0] - 2022-08-07
- Upgraded to v10 compatibility
- Fixed effects with "1 or more" in their duration (will be set as Unlimited)

## [1.2.1] - 2022-07-09
- Fixed shift-click reducing "locked" sub-conditions

## [1.2.0] - 2022-07-08
- Added ability to Shift+click to edit effects in the effects panel (#2)
- Added ability to Ctrl+Shift+E to create a new effect (#4)

## [1.1.0] - 2022-06-24
- Changed behavior of Shift key (held while activating) to be more generic and simple:  will open the effect's sheet.
- Made afflictions with a maximum duration use that duration for the effect.
- [1.1.1] Added lib-wrapper to dependencies, though it was already a dependency before

## [1.0.0] - 2022-06-16
- Created the module

## See also: [Unreleased]

[1.0.0]: https://github.com/shemetz/pf2e-extempore-effects/compare/1.0.0...1.0.0
[1.1.0]: https://github.com/shemetz/pf2e-extempore-effects/compare/1.0.0...1.1.0
[1.1.1]: https://github.com/shemetz/pf2e-extempore-effects/compare/1.1.0...1.1.1
[1.2.0]: https://github.com/shemetz/pf2e-extempore-effects/compare/1.1.1...1.2.0
[1.2.1]: https://github.com/shemetz/pf2e-extempore-effects/compare/1.2.0...1.2.1
[1.3.0]: https://github.com/shemetz/pf2e-extempore-effects/compare/1.2.1...1.3.0
[1.3.1]: https://github.com/shemetz/pf2e-extempore-effects/compare/1.3.0...1.3.1
[1.3.2]: https://github.com/shemetz/pf2e-extempore-effects/compare/1.3.1...1.3.2
[1.4.2]: https://github.com/shemetz/pf2e-extempore-effects/compare/1.3.2...1.4.2
[1.5.0]: https://github.com/shemetz/pf2e-extempore-effects/compare/1.4.2...1.5.0
[1.5.1]: https://github.com/shemetz/pf2e-extempore-effects/compare/1.5.0...1.5.1
[1.5.2]: https://github.com/shemetz/pf2e-extempore-effects/compare/1.5.1...1.5.2
[1.6.0]: https://github.com/shemetz/pf2e-extempore-effects/compare/1.5.1...1.6.0
[1.6.1]: https://github.com/shemetz/pf2e-extempore-effects/compare/1.6.0...1.6.1
[1.6.2]: https://github.com/shemetz/pf2e-extempore-effects/compare/1.6.1...1.6.2
[1.6.4]: https://github.com/shemetz/pf2e-extempore-effects/compare/1.6.2...1.6.4
[1.6.5]: https://github.com/shemetz/pf2e-extempore-effects/compare/1.6.4...1.6.5
[Unreleased]: https://github.com/shemetz/pf2e-extempore-effects/compare/1.6.5...HEAD
