---

# 🛠️ Development Setup

This repository uses **pre-commit** to automatically check Markdown, Python, YAML, JSON, shell scripts, and other files before each commit.

## Install

```bash
pip install pre-commit
```

## Enable Git Hooks

```bash
pre-commit install
```

## Run All Checks

```bash
pre-commit run --all-files
```

Once installed, the hooks will run automatically every time you execute:

```bash
git commit
```

This helps maintain consistent formatting, catch common mistakes early, and keep the repository clean and professional.
````
