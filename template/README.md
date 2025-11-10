# {{ package_name }}

A minimal Python project template.

## What's Included?

This project is set up with a suite of modern, high-performance tools, all configured to work together seamlessly:

- **`uv` for Project & Dependency Management:** Used to manage the project's virtual environment and dependencies, all defined in `pyproject.toml`.
- **`ruff` for Linting & Formatting:** The included VS Code settings (`.vscode/settings.json`) will automatically format your code on save.
- **`basedpyright` for Type Checking:** A fast, powerful type checker to help you write clean, type-safe code.
- **`pytest` for Testing:** The standard for testing in Python.
- **`make` for Common Tasks:** A simple `Makefile` is included with commands for common tasks:
    - `make install`: Sets up the virtual environment and installs all dependencies.
    - `make lint`: Runs the linter and formatter.
    - `make test`: Runs the test suite.

## Getting Started

1.  **Install dependencies:** `make install`
2.  **Start coding!** Your VS Code environment is already configured.
