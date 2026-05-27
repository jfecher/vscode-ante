# Change Log

All notable changes to the "ante" extension will be documented in this file.

This project adheres to [Keep a Changelog](http://keepachangelog.com/).

## [0.3.2] - 2026-05-27

### Changed
- Improved highlight of function calls, `fn` is now properly highlighted as a keyword when in a trailing position

## [0.3.1] - 2026-05-27

### Added
- New keywords in syntax highlighting, including `exists`, `forall`, `freeze`, `implicit`, and `var`.
- File icons for `.an` files (light and dark themes).

### Changed
- Improved float literal highlighting, including optional type suffixes.
- Default `ante.languageServerPath` is now `ante-ls`, resolved from `$PATH`, instead of the hardcoded `/opt/ante/target/release/ante-ls`. Set an absolute path to override.
- Updated the README screenshots and extension icon.

## [0.3.0] - 2025-06-04

### Added
- Basic Language Server Protocol (LSP) support via `vscode-languageclient`, with a configurable `ante.languageServerPath` setting.
- Extension icon.

### Changed
- Expanded the keyword list and updated dependencies.

## [0.2.0] - 2022-03-13

### Changed
- Syntax highlighting updates.

## [0.1.0] - 2022-03-13

### Added
- Ante syntax highlighting and language configuration.

## [0.0.1] - 2022-03-13

### Added
- Initial release.
