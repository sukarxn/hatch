# Hatch

<div align="center">

<img src="https://raw.githubusercontent.com/pypa/hatch/master/docs/assets/images/logo.svg" alt="Hatch logo" width="500" role="img">

| | |
| --- | --- |
| CI/CD | [![CI - Test](https://github.com/pypa/hatch/actions/workflows/test.yml/badge.svg)](https://github.com/pypa/hatch/actions/workflows/test.yml) [![CD - Build Hatch](https://github.com/pypa/hatch/actions/workflows/build-hatch.yml/badge.svg)](https://github.com/pypa/hatch/actions/workflows/build-hatch.yml) [![CD - Build Hatchling](https://github.com/pypa/hatch/actions/workflows/build-hatchling.yml/badge.svg)](https://github.com/pypa/hatch/actions/workflows/build-hatchling.yml) |
| Docs | [![Docs - Release](https://github.com/pypa/hatch/actions/workflows/docs-release.yml/badge.svg)](https://github.com/pypa/hatch/actions/workflows/docs-release.yml) [![Docs - Dev](https://github.com/pypa/hatch/actions/workflows/docs-dev.yml/badge.svg)](https://github.com/pypa/hatch/actions/workflows/docs-dev.yml) |
| Package | [![PyPI - Version](https://img.shields.io/pypi/v/hatch.svg?logo=pypi&label=PyPI&logoColor=gold)](https://pypi.org/project/hatch/) [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/hatch.svg?logo=python&label=Python&logoColor=gold)](https://pypi.org/project/hatch/) [![PyPI - Installs](https://img.shields.io/pypi/dm/hatchling.svg?color=blue&label=Installs&logo=pypi&logoColor=gold)](https://pypi.org/project/hatch/) [![Release - Downloads](https://img.shields.io/github/downloads/pypa/hatch/total?label=Downloads)](https://github.com/pypa/hatch/releases) |
| Meta | [![Hatch project](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/pypa/hatch/master/docs/assets/badge/v0.json)](https://github.com/pypa/hatch) [![linting - Ruff](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json)](https://github.com/astral-sh/ruff) [![types - Mypy](https://img.shields.io/badge/types-Mypy-blue.svg)](https://github.com/python/mypy) [![License - MIT](https://img.shields.io/badge/license-MIT-9400d3.svg)](https://spdx.org/licenses/) [![GitHub Sponsors](https://img.shields.io/github/sponsors/ofek?logo=GitHub%20Sponsors&style=social)](https://github.com/sponsors/ofek) |

</div>

-----

Hatch is a modern, extensible Python project manager.

## Overview

Hatch is an all-in-one tool for Python developers that covers the entire project lifecycle — from creating a new project and managing dependencies to running tests, enforcing code quality, and publishing releases.

At its core, Hatch provides:

- **Project scaffolding:** Generate new Python projects with a standard layout and best-practice configuration using `hatch new`.
- **Build backend (Hatchling):** A [PEP 517](https://peps.python.org/pep-0517/)-compliant build backend that produces reproducible wheels and source distributions by default, with a clean plugin system for advanced customization.
- **Environment management:** Create and manage isolated virtual environments for development, testing, or any other purpose, with support for multiple Python versions and named run scripts.
- **Python distribution management:** Download and manage CPython (and other) distributions without relying on system-installed Python versions.
- **Test runner:** Run tests across multiple environments with sensible defaults, using frameworks such as pytest.
- **Static analysis:** Lint and format your code via a built-in integration with [Ruff](https://github.com/astral-sh/ruff), kept current with maintained defaults.
- **Script runner:** Execute standalone Python scripts that declare their own dependencies inline.
- **Version management:** Bump and synchronize version strings across your project from a single command.
- **Publishing:** Upload built distributions to PyPI or any other compatible index with `hatch publish`.

Hatch is designed so that adopting its full feature set eliminates the need for a collection of separate tools (setuptools, tox/nox, pyenv, twine, bump2version, etc.). Individual features can also be adopted incrementally if you prefer to keep parts of an existing workflow.

## Features

- Standardized [build system](https://hatch.pypa.io/latest/config/build/#build-system) with reproducible builds by default
- Robust [environment management](https://hatch.pypa.io/latest/environment/) with support for custom scripts and UV
- Configurable [Python distribution management](https://hatch.pypa.io/latest/tutorials/python/manage/)
- [Test execution](https://hatch.pypa.io/latest/tutorials/testing/overview/) with known best practices
- [Static analysis](https://hatch.pypa.io/latest/config/static-analysis/) with sane defaults
- Built-in Python [script runner](https://hatch.pypa.io/latest/how-to/run/python-scripts/)
- Easy [publishing](https://hatch.pypa.io/latest/publish/) to PyPI or other indices
- [Version](https://hatch.pypa.io/latest/version/) management
- Best practice [project generation](https://hatch.pypa.io/latest/config/project-templates/)
- Responsive [CLI](https://hatch.pypa.io/latest/cli/about/), ~2-3x [faster](https://github.com/pypa/hatch/actions/workflows/cli.yml) than equivalent tools

See the [Why Hatch?](https://hatch.pypa.io/latest/why/) page for more information.

## Documentation

The [documentation](https://hatch.pypa.io/) is made with [Material for MkDocs](https://github.com/squidfunk/mkdocs-material) and is hosted by [GitHub Pages](https://docs.github.com/en/pages).

## License

Hatch is distributed under the terms of the [MIT](https://spdx.org/licenses/MIT.html) license.
