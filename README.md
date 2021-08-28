![tests](https://github.com/kevinhowbrook/python-template/workflows/Tests/badge.svg)
[![codecov](https://codecov.io/gh/kevinhowbrook/python-template/branch/main/graph/badge.svg?token=9Z56AJCFTT)](https://codecov.io/gh/kevinhowbrook/python-template)
[![black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

# Python Template

_A starter template for a python project_

## What's included?

### Poetry

A pyproject.toml file to run this project on poetry.

### Fabfile

For ease of running certain tasks, like `fab run-tests`

### Coverage

A .coveragerc file for running reports on test coverage

### Github actions

- Run tests
- Run coverage
- Upload coverage reports

#### Precommit

A precommit.yaml file with the following:

- Black
- isort
- flake8
- prettier
- secret detection

## Configuration

### Coverage

Add your [codecov](https://app.codecov.io) token as a GitHub secret (repo > settings > secrets) with the var name `CODE_COV_KEY`
