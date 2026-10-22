# Changelog

All notable changes to this project will be documented in this file.

Pre-`v1.0.0` version numbers below are inferred from project milestones because
the early history was not tagged with release versions.

## [Unreleased]

No unreleased changes yet.

## [v1.0.1] - 2026-10-22

### Added

- Added a favicon (cat icon cropped from the watermark logo on the obsidian
  background): `favicon.ico`, `media/favicon-32.png`, `media/favicon-512.png`
  and `media/apple-touch-icon.png`, linked from the `<head>` of `index.html`.

### Changed

- Panels and call-to-action buttons now show the pointer (hand) cursor on hover.
- Updated README and VERSIONING.md to reflect v1.0.0 and v1.0.1 changes.

## [v1.0.0] - 2026-10-22

### Added

- Added taglines under each profile heading: "I Imagine. I Envision. I Create."
  and "I Learn. I Question. I Grow."
- Linked the Scholar panel to https://ungkufarhah-portfolio.sfworks.top.

### Changed

- Renamed "The Architect" to "The Visionary".
- Enlarged the name and role labels on both panels.
- Mobile panels now grow with their content instead of using a fixed height.

### Removed

- Removed the custom cursor; the default system cursor is used again.

### Fixed

- Fixed the "View Journey" button being cut off by the footer on mobile.

## [v0.1.1] - 2026-04-17

### Added

- Added [VERSIONING.md](VERSIONING.md) with a quick guide for updating the
  site version in `index.html`.
- Added visible version support in the shared footer.
- Added watermark assets and watermark styling for portfolio branding.

### Changed

- Updated the shared footer to use plain-text version messaging on desktop and
  mobile.
- Updated the mobile watermark behavior to stay centered in the viewport while
  the page scrolls.
- Added separate versioning and changelog documentation for manual maintenance.

## [v0.1.0] - 2026-04-16

### Added

- Initial release of the static split-screen portfolio landing page.
- Added the Architect and Scholar hero panels in a single `index.html` file.
- Added the base README with setup, customization, and deployment guidance.
- Added the cinematic hover behavior, responsive stacked mobile layout, and
  custom cursor effect.
