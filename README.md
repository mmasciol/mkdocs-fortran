# Markdown-Fortran

An extension for [MkDocs](https://www.mkdocs.org/) for building documentation from Fotran source files.

## Installation

```bash
$ pip install .
```

## Activating in MkDocs

```yaml
markdown_extensions:
  - markdown_fortran.wrap:
      base_path: docs
      encoding: 'utf-8'
```
