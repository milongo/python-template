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

## Dev Containers

This repository supports the use of development containers to streamline your development environment setup. By leveraging Docker and Visual Studio Code's Remote - Containers extension, you can work in a consistent environment that includes all necessary dependencies and tools.

### Getting Started with Dev Containers

1. Prerequisites:
   - Ensure you have Docker installed on your machine.
   - Install Visual Studio Code and the Remote - Containers extension.

2. Using the Dev Container:
   - Open this repository in Visual Studio Code.
   - Once the workspace is open, you should see a prompt to reopen the folder in a container. Click on "Reopen in Container."
   - Visual Studio Code will build the dev container defined in the `.devcontainer` directory, which may include setting up the environment specified in `environment.yml`.

3. Using the Development Environment:
   - Once the container is running, you can access a terminal within VS Code to run your Python scripts using the specified environment.
   - All code quality tools and testing frameworks will be available as defined in the `environment.yml` and configured in the `devcontainer.json` file.

4. Stopping the Dev Container:
   - To stop the container, you can either close Visual Studio Code or use the command palette (Ctrl+Shift+P) and select "Remote-Containers: Rebuild Container" or "Remote-Containers: Close Remote Connection" as needed.
