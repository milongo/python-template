# Contributing to Template Repository

## Code Standards

To maintain a consistent code quality, we follow specific coding standards and tools outlined below:

### Python Code Style

- PEP 8 Compliance: Code should adhere to the PEP 8 style guide. Use `flake8` as a linter to check for style violations.
- Line Length: Maximum line length is set to **90 characters** as per our `.flake8` and `pyproject.toml` configurations.
```

### Code Formatting

- Black: We use `black` as the formatter. It will automatically format your code according to its opinionated style. The line length is also set to 90 characters.

### Import Sorting
- isort: Ensure that imports are sorted correctly using isort.

### Linting
- Pylint: Use `pylint` as a linter to check for potential errors in your code.

### Testing
- Testing Framework: We use pytest for running tests. Please make sure to write tests for any new functionality or bug fixes you introduce.
- Test Coverage: Aim for at least 95% test coverage as configured in pyproject.toml. You can check the coverage report after running your tests.
