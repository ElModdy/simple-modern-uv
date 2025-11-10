# Minimal Python Project Template for VS Code

This is a minimal, modern Python project template for new projects, optimized for VS Code. It is designed to be a simple, straightforward starting point for any project, with all the essential tools pre-configured.

## What's Included?

This template comes with a suite of modern, high-performance tools, all configured to work together seamlessly:

- **`uv` for Project & Dependency Management:** An extremely fast Python package installer and resolver, used to manage the project's virtual environment and dependencies.
- **`ruff` for Linting & Formatting:** An extremely fast Python linter and code formatter. The included VS Code settings will automatically format your code on save.
- **`basedpyright` for Type Checking:** A fast, powerful type checker to help you write clean, type-safe code.
- **`pytest` for Testing:** The standard for testing in Python.
- **`make` for Common Tasks:** A simple `Makefile` is included with commands for common tasks like installing dependencies, running the linter, and running tests.
- **VS Code Integration:** The included `.vscode/settings.json` file configures VS Code to use all these tools automatically, providing a seamless development experience.
- **GitHub Copilot Instructions:** A `.github/copilot-instructions.md` file is included to guide GitHub Copilot in understanding and contributing to your project.

## How to Use

This template uses [Copier](https://github.com/copier-org/copier). To create a new project:

```shell
# 1. Install Copier if you don't have it
uv tool install copier

# 2. Create a new project from the template
copier copy gh:ElModdy/simple-modern-uv YOUR_NEW_PROJECT_NAME
```

Copier will prompt you for a project name.

> **Note:** This template sets up a standard Python project (which is technically a "package"), but this does not mean it has to be published to PyPI.

Once the project is created, navigate into the directory and run:

```shell
make install
```

This will set up the virtual environment and install all dependencies.
