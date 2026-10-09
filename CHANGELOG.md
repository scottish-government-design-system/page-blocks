# Change log

All notable changes to page blocks will be documented in this file.

Changes are grouped under the labels: `Added`, `Changed`, `Deprecated`, 
`Removed`, `Fixed`, and `Security`.

---
## v2.1.0
### Added
- Nunjucks macros for each page block, with supporting documentation and examples
- GovUK Prototype Kit plugin config, so page blocks can be used in prototypes
- Video and text block now includes a play button overlay for the image link
### Changed
- Scottish Government Design System dependency bumped to v4.3.0
- First child item in a page block or within a text block has its top margin removed
- Prepack changed to Prepare in npm scripts

## v2.0.0
### Changed
- Sass changed to modular Sass
- Browse and card page block headings no longer underlined when links

## v1.1.1
### Added
- Browse page block

## v1.0.1
### Fixed
- Vertically centre option for media and text blocks only applied to fixed width sizes

## v1.0.0
### Added
- Feature header
- Primary, secondary and theme background colour support
- Vertical centre align option for media and text blocks
### Changed
- Change package name from content blocks to page blocks
- CSS prefix changed from `ds_cb` to `ds_pb`
- Divider page block line is now either full width or the `ds_wrapper` width
- Divider page block background is always transparent, while the line colour is defined by the block's chosen background colour
- Background colour on a block is always full width, unless it is the Feature Header block which offers additional options
- Updated to use v3.0.1 of the Scottish Government Design System
- Simplified support for themes to give a consistent colour palette for a site
### Removed
- Support for `ds_cb` prefix classes, use old version of content blocks package to continue to use old html markup
- Page title page block removed and replaced by new Feature header
- Option to set foreground colour for headings

## v0.1.2
### Added
- Relative positioning to feature grid items to support absolute positioning of edit buttons in the Bloomreach CMS

## v0.1.1
### Fixed
- Incorrect path in documentation

## v0.1.0
### Added
- Migrate content block Sass from Scottish Government Design System to this new repo