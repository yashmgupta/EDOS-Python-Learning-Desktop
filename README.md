# EDOS — Educational Desktop Operating Simulator

> **Learn Python. Experiment safely. No installation required.**

**EDOS** is a browser-based educational desktop environment designed for students, beginners, teachers, workshops, coding clubs, and computer-science classrooms.

**Created by Dr. Yash Munnalal Gupta.**

EDOS provides a Windows-inspired learning desktop with real Python execution in the browser through **Pyodide / WebAssembly**. Students can write Python, use a terminal, work in Jupyter-style notebooks, install compatible Python packages, analyze CSV data, view learning PDFs, and follow guided lessons without installing a local Python environment.

---

## 🌐 Live EDOS

### ▶️ [Launch EDOS — Python Learning Desktop](https://yashmgupta.github.io/EDOS-Python-Learning-Desktop/)

**Live website:**  
https://yashmgupta.github.io/EDOS-Python-Learning-Desktop/

**GitHub repository:**  
https://github.com/yashmgupta/EDOS-Python-Learning-Desktop

No installation is required. Open the live site in a modern browser and start learning Python immediately.

---

## ✨ Main Features

- 🐍 Real Python execution in the browser using Pyodide
- 📝 Beginner-friendly Python IDLE-style editor
- 🟠 Jupyter-style notebook environment with code and Markdown cells
- 📦 Browser-side Python package manager for compatible packages
- 📊 Inline Matplotlib figures inside notebook cells
- 💻 Interactive Python terminal / REPL
- 📚 Guided Python learning material
- 🇬🇧 English teaching content
- 🇹🇭 Thai teaching content
- 📄 Integrated PDF learning material
- 📁 Live GitHub Books library powered by the repository `book/` folder
- 📊 CSV and TSV dataset viewing
- 💾 Local browser autosave for student work
- 🧒 Kid-friendly Python error explanations
- 🖥️ Windows-inspired educational desktop interface
- 🔒 Client-side code execution with no Python application server required

---

## 🎓 Who EDOS Is For

EDOS is intended for:

- School students
- University beginners
- Teachers and lecturers
- Python workshops
- Coding clubs
- STEM programs
- Self-learning students
- Computer laboratories where software installation is restricted
- Institutions looking for a zero-install Python teaching environment

---

## 🚀 Quick Start for Students

