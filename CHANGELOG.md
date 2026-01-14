# Changelog

All notable changes to DotCode will be documented in this file.

The format follows Keep a Changelog (https://keepachangelog.com/)
and adheres to Semantic Versioning (https://semver.org/).

---

## [1.0.0] – 2026-01-13

### Added
- Initial release of the DotCode language family
- Dot language with unary dot-length encoding
- NumDot language with numeric dot-terminated encoding (`<ASCII>.`)
- Reversible Python ↔ Dot compiler and runtime
- Reversible Python ↔ NumDot compiler, decoder, and runtime
- Command-line interfaces: `dot` and `numdot`
- Editable installation and PyPI-ready packaging

### Notes
- This is the first stable public release.
- Dot language uses `.dcode` as the recommended file extension.
- NumDot language uses `.nd` as the recommended file extension.
