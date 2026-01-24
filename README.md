# package_name

A minimal scaffold for building modern, reproducible scientific Python packages.

[![Python 3.12+](https://img.shields.io/badge/python-3.12+-blue.svg)](https://www.python.org/downloads/)
[![License](https://img.shields.io/badge/license-BSD--3--Clause-green.svg)](LICENSE)
[![Ruff](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json)](https://github.com/astral-sh/ruff)

## Features

- 🚀 **Modern Python** — Python 3.12+ with `from __future__ import annotations`
- 📦 **Hatchling** — Fast, modern build backend
- 🔍 **Ruff** — Lightning-fast linting and formatting
- 🔬 **Pyrefly** — Next-generation type checking
- 📖 **MkDocs Material** — Beautiful documentation with auto-generated API reference
- ✅ **pytest** — Testing with coverage support
- 🔧 **Pre-commit** — Git hooks for code quality
- ⚡ **uv** — Recommended for fast package management

## Quick Start

```bash
# Clone the repository
git clone https://github.com/username/package_name.git
cd package_name

# Using uv (recommended)
uv venv .venv && source .venv/bin/activate
uv pip install -e ".[dev]"

# Or using pip
python -m venv .venv && source .venv/bin/activate
pip install -e ".[dev]"
```

For detailed setup instructions (including HPC environments), see the [Developer Guide](docs/developer-guide.md).

### Development Commands

```bash
pytest                      # Run tests
ruff check . && ruff format # Lint and format
pyrefly check               # Type check
mkdocs serve                # Build docs
```

## Project Structure

```
package_name/
├── src/
│   └── package_name/
│       ├── __init__.py
│       └── py.typed
├── tests/
│   ├── __init__.py
│   └── test_package.py
├── docs/
│   ├── index.md
│   ├── changelog.md
│   ├── gen_ref_pages.py
│   └── getting-started/
│       ├── installation.md
│       └── quickstart.md
├── pyproject.toml
├── mkdocs.yml
├── LICENSE
├── README.md
└── CHANGELOG.md
```

## Using This Template

### Option 1: Automated (Recommended)

Run the initialization script to automatically rename everything:

```bash
# Clone the template
git clone https://github.com/username/py-scaffold.git my_new_package
cd my_new_package

# Run the init script
python scripts/init_project.py
```

The script will interactively prompt you for:
- Package name
- Description
- Author name and email
- GitHub username

### Option 2: Manual

1. **Replace placeholders** in all files:
   - `package_name` → your package name
   - `username` → your GitHub username
   - `Your Name` → your name
   - `you@example.com` → your email

2. **Rename the source directory**:
   ```bash
   mv src/package_name src/your_package_name
   ```

3. **Update imports** in test files and documentation

4. **Delete the scripts directory**:
   ```bash
   rm -rf scripts/
   ```

## License

This project is licensed under the BSD-3-Clause License - see the [LICENSE](LICENSE) file for details.