1. Open **[EDOS online](https://yashmgupta.github.io/EDOS-Python-Learning-Desktop/)**.
2. Open **Python IDLE** or **Jupyter Notebook** from the desktop.
3. Create a new Python file or notebook.
4. Write some Python:

```python
print("Hello, EDOS!")
```

5. Press **Run**.
6. Read the output and experiment.

No local Python installation is required for the browser playground.

---

## 🟠 Jupyter-Style Notebook

EDOS includes a beginner-friendly notebook environment where students can:

- Create `.ipynb` notebooks
- Add Python code cells
- Add Markdown / explanation cells
- Run one cell at a time
- Run all cells
- Keep variables between executed cells
- Load CSV files
- Use pandas and NumPy when available
- Display Matplotlib figures inline
- Save notebooks in the EDOS browser workspace

Example:

```python
import numpy as np
import matplotlib.pyplot as plt

x = np.arange(1, 6)
y = x ** 2

plt.plot(x, y)
plt.title("My First Graph")
plt.show()
```

---

## 📦 Python Packages

EDOS can load many packages provided by Pyodide and can install compatible pure-Python packages with `micropip`.

Common teaching packages may include:

```text
numpy
pandas
matplotlib
scipy
scikit-learn
```

Because Python runs inside WebAssembly in a browser, not every desktop Python package is compatible. Packages that require unsupported native operating-system binaries, hardware access, system services, or desktop GUI frameworks may not work.

---

## 📚 Live Learning Library

The EDOS desktop contains a **Books / Live Library** folder. It reads the contents of this repository's `book/` directory at runtime when hosted publicly on GitHub Pages.

This means teachers can update learning materials without rebuilding the main EDOS HTML application.

Example repository layout:

```text
book/
├── python/
│   └── python-basics.pdf
├── datasets/
│   ├── students.csv
│   └── weather.csv
├── notebooks/
│   └── introduction.ipynb
└── workshops/
    └── workshop-01.pdf
```

After committing a new file to `book/`, students can refresh the EDOS Books app and see the latest published content.

### Supported library content

Depending on the EDOS viewer, the library can work with formats such as:

- PDF
- CSV / TSV
- Jupyter Notebook (`.ipynb`)
- Markdown
- Text files
- JSON
- Python source files
- Common browser-compatible images

---

## 📁 Repository Structure

```text
EDOS-Python-Learning-Desktop/
├── index.html
├── README.md
├── LICENSE.md
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
├── SECURITY.md
├── CITATION.cff
├── CHANGELOG.md
├── ROADMAP.md
├── book/
│   ├── python/
│   ├── datasets/
│   ├── notebooks/
│   └── workshops/
└── .github/
    ├── ISSUE_TEMPLATE/
    └── PULL_REQUEST_TEMPLATE.md
```

---

## 🌍 Languages

Current educational content includes:

- 🇬🇧 English
- 🇹🇭 Thai

Translations and localization improvements are welcome through authorized collaboration.

---

## 🔐 Privacy and Safety

Student Python code is designed to execute locally in the browser through Pyodide rather than being sent to a remote Python execution server.

Internet access may still be required for:

- Loading Pyodide and external frontend assets
- Loading compatible Python packages
- Reading the live GitHub `book/` library
- Opening externally hosted resources

Teachers should review external learning materials before classroom use.

---

## 🤝 Collaboration

EDOS welcomes collaboration with:

- Educators
- Researchers
- Developers
- Schools and universities
- Translators
- Educational organizations
- Curriculum designers
- Data-science instructors

Useful contribution areas include:

- New beginner lessons
- Thai and other-language translations
- Accessibility improvements
- Notebook examples
- Classroom datasets
- Documentation
- Bug fixes
- Browser compatibility
- Teacher tools

Please read [`CONTRIBUTING.md`](CONTRIBUTING.md) before proposing changes.

---

## ⚖️ Copyright and Licensing

Copyright © Dr. Yash Munnalal Gupta. All rights reserved except where permission is explicitly granted.

This repository is **source-visible for educational demonstration, evaluation, and authorized collaborative development**. Public visibility does not automatically grant permission to redistribute, rebrand, sell, sublicense, or publish modified distributions of EDOS.

See [`LICENSE.md`](LICENSE.md) for the project terms.

> **Important:** The custom license is a project policy draft and should be reviewed by a qualified intellectual-property lawyer before being relied upon for commercial, institutional, or cross-jurisdictional enforcement.

Third-party libraries, frameworks, fonts, images, and other dependencies remain subject to their own licenses and terms.

---

## 🔬 Academic Citation

If EDOS is used in a publication, research project, workshop report, dissertation, teaching study, or academic project, please cite the project.

GitHub-compatible citation metadata is provided in [`CITATION.cff`](CITATION.cff).

Suggested plain-text citation:

> Gupta, Yash Munnalal. *EDOS — Educational Desktop Operating Simulator*. Software project.

---

## 🗺️ Roadmap

Planned development areas include:

- Expanded Python curriculum
- More languages
- Teacher lesson packs
- Student exercises and assessments
- More data-science notebooks
- Classroom / instructor mode
- Accessibility improvements
- Offline-friendly deployment options
- Expanded live learning library

See [`ROADMAP.md`](ROADMAP.md).

---

## 🐛 Found a Problem?

Please use the GitHub **Issues** tab and select the most appropriate issue template.

For security-sensitive reports, follow [`SECURITY.md`](SECURITY.md) instead of publishing exploit details in a public issue.

---

## 👨‍🏫 Creator and Project Lead

**Dr. Yash Munnalal Gupta**  
Creator and Project Lead — EDOS  

🌐 **Project:** https://yashmgupta.github.io/EDOS-Python-Learning-Desktop/

---

## ⭐ Support EDOS

Try EDOS online: **https://yashmgupta.github.io/EDOS-Python-Learning-Desktop/**

If EDOS is useful in your classroom, institution, workshop, or research:

- ⭐ Star the repository
- 📢 Share the official project page
- 🐛 Report reproducible bugs
- 📚 Propose educational materials
- 🌍 Help improve translations
- 🤝 Collaborate through the official repository

**EDOS — Learn Python. Experiment safely. No installation required.**
