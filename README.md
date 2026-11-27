# DevOps Core Tooling

![Build Status](https://github.com/Sreevalli20/devops-core-tooling/actions/workflows/ci.yml/badge.svg)
![License](https://img.shields.io/badge/License-MIT-blue.svg)

## Project Overview

DevOps Core Tooling is a Python-based project demonstrating Git version control, collaborative development, automated testing, and CI/CD practices using GitHub Actions.

## Architecture Overview

The project follows a simple development and automation workflow:

Developer -> Git Repository -> GitHub -> GitHub Actions -> Automated Testing

## Technologies Used

- Git
- GitHub
- Python 3.11
- GitHub Actions
- Flake8
- Pytest

## Project Structure

devops-core-tooling/
|
|-- .github/
|   |-- workflows/
|       |-- ci.yml
|
|-- main.py
|-- dashboard.py
|-- config.py
|-- test_main.py
|-- requirements.txt
|-- README.md
|-- CHANGELOG.md
|-- .gitignore

## Installation

1. Clone the repository:

   git clone https://github.com/Sreevalli20/devops-core-tooling.git

2. Navigate to the project directory:

   cd devops-core-tooling

3. Install Python dependencies:

   pip install -r requirements.txt

## Environment Setup

Python 3.11 or later is recommended.

Create a virtual environment:

   python -m venv venv

Activate it in Git Bash:

   source venv/Scripts/activate

## Usage

Run the main application:

   python main.py

Run the dashboard module:

   python dashboard.py

## Testing

Run unit tests:

   pytest

Run code quality checks:

   flake8 .

## CI/CD Pipeline

GitHub Actions automatically runs Python linting and unit tests when code is pushed to main or a Pull Request targets main.

## Contribution Guidelines

1. Create a feature branch.
2. Make your changes.
3. Test your code.
4. Commit changes with descriptive messages.
5. Push your branch to GitHub.
6. Create a Pull Request.
7. Address reviewer feedback before merging.

## Code of Conduct

All contributors should communicate respectfully, collaborate professionally, and maintain a welcoming development environment.

## License

This project is licensed under the MIT License.
