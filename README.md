# py-scaffold

[![Python](https://img.shields.io/badge/python-3.12+-blue.svg)](https://www.python.org/downloads/)
[![PyPI](https://img.shields.io/pypi/v/package_name.svg)](https://pypi.org/project/package_name/)
[![codecov](https://codecov.io/gh/skethirajan/py-scaffold/graph/badge.svg?token=dl0U9dYIj6)](https://codecov.io/gh/skethirajan/py-scaffold)
[![Ruff](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json)](https://github.com/astral-sh/ruff)
[![Pyrefly](https://img.shields.io/badge/pyrefly-checked-blueviolet)](https://github.com/NoneGG/pyrefly)
[![Pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit)](https://github.com/pre-commit/pre-commit)
[![MkDocs](https://img.shields.io/badge/docs-mkdocs-blue.svg)](https://www.mkdocs.org/)
[![License](https://img.shields.io/badge/license-BSD--3--Clause-green.svg)](LICENSE)

A minimal scaffold for building modern, reproducible scientific Python packages.

## Create your own python package with this template

Use this template to create your own repo, ```my_project```. Then clone your ```my_project``` repo and run the initialization script to automatically rename everything:

```bash
# Clone the template
git clone https://github.com/<user_name>/my_project.git
cd my_project

# Run the init script
python scripts/init_project.py
```

The script will interactively prompt you for:
- Package name
- Description
- Author name and email
- GitHub username

After that you can delete the init script.

```bash
# Delete the init script
rm -rf scripts/init_project.py
```

## 📦 Features

- Quick project initialization with modern tools & best practices
- Easy to extend this template to your needs

## 🚀 Getting Started

| Resource        | Link                                                                                   |
|-----------------|----------------------------------------------------------------------------------------|
| 👉 Installation Guide | [Installation Guide](docs/getting-started/installation.md) |
| 🧑‍💻 Developer Guide | [Developer Guide](docs/CONTRIBUTING.md) |

---
