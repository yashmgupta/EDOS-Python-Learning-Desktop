# Changelog

All notable changes to **EDOS — Educational Desktop Operating Simulator** should be documented in this file.

The project currently uses a simple human-readable changelog. Version numbers can be aligned with GitHub Releases when formal releases begin.

## [Unreleased]

### Added

- Windows-inspired educational desktop interface
- Live taskbar clock and Start menu
- Multi-window application framework
- Python IDLE-style beginner editor
- Browser-side Python execution with Pyodide
- Python terminal / REPL
- Kid-friendly Python error translation
- Local browser VFS and autosave
- Guided Code Adventures lessons
- English beginner Python course presentation
- Thai beginner Python course presentation
- One-click language switching in teaching slides
- Integrated Python setup PDF reader
- Browser-side Python package manager
- Jupyter-style notebook application
- Code and Markdown notebook cells
- Persistent notebook namespace during a session
- `%pip` / package-install teaching workflows where supported
- Inline Matplotlib figures in Jupyter notebook cells
- Data Lab notebook examples
- CSV dataset examples
- Live GitHub `book/` library
- Nested live-library folder navigation
- PDF, CSV/TSV, image, Markdown/text, JSON, Python, and notebook viewing workflows
- EDOS desktop copyright branding

### Changed

- Increased teaching-presentation body and bullet text for classroom projection
- Routed Matplotlib visual output to Jupyter notebook cells for clearer teaching behavior
- Improved integration between EDOS virtual files and notebook/data-analysis workflows

### Security

- Added project security-reporting guidance
- Added contribution and educational-content publishing rules

---

## Suggested Release Process

When publishing a formal release:

1. Move completed entries from `[Unreleased]` to a version heading.
2. Use a date in `YYYY-MM-DD` format.
3. Create a matching Git tag and GitHub Release.
4. Update `CITATION.cff` if the software version changes.

Example:

```text
## [1.0.0] - 2026-09-10
```
