# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.6.0] - 2020-10-29

### Changed
- `list-context.image-list` has been refactored to use the `image-list` with a `list-context`

### Added
- `image-list` a new block that renders a simple list of images that can be editable via the Site Editor 

## [0.5.3] - 2020-10-07
### Removed
- Remove description of `new-image` schema to make it not available in the new CMS.

## [0.5.2] - 2020-09-15
### Fixed
- `experimentalPreventLayoutShift` not being passed down to `Image`s rendered by `ImageList`.

## [0.5.1] - 2020-09-09

### Fixed
- `title` prop to `Image` component

## [0.5.0] - 2020-08-10
### Added
- `experimentalPreventLayoutShift` prop to `Image` component

### Changed
- `ImageList` component uses `experimentalPreventLayoutShift` prop.

## [0.4.5] - 2020-07-10
### Added
- Title and description to `image` block schema to make it compliant with the new cms.

### Security
- Bump dependency versions.

## [0.4.4] - 2020-05-14
### Fixed
- Users not able to configure links to open in new tabs via Site Editor.

## [0.4.3] - 2020-04-24
### Changed
- Use `useIntl` hook instead of the HOC.

### Fixed
- `react-intl` typings that was breaking the build.

### Security
- Bump dependencies versions.

## [0.4.2] - 2020-04-14

### Fixed
- README.md documentation 

## [0.4.1] - 2020-03-04
### Fixed
- Potential runtime error on ImageList component.

## [0.4.0] - 2020-02-10
### Added
- `title` prop to the `Image` component.

## [0.3.1] - 2019-11-22
### Removed
- Default values for the props `maxWidth` and `maxHeight` in `Image`.

## [0.3.0] - 2019-11-01
### Added
- `image-uploader` widget to `Image` contentSchema.

## [0.2.1] - 2019-10-24

## [0.2.0] - 2019-10-22
### Added
- New `ImageList` component that uses `list-context`.

## [0.1.0] - 2019-10-10
### Added
- Initial implementation.
- Port `Image` component from `vtex.store-components`.
- Create `ImageSlider` component.
- New `image-slider` interface.
