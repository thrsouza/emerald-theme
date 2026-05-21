# Changelog

All notable changes to the **Emerald Minimal Theme** extension are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.1.0] - 2026-05-21

### Added

- Bracket pair colorization in a monochrome emerald scheme (levels distinguished by brightness, not hue).
- Theming for previously-unstyled UI areas: sticky scroll, command center, menus, inlay hints, inline suggestions (ghost text), merge-conflict regions, overview-ruler diagnostic/Git markers, and terminal selection & command decorations.

### Fixed

- **Dark:** strings and tags rendered in a near-illegible dark teal (`#006b5e`, ~2.9:1 contrast). Strings now use light blue (`#a5d6ff`) and tags green (`#7ee787`), restoring WCAG-compliant contrast.
- **Light:** split the type/string/tag colors that all shared `#006b5e`, so they are now visually distinct.

### Changed

- Unified the warning/Git-modified yellow into a single tone (dark `#e3b341`, light `#9a6700`).
- Made the editor selection more visible (`#00d2be4d`).

## [1.0.0]

### Added

- **Emerald Minimal Dark** variant — near-black "midnight" surfaces (`#050505` / `#0c0c0c` / `#111111`) with a vivid emerald/teal accent (`#00d2be`).
- **Emerald Minimal Light** variant — clean white surfaces with a deeper emerald accent (`#006b5e` / `#00b8a6`) tuned for contrast.
- Full workbench theming: activity bar, side bar, status bar, tabs, lists, inputs, buttons, badges, peek view, terminal and Git decorations.
- Syntax highlighting with emerald-highlighted types/classes and a rose-red (`#f7768e`) for keywords.
