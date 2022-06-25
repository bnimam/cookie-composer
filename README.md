# Cookie Composer

Cookie composer builds on the [cookie cutter](https://github.com/cookiecutter/cookiecutter) project to generate projects based on one or more cookiecutter templates.

## Goals

- Create new projects from a composition of several templates
- Add new capabilities to an existing repository by applying a template
- Apply template updates to the generated project


## Purpose

- Separate out parts to a repo into composable templates
  - Boilerplate
    - README, CONTRIBUTING, docs, Makefile, license, tooling configurations
  - Project-specific
    - Django
    - Flask
    - Library
    - Data science
  - CI/CD specific
    - Helm chart
    - GitHub Actions vs. Jenkins vs. ...
  - Documentation specific
    - Sphinx
    - MkDocs
- Each composable template is managed and updated individually
- A project can update itself based on chages in layers


## Please contribute

- Documentation critiques
- Documentation suggestions
- Feature suggestions
- Feature improvements
- Edge case identification
- Code improvements
