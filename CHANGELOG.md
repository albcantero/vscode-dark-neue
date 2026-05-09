# Changelog

## [2.0.0]

### Added
- **GitHub Scheme** variant: UI neutrals get a subtle blue tint (+8 on the blue channel), with GitHub-inspired syntax colors (green strings, red operators, blue keywords, orange constants).
- `widget.border` and `editorWidget.border` tokens (`#FFFFFF0D`).
- `menubar.selectionForeground` (`#DBDFE0`).

### Changed
- **Fully monochrome UI**: all accent colors removed from the chrome. Buttons, bars, focus rings, selections, and progress indicators now use a pure gray scale.
  - Buttons: blue `#4F8FDD` → gray `#606060`/`#747474`.
  - Links and notifications: blue `#48A0C7` → near-white `#ededed`.
  - Progress bar: green `#A3BE8C` → gray `#747474`.
  - Focus border: dark blue `#30373a` → neutral `#494949`.
  - Status bar debugging state: blue `#434C5E` → `#343434`/`#a1a1a1`.
  - `menubar.selectionBackground`: semi-transparent → solid `#1d1d1d`.
  - `list.hoverBackground`: transparent → `#2A2A2A99` (visible hover for the first time).
  - Menu and picker borders: transparent → `#FFFFFF0D`.
- `editor.foreground`: `#DBDFE0` → `#CCCCCC`.
- `punctuation.definition.tag` (HTML/XML tags): `#DBDFE0` → `#CCCCCCA6` (semi-transparent).
- Import/module keywords: italic removed, color `#646695` → neutral `#CCCCCC`.
- CSS hex color values split into a dedicated rule with color `#D1D6AE`.

### Deprecated
- **High Contrast** as a standalone theme. In a future release it will be replaced by a user-configurable option in `settings.json` (e.g. `darkModernNeue.highContrast: true`), with no need to switch themes.

---

## [1.1.2]

### Fixed
- Theme IDs corrected: `Default Dark Modern Neue in High Contrast` → `Default Dark Modern Neue High Contrast`; `Default Minimal Dark Modern Neue` → `Default Dark Modern Neue Minimal`.

### Fixed (Minimal)
- Line highlight: `#101010` → `#161616`.
- Error color unified to `#f14445` across all relevant tokens (editor, gutter, input validation, list, terminal, minimap).

---

## [1.1.1]

### Changed (Minimal — full palette rewrite)
- Primary foreground raised from `#b4b4b4` to `#ededed`, affecting the entire UI and syntax.
- Gray scale consolidated: mid-gray `#525252`/`#737373` → `#747474`; warning-gray `#a3a3a3` → `#a1a1a1`.
- Selection changed from neutral white to teal: `editor.selectionBackground` `#ffffff15` → `#0cc5b330`.
- Syntax teal adjusted: `#7DCFCA` → `#0cc5b3`.
- Inactive line numbers: `#262626` → `#404040`.
- Italic removed from several syntax tokens (variables, parameters, modules).
- Terminal ANSI colors normalized to the new gray scale.

---

## [1.1.0]

### Changed
- Theme IDs corrected from `Visual Studio` prefix to `Default` across all three variants (fixes categorization in VS Code).
- Added `storage.type.class.jsdoc` to the JSDoc tag rule (`@param`, `@return`, `@throws`) in all three variants.
- Removed legacy abbreviated theme files (`-hc.json`, `-mn.json`).

---

## [1.0.1]

### Changed
- **High Contrast** and **Minimal** variants rebuilt from scratch and renamed to their final file names (`-high-contrast.json`, `-minimal.json`).
- Added `comment.block.documentation` to the docstring highlight rule (base variant).

---

## [1.0.0]

Initial release. Three variants: Dark Modern Neue, High Contrast, and Minimal.
