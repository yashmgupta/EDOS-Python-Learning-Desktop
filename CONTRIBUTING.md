# Contributing to EDOS

Thank you for your interest in improving **EDOS — Educational Desktop Operating Simulator**.

EDOS is designed for beginner-friendly Python education. Contributions should preserve that goal: students should feel safe experimenting, teachers should be able to understand the interface quickly, and the application should remain lightweight enough to run from GitHub Pages.

## Before You Contribute

Please:

1. Read the project README.
2. Search existing GitHub Issues before creating a duplicate.
3. Use an Issue to discuss large changes before spending significant time implementing them.
4. Keep contributions focused and easy to review.
5. Do not include copyrighted educational material, datasets, images, fonts, or code unless you have the right to contribute them.

## Ways to Contribute

Useful contributions include:

- Bug fixes
- Browser compatibility improvements
- Accessibility improvements
- Beginner Python lessons
- Jupyter notebook examples
- Small classroom-safe datasets
- Thai translations
- Additional language translations
- Teacher documentation
- UI/UX improvements
- Performance improvements
- Security hardening
- Tests and reproducible bug reports

## Educational Design Principles

Contributions should generally follow these principles:

- Prefer plain language over jargon.
- Explain errors in a constructive and actionable way.
- Keep examples small enough for beginners to understand.
- Avoid unnecessary installation steps.
- Prefer progressive learning: show one new idea at a time.
- Keep student data local whenever practical.
- Make important actions obvious and reversible.
- Do not intentionally expose students to unsafe browser, filesystem, or network behavior.

## Technical Principles

EDOS is intentionally designed around a lightweight single-page architecture.

When modifying the application:

- Prefer vanilla JavaScript, CSS, and browser APIs.
- Avoid adding large frameworks unless discussed first.
- Preserve GitHub Pages compatibility.
- Preserve graceful behavior on common modern browsers.
- Keep external dependencies limited and well documented.
- Avoid silently sending student code or notebook content to external servers.
- Sanitize or safely render untrusted library content.
- Keep notebook and package behavior compatible with the browser / Pyodide sandbox.

## Adding Educational Materials

The live EDOS library reads content from the repository's `book/` folder.

Use the appropriate location:

```text
book/python/       Python learning material
book/datasets/     CSV/TSV datasets
book/notebooks/    Jupyter notebooks
book/workshops/    Workshop handouts and teaching packs
```

### PDFs

Use descriptive names, for example:

```text
python-variables-beginner.pdf
python-loops-workshop.pdf
```

### Datasets

Datasets should be:

- small enough for browser-based learning;
- free of private or sensitive student information;
- documented sufficiently for a beginner to understand the columns; and
- licensed or created in a way that permits publication.

### Notebooks

Notebook contributions should:

- include Markdown explanations;
- use short code cells;
- avoid requiring unsupported native packages;
- keep output sizes reasonable; and
- clearly identify any required dataset path.

## Branch and Commit Suggestions

Branch examples:

```text
fix/notebook-output
feature/new-thai-lesson
content/weather-dataset
accessibility/keyboard-navigation
```

Commit examples:

```text
fix: keep matplotlib output inside notebook cells
feat: add beginner CSV viewer
content: add Thai variables lesson
accessibility: improve taskbar keyboard focus
```

These conventions are recommended, not mandatory.

## Pull Requests

A good pull request should explain:

- what changed;
- why it changed;
- how it was tested;
- whether it changes student-facing behavior;
- whether it adds external dependencies;
- whether screenshots are useful for review; and
- whether new educational material has appropriate publishing rights.

Please use the provided pull-request template.

## Contributor Rights and Project License

By submitting a contribution, you confirm that you have the right to submit it.

Unless separately agreed in writing, you grant the EDOS project owner a perpetual, worldwide, non-exclusive, royalty-free license to use, reproduce, modify, adapt, distribute, sublicense, display, perform, and incorporate your contribution into EDOS and related official project materials.

Contributors retain copyright in their original contributions unless copyright is separately assigned in writing.

Please read [`LICENSE.md`](LICENSE.md) before contributing.

## Conduct

All project participation is subject to [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md).

## Security Issues

Do not publish sensitive vulnerability details in a normal public Issue. Follow [`SECURITY.md`](SECURITY.md).

## Questions

If you are unsure whether an idea fits EDOS, open a GitHub Discussion or Issue describing the educational goal before implementing it.

Thank you for helping make Python learning more approachable.
