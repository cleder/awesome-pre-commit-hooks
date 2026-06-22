# Awesome Pre-commit Hooks

A curated collection of [pre-commit](https://pre-commit.com) and [prek](https://github.com/j178/prek/) hooks, organized by language and framework.

_Auto-generated from [pc-init](https://github.com/cleder/gpc-init) presets — to add or update a hook, open a PR there rather than editing this file directly._

## Contents

- [Common](#common)
- [Languages](#languages)
  - [go](#go)
  - [js](#js)
  - [md](#md)
  - [py](#py)
  - [ru](#ru)
  - [toml](#toml)
  - [yaml](#yaml)
- [Frameworks](#frameworks)
  - [bevy](#bevy)
  - [django](#django)
  - [react](#react)
  - [sphinx](#sphinx)

---

## Common

> Applied to every generated configuration, regardless of language or framework.

- **meta**
- [pre-commit-hooks](https://github.com/pre-commit/pre-commit-hooks) — Some out-of-the-box hooks for pre-commit
- [pre-commit-sort](https://github.com/nim65s/pre-commit-sort) — Sort .pre-commit-config.yaml & .pre-commit-hooks.yaml
- [typos](https://github.com/crate-ci/typos) — Source code spell checker

---

## Languages

### go

- [pre-commit-golang](https://github.com/tekwizely/pre-commit-golang) — Pre-commit hooks for Golang with support for monorepos, the ability to pass arguments and environment variables to all hooks, and the ability to invoke custom go tools.

### js

- **local**
- [typos](https://github.com/crate-ci/typos) — Source code spell checker

### md

- [rumdl-pre-commit](https://github.com/rvben/rumdl-pre-commit) — Pre-commit hook for rumdl, a rust-based Markdown linter.
- [typos](https://github.com/crate-ci/typos) — Source code spell checker

### py

- [absolufy-imports](https://github.com/MarcoGorelli/absolufy-imports) — Automatically convert relative imports to absolute
- [blacken-docs](https://github.com/adamchainz/blacken-docs) — Run `black` on python code blocks in documentation files
- [complexipy-pre-commit](https://github.com/rohaquinlop/complexipy-pre-commit) — A pre-commit hook for complexipy.
- [pyprojectsort](https://github.com/kieran-ryan/pyprojectsort) — Formatter for pyproject.toml files
- [pyrefly-pre-commit](https://github.com/facebook/pyrefly-pre-commit) — A pre-commit hook for Pyrefly.
- [removestar](https://github.com/asmeurer/removestar) — Tool to automatically replace 'import *' in Python files with explicit imports
- [ruff-pre-commit](https://github.com/astral-sh/ruff-pre-commit) — A pre-commit hook for Ruff.
- [ty-pre-commit](https://github.com/astral-sh/ty-pre-commit) — A pre-commit hook for ty.
- [uv-pre-commit](https://github.com/astral-sh/uv-pre-commit)
- [validate-pyproject](https://github.com/abravalheri/validate-pyproject) — Validation library for simple check on `pyproject.toml`

### ru

- [pre-commit-rust](https://github.com/doublify/pre-commit-rust) — Rust hooks for pre-commit
- [typos](https://github.com/crate-ci/typos) — Source code spell checker

### toml

_No hooks defined yet._

### yaml

- [ryl-pre-commit](https://github.com/owenlamont/ryl-pre-commit) — Pre-commit hook for ryl

---

## Frameworks

### bevy

> Primary language(s): ru.

- [nickel-pre-commit](https://github.com/nickel-lang/nickel-pre-commit)

### django

> Primary language(s): py.

- [django-codemod](https://github.com/browniebroke/django-codemod) — A tool to automatically fix Django deprecations.
- [django-upgrade](https://github.com/adamchainz/django-upgrade) — Automatically upgrade your Django projects.
- [django-urlconfchecks](https://github.com/AliSayyah/django-urlconfchecks) — A package for type-checking the URLs and associated views for Django
- [djLint](https://github.com/djlint/djLint) — ✨ HTML Template Linter and Formatter. Django - Jinja - Nunjucks - Handlebars - GoLang
- [pre-commit-hooks](https://github.com/pre-commit/pre-commit-hooks) — Some out-of-the-box hooks for pre-commit
- [pre-commit-hooks-django](https://github.com/ecugol/pre-commit-hooks-django) — Some useful hooks for Django development

### react

> Primary language(s): js.

- **local**

### sphinx

- [sphinx-lint](https://github.com/sphinx-contrib/sphinx-lint) — Check for stylistic and formal issues in .rst and .py files included in the documentation
