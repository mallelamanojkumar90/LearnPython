# LearnPython

A collection of Jupyter Notebooks for learning Python — from fundamentals to practical examples and data analysis.

Repository language: Jupyter Notebook (100%).

## Contents

This repository contains self-contained Jupyter Notebook lessons and exercises that demonstrate Python concepts, data manipulation, visualization, and simple machine learning examples. Notebooks are located in the repository root and (if present) any subfolders.

## Quick start

Prerequisites:
- Python 3.8 or newer
- pip

Recommended setup:

```bash
python -m venv .venv
# macOS / Linux
source .venv/bin/activate
# Windows (PowerShell)
.\.venv\Scripts\Activate.ps1

pip install --upgrade pip
# If a requirements.txt file exists in the repository, use it:
# pip install -r requirements.txt
# Otherwise, install common packages for the notebooks:
pip install jupyterlab notebook numpy pandas matplotlib seaborn scikit-learn
```

Run the notebooks:

```bash
jupyter lab
# or
jupyter notebook
```

Open any .ipynb file in your browser to view and run the lessons.

## Viewing without running

You can preview notebooks directly on GitHub or with the free nbviewer service:

- GitHub: https://github.com/mallelamanojkumar90/LearnPython
- NBViewer: https://nbviewer.org/github/mallelamanojkumar90/LearnPython

## Contributing

Contributions are welcome!

- Fork the repository and create a branch for your changes.
- Add or improve notebooks, add documentation or examples.
- Clear large output cells before committing to keep diffs small (use "Kernel > Restart & Clear Output").
- Open a pull request describing your changes.

## License

If a LICENSE file is present in this repository, that file governs how the content may be used. If there is no LICENSE yet, please add one (for example, the MIT license) to make reuse and contribution terms clear.

## Issues and support

If you find problems or have suggestions, please open an issue on this repository.

---

Updated README to reflect that this repository contains Jupyter Notebooks and to provide setup and contribution guidance.
