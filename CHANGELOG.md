# Changelog

## v2.2.2 - 2020-07-09

### Changed

- Used [use-latest](https://www.npmjs.com/package/use-latest) for handling refs in `useBeforeunload` hook.
- Updated devDependencies.

## v2.2.1 - 2020-05-20

### Changed

- Enabled loose mode on '@babel/preset-env' to reduce build output.
- Updated devDependencies.

## v2.2.0 - 2020-04-27

## Added

- Added ES Module build.
- Added `defaultProps` to `Beforeunload` component.

### Changed

- Updated devDependencies.

## v2.1.0 - 2019-06-23

### Added

- Added type-checking to `useBeforeunload` hook.

## v2.0.1 - 2019-06-20

### Added

- Added `Event.preventDefault()` workaround for Chromium browsers.

### Removed

- Removed `default` export.

## v2.0.0 - 2019-06-02

### Added

- Added `useBeforeunload` hook.

### Changed

- **BREAKING** Requires [react](https://www.npmjs.com/package/react) peerDependency to be v16.8.0 or newer.
- **BREAKING** `Beforeunload` is now a named export.
- Changed `Beforeunload` component to be functional and use hooks internally.

## v1.1.1 - 2019-06-02

### Fixed

- Fixed failing builds due to missing Babel plugin.

## v1.1.0 - 2019-06-02

### Changed

- Builds are now done with [Rollup](http://rollupjs.org).
- Updated devDependencies.

## v1.0.4 - 2017-08-21

### Changed

- Updated [react](https://www.npmjs.com/package/react) peerDependency to support React 16.

## v1.0.3 - 2017-07-28

### Fixed

- Fixed rendering when no `children` are set.
  
## v1.0.2 - 2017-07-27

### Fixed

- Fixed publishing to NPM registry.

## v1.0.1 - 2017-07-27

### Fixed

- Fixed wrong class being exported.

## v1.0.0 - 2017-07-15

Initial public version! :tada: