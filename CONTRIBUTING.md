# Contributing to NEX

Thank you for your interest in contributing to NEX! :tada:

## Table of Contents
1. [How to Contribute](#how-to-contribute)
2. [Code of Conduct](#code-of-conduct)
3. [Reporting Issues](#reporting-issues)
4. [Submitting Pull Requests](#submitting-pull-requests)
5. [Development Workflow](#development-workflow)

## How to Contribute
- **Issues**: Found a bug or have a feature request? Check existing issues or open a new one.
- **Code**: Fork the repo, create a feature branch, and submit a PR.
- **Docs**: Help improve documentation (README, ROADMAP, etc.).

## Code of Conduct
This project adheres to the [Contributor Covenant](https://www.contributor-covenant.org/). Please read the full [Code of Conduct](CODE_OF_CONDUCT.md) before participating.

## Reporting Issues
- Search existing issues to avoid duplicates.
- Use the issue template and include:
  - A clear title and description
  - Steps to reproduce (for bugs)
  - Expected vs. actual behavior
  - Any relevant logs or screenshots

## Submitting Pull Requests
1. Fork the repository and create a branch (`git checkout -b feature/foo`).
2. Commit your changes (`git commit -m 'Add foo feature'`).
3. Push to your fork (`git push origin feature/foo`).
4. Open a pull request against the `main` branch.

### PR Guidelines
- Follow the existing coding style.
- Write clear commit messages.
- Include tests for new functionality.
- Link related issues in the PR description.

## Development Workflow
```bash
# Clone and setup
git clone https://github.com/awanicaleb/nex.git
cd nex
python -m venv venv && source venv/bin/activate
pip install -r requirements.txt

# Run tests
pytest

# Linting
flake8