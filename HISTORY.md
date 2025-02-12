# History

## v1.1.2 2016 March 20
- Repackaged

## v1.1.1 2016 March 20
- Fix `projectz: line 1: //: is a directory`

## v1.1.0 2016 March 20
- Repackaged with [Editions](https://github.com/bevry/editions)
- Added editions rendering

## v1.0.9 2015 December 10
- Updated esnextguardian script

## v1.0.8 2015 December 7
- Moved from ECMAScript Modules to CommonJS Modules due to lack of Node.js support
- Updated base files

## v1.0.7 2015 November 30
- Updated dependencies

## v1.0.6 2015 September 21
- Browser install instructions will now correctly display is bower or component configuration exists, or `browser` or `jspm` fields exist

## v1.0.5 2015 September 21
- Updated dependencies

## v1.0.4 2015 September 20
- Fixed missing `esnextguardian` dependency (regression since v1.0.3)

## v1.0.3 2015 September 20
- Readme files will correctly finish with a newline character
- Updated dependencies
- Fixed second author losing their year

## v1.0.2 2015 September 18
- Continue if fetching github contributors fails

## v1.0.1 2015 September 16
- Fixed github API auth for user api requests

## v1.0.0 2015 September 16
- Initial stable release
- Readme and Package files are now extension independent
- Readme sections are now outputted in HTML instead of Markdown to be more universal
- Support SPDX licenses
	- Implements [#72](https://github.com/bevry/projectz/issues/72), [#66](https://github.com/bevry/projectz/issues/66)
	- Fixes [#65](https://github.com/bevry/projectz/issues/65)
- Uses new [bevry/badges](https://github.com/bevry/badges) package for badge rendering
	- Implements [#67](https://github.com/bevry/projectz/issues/67), [#55](https://github.com/bevry/projectz/issues/55), [#25](https://github.com/bevry/projectz/issues/25), [#10](https://github.com/bevry/projectz/issues/10)
- Uses new [bevry/fellow](https://github.com/bevry/fellow) package for people handling
	- Implements [#37](https://github.com/bevry/projectz/issues/37), [#11](https://github.com/bevry/projectz/issues/11)
- Newline no longer required at start of readme file
	- Fixes [#53](https://github.com/bevry/projectz/issues/53)
- Moved from CoffeeScript to ES6+
	- Fixes [#20](https://github.com/bevry/projectz/issues/20)

## v0.5.0 2015 February 24
- Support multiple licenses
	- Currently only MIT and CC-BY-4.0 are supported

## v0.4.3 2015 February 13
- Appends new line when saving packages

## v0.4.2 2015 February 11
- Fixes cmd line -d option
- Fixes CRLF issue that occurred in the v0.4.1 npm package

## v0.4.1 2015 February 09
- Fixes incorrect handling of CSON.parseFile

## v0.4.0 2015 February 09
- Removed merging of dependencies between Package.json and Bower.json
- Added Node v0.12.0 support

## v0.3.17 2014 December 11
- Fixed david badges (regression from v0.3.16)

## v0.3.16 2014 December 11
- Better badges
- New npm downloads badge
- Updated dependencies

## v0.3.15 2014 June 23
- Updated dependencies

## v0.3.14 2014 May 31
- Add support for global install instructions

## v0.3.13 2014 May 17
- Keep contributor cache valid for one day

## v0.3.12 2014 May 17
- Updated dependencies

## v0.3.11 2014 February 19
- Added [DocPad](http://docpad.org) plugin install instructions
- Added support for the `browser` field, see readme

## v0.3.10 2014 February 6
- Added [Waffle.io](http://waffle.io) badge
- Added Wishlist badge

## v0.3.9 Unknown
- Always show david dependency and dev dependency badges if they are enabled, rather than disabling them if there are no dependencies or dev dependencies

## v0.3.8 Unknown
- Cleaner badge determination

## v0.3.7 2014 January 03
- Updated [david-dm](https://david-dm.org/) to use the [Shields.io](http://shields.io/) theme
	- Thanks to [Rob Loach](https://github.com/RobLoach) for [pull request #26](https://github.com/bevry/projectz/pull/26)

## v0.3.6 2014 January 03
- Added bitcoin badge which accepts a URL via the `bitcoin` badge option
- Donation badges are now on their own line

## v0.3.5 2014 January 01
- Only show david dm badges if there actually are dependencies for that badge

## v0.3.4 2014 January 01
- Added [david-dm](https://david-dm.org/) dev dependency badge support
- Automatic badge detection for `daviddev`

## v0.3.3 2014 January 01
- Added [david-dm](https://david-dm.org/) badge support
	- Thanks to [Rob Loach](https://github.com/RobLoach) for [pull request #21](https://github.com/bevry/projectz/pull/21)
- Automatic badge detection for `travis`, `npm`, and `david` badges
- Travis file is now regarded as a readme file

## v0.3.2 2013 December 16
- Formatting changes to backers listing

## v0.3.1 2013 December 16
- Formatting changes to backers listing

## v0.3.0 2013 December 12
- Client-side install instructions will only show if `browser` property is truthy
- Added new `browser` property that will default to true if `bower` or `component` packages are defined

## v0.2.10 2013 December 12
- Moved `docco` from `dependencies` into `devDependencies` where it belongs

## v0.2.9 2013 December 12
- Fixed CDN URL highlighting

## v0.2.8 2013 December 12
- Changed `HISTORY.md` and `CONTRIBUTING.md` URLs and names to always be uppercase
- Added [wzrd.in](http://wzrd.in/) CDN URL to the Node/Browserify install section

## v0.2.7 2013 November 25
- Updated dependencies

## v0.2.6 2013 November 6
- Updated dependencies

## v0.2.5 2013 October 31
- Seems github doesn't like `//` urls

## v0.2.4 2013 October 31
- Updated badges to use `//` for their urls

## v0.2.3 2013 October 23
- Fixed error when encountering an unknown license

## v0.2.2 2013 October 23
- Fixed `license` and `licenses` duplicate in `package.json` file
- Fixed some issues with contributors and `package.json` files

## v0.2.1 2013 October 16
- Fixed some issues. Now stable enough to use for your projects.

## v0.2.0 2013 October 16
- Added INSTALL, BACKER, and BACKERFILE tags

## v0.1.0 2013 October 15
- Mostly working except for BACKER tags

## v0.0.2 2013 September 19
- Renamed from `readme-utils` to `projectz`

## v0.0.1 2013 June 19
- Initial non-working commit
