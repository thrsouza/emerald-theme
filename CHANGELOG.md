# Changelog

All notable changes to the **Emerald Minimal Theme** extension are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.3.0] - 2026-05-23

### Added

- **Semantic highlighting colors** (`semanticTokenColors`) for both variants. Language servers can now color classes, interfaces, enums, parameters, properties, decorators, default-library symbols and read-only variables precisely, instead of falling back to TextMate scopes — noticeably more accurate highlighting in TypeScript, Rust, Python and C#.
- Theming for newer VS Code UI areas: inline chat / Copilot panels (`chat.*`, `inlineChat*`), notebooks (`notebook.*`, status icons), the multi-file diff editor, profile badge, banner, keybinding labels, toolbar/sash hover, testing icons & message decorations, debug toolbar, stack-frame highlight, debug console, the Settings editor, and the running-port icon.
- Language-specific syntax refinements: distinct escape characters, regex internals (anchors, quantifiers, character classes, groups), Markdown blockquotes/strikethrough/heading marks/inline code, JSX/TSX components & tag punctuation, and CSS/SCSS/LESS class, id, property and element selectors.

### Fixed

- Raised comment contrast to meet WCAG AA (4.5:1): dark `#6b737c` (3.9:1) → `#7d8590` (5.1:1), light `#6e7781` (4.2:1) → `#656d76` (4.8:1). All other syntax colors were audited and already pass AA.

## [1.2.0] - 2026-05-22

### Changed

- Raised the minimum supported VS Code version (`engines.vscode`) from `^1.25.0` to `^1.70.0`, matching the UI areas the theme actually styles (sticky scroll, command center, inlay hints, merge-conflict regions).
- Shrank the packaged extension from 2.2 MB to ~90 KB by optimizing the icon (1254×1254 → 256×256) and excluding preview images from the VSIX.

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
