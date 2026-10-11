# Contributing to the Mergington High Extra-Curricular Activities Website

Thank you for helping improve this GitHub Skills exercise! This repository is a training copy of the fictional school's application. Use the included sample data, never real student information.

## Development setup

1. Clone this repository and create a Python virtual environment.
2. Install the requirements with `python -m pip install -r requirements.txt`.
3. Start a local MongoDB instance on `localhost:27017`, as expected by `src/backend/database.py`.
4. From the repository root, run `python -m uvicorn src.app:app --reload`.
5. Visit `http://localhost:8000` and use only the training data.

The repository also includes a development container and a VS Code launch configuration. Running the application is optional for this repository-management exercise.

## Making changes

1. Create a descriptive branch, such as `fix-chess-signup`.
2. Make a focused change and test the affected behavior with sample data.
3. Keep credentials, environment files, and generated files out of Git.
4. Push the branch and open a pull request explaining the behavior and checks.
5. Address review feedback before merging; changes to `main` go through pull requests.

## Code style

- Follow PEP 8 for Python and the surrounding style for JavaScript and HTML.
- Use descriptive names and comments that explain non-obvious decisions.
- Keep changes scoped and avoid unrelated formatting.

## Getting help

Search existing issues first. If your question is new, open an issue with context and steps to reproduce. Use the security policy for private vulnerability reports.
