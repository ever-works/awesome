# Awesome Python Typing

Awesome Python Typing is a curated, community-maintained directory of tools, libraries, learning resources, and ecosystem projects related to optional static typing in Python.

## Overview

- **Type**: Open-source curated list (Awesome list)
- **Focus**: Python type hints, static and dynamic type checking, stubs, plugins, and tooling
- **Source**: [GitHub – typeddjango/awesome-python-typing](https://github.com/typeddjango/awesome-python-typing#readme)

## Features

### 1. Static Type Checkers
- Directory of static type checkers for Python (e.g., tools that analyze code using type hints without executing it).
- Focuses on tools that integrate with modern `typing` features and type annotations.

### 2. Dynamic Type Checkers
- Collection of tools that validate types at runtime.
- Aimed at enforcing or experimenting with types during execution rather than only at analysis time.

### 3. Stub Packages
- List of third‑party type stub packages (`*.pyi`) for libraries that may not ship with built‑in type hints.
- Helps developers find typings for popular packages so static checkers can provide better analysis.

### 4. Additional Types
- Resources and libraries providing additional or enhanced type definitions beyond the standard library.
- Includes references such as:
  - `collections.abc`
  - `operators`

### 5. Backports and Improvements
- Libraries and tools that backport newer typing features to older Python versions or extend existing typing capabilities.
- Example concept mentioned: the union type operator syntax `X | Y`.

### 6. Tools and Utilities
- Aggregated tools to improve working with type hints and type‑driven development in Python, including:

#### Linters
- Linters that understand type annotations and can use them to provide more accurate diagnostics.

#### Testing
- Testing tools and frameworks that integrate with type information (e.g., for generating tests or validating types during test runs).

#### Working with Types
- Utilities specifically for manipulating and inspecting types, centered around the `typing` module and related constructs.

#### Helper Tools to Add Annotations
- Tools aimed at adding or inferring type annotations in existing codebases.
- Section explicitly covers "Helper tools to add annotations to existing code" (even if a placeholder `None` is currently listed, it’s part of the structure and scope).

#### Mypy Plugins
- Collection of plugins that extend or customize the behavior of the `mypy` static type checker.
- Useful for framework-specific typing (e.g., Django, etc.) and advanced type system extensions.

### 7. Integrations
- Resources for integrating typing and type-checking tools into editors, IDEs, CI/CD pipelines, and other development workflows.

### 8. Articles and Learning Resources
- **PEPs**: Links to Python Enhancement Proposals that define and evolve the typing system (e.g., features like `Final`, `Literal`, `PEP612`, and broader `typing` changes).
- **Third‑party articles**: Blog posts, guides, and external documentation explaining:
  - `Final`
  - `Literal`
  - `typing` module usage
  - `PEP612` (parameter specification variables) and other advanced typing features.

### 9. Related Projects
- Section for related repositories, lists, or ecosystems around Python typing and type‑safe Python development.

### 10. Contribution Guidelines
- `contributing.md` provides instructions for adding new tools, libraries, or resources to the list.
- Encourages community contributions to keep the directory up to date.

### 11. Licensing
- A `LICENSE` file is present in the repository, indicating the list’s open-source licensing terms (exact license text is available in the repository).

## Pricing

- **Cost**: Free
- **Model**: Open-source GitHub repository; no paid plans or pricing tiers.

## Categories

- **Directory Category**: Themed Directories
- **Tags**: `awesome-lists`, `python`, `developer-tools`