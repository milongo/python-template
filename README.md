# Template Repository

This repository serves as a template for initializing new Python projects. It includes a configured development environment and essential tools for maintaining code quality.

## Environment Setup

To set up the development environment, use the provided `environment.yml` file. It includes the following dependencies:

- Python 3.12
- Code Quality Tools
  - `pylint`: A static code analyzer for Python.
  - `flake8`: A tool for enforcing coding style based on PEP 8.
  - `isort`: A utility for sorting imports.
  - `black`: An opinionated code formatter for Python.
- Testing Framework
  - `pytest`: A framework that makes building simple and scalable test cases easy.
  - `pytest-cov`: A plugin for measuring test coverage.

## Getting Started

To create the environment, replace the `{ { template } }` in the `environment.yml` file with an appropiate name for your environment and run the following command:

```bash
conda env create -f environment.yml
```

To activate the environment, run the following command:
```bash
conda activate { { template } }
```

Replace `{ { template } }` with the name specified in the `environment.yml` file.
