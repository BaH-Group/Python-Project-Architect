# Python Project Architect Gemini CLI extension

This repository is a Gemini CLI extension that provides custom slash commands for creating and managing Python projects.

## Features

- **Interactive Scaffolding**: Choose from various project templates via multiple-choice questions.
- **Automated Environment Setup**: Automatically creates and configures a virtual environment (`venv`).
- **Dependency Management**: Generates `requirements.txt` and installs necessary packages like `python-dotenv`.
- **Pre-configured Git**: Sets up a comprehensive `.gitignore` for Python development.
- **Environment Configuration**: Optional `.env` file generation for secure environment variable management.

## Installation

**Local Installation:**

1. Clone the repository:
   ```bash
   git clone https://github.com/BaH-Group/python-project-architect.git
   ```

2. Navigate to the project directory:
   ```bash
   cd python-project-architect
   ```

3. Link the extension to Gemini CLI:
   ```bash
   gemini link .
   ```

## Global Installation:

To install the extension globally from the repository:

```bash
gemini extension install https://github.com/BaH-Group/python-project-architect.git
```

## Update

To update the extension to the latest version, use:

```bash
gemini extensions update python-project-architect
```

Or to update all extensions:

```bash
gemini extensions update --all
```

## Uninstallation

To uninstall the extension, use the following command:

```bash
gemini extensions uninstall python-project-architect
```

If you installed it locally using `gemini link .`, you can also use:

```bash
gemini unlink .
```
