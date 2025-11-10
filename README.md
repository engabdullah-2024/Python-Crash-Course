# Python Crash Course

A companion repository for a hands-on **Python Crash Course** — lessons, exercises, and small projects to take you from beginner to confident Python programmer.

---

## Table of contents

1. [About](#about)
2. [Prerequisites](#prerequisites)
3. [Repository structure](#repository-structure)
4. [Setup / Installation](#setup--installation)
5. [How to use this repo](#how-to-use-this-repo)
6. [Lesson list & learning path](#lesson-list--learning-path)
7. [Exercises & Projects](#exercises--projects)
8. [Testing](#testing)
9. [Contributing](#contributing)
10. [License](#license)
11. [Author / Contact](#author--contact)

---

## About

This repository contains curated notes, short examples, and exercise files for a compact, practical **Python Crash Course**. It's designed for learners who want to quickly build the fundamentals and practice with small real-world problems.

The course favors **readable examples**, short exercises, and 3–5 small projects that reinforce the concepts.

---

## Prerequisites

* Basic computer knowledge (files, terminal/command line)
* Python 3.10+ installed (recommended). Use `python --version` to check.
* Git (optional, for cloning the repo)

---

## Repository structure

```
Python-Crash-Course/
├─ README.md
├─ requirements.txt
├─ .gitignore
├─ lessons/
│  ├─ 01-intro/
│  ├─ 02-control-flow/
│  ├─ 03-functions/
│  ├─ 04-data-structures/
│  ├─ 05-modules-packages/
│  ├─ 06-file-io/
│  ├─ 07-errors-exceptions/
│  ├─ 08-classes-objects/
│  ├─ 09-virtualenv-pip/
│  └─ 10-testing/
├─ exercises/
│  ├─ beginner/
│  ├─ intermediate/
│  └─ challenge-projects/
└─ projects/
   ├─ todo-cli/
   ├─ calculator/
   └─ web-scraper/
```

Each lesson folder contains a short `README.md` and 1–3 example `.py` files.

---

## Setup / Installation

Clone the repository (if you haven't):

```bash
git clone https://github.com/engabdullah-2024/Python-Crash-Course.git
cd Python-Crash-Course
```

Create a virtual environment and install dependencies (optional but recommended):

```bash
python -m venv .venv
# Windows
.venv\Scripts\activate
# macOS / Linux
source .venv/bin/activate

pip install -r requirements.txt
```

If you don't want a virtual env, you can run files directly with `python lessons/01-intro/example.py`.

---

## How to use this repo

1. Pick a lesson folder (start with `01-intro`).
2. Read the `README.md` inside the lesson folder.
3. Run the example files with `python example.py` and step through the code.
4. Do the exercises in the `exercises/` folder.
5. Attempt at least one project from `projects/` once you're comfortable.

---

## Lesson list & learning path

Suggested flow (fast crash course — roughly 1–2 days per module depending on practice time):

1. **Intro** — hello world, `print()`, `input()`, basic types
2. **Control flow** — `if`, `elif`, `else`, loops (`for`, `while`)
3. **Functions** — defining, parameters, return values, scope
4. **Data structures** — lists, tuples, sets, dicts
5. **Modules & packages** — `import`, `pip`, third-party libs
6. **File I/O** — reading/writing files, working with CSV/JSON
7. **Errors & exceptions** — `try/except`, raising exceptions
8. **OOP** — classes, objects, methods, inheritance
9. **Virtualenv & packaging** — `venv`, `requirements.txt`
10. **Testing** — `unittest` or `pytest` basics

---

## Exercises & Projects

### Beginner exercises

* Sign checker (positive/negative/zero)
* Age categorizer (child/adult/senior)
* Simple calculator (add, subtract, multiply, divide)

### Intermediate

* To-do CLI with file persistence (JSON)
* Simple web scraper (requests + BeautifulSoup)
* CSV data summarizer

### Challenge projects

* CLI note-taking app with search
* A mini REST API using Flask or FastAPI
* Small GUI using Tkinter

Each exercise folder includes instructions and test cases where appropriate.

---

## Testing

Basic tests live in `lessons/10-testing/` and in each exercise where applicable. Run tests with:

```bash
python -m unittest discover -v
# or, if using pytest
pytest -q
```

---

## Contributing

Contributions welcome! Suggested workflow:

1. Fork the repo
2. Create a feature branch `git checkout -b feat/your-topic`
3. Add lesson / exercise / fix
4. Commit and push
5. Create a pull request with description of changes

Please keep code simple and well-documented. Add tests when relevant.

---

## .gitignore (suggested)

```
__pycache__/
.venv/
.env
*.pyc
.DS_Store
```

---

## requirements.txt (suggested minimal)

```
requests
beautifulsoup4
pytest
```

---

## License

This repository is offered under the **MIT License**. See `LICENSE` for details.

---

## Author / Contact

**Eng Abdalla** — GitHub: [https://github.com/engabdullah-2024](https://github.com/engabdullah-2024)

If you'd like, I can also:

* generate `LICENSE`, `.gitignore`, `requirements.txt`, and starter lesson files,
* create example exercises (with test cases), or
* produce a GitHub Actions workflow for running tests automatically.

Tell me which extras you want and I will add them to the repo.
