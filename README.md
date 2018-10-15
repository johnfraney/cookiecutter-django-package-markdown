# Cookiecutter Django Package Markdown

This is based on pydanny's excellent [cookiecutter-djangopackage](https://github.com/pydanny/cookiecutter-djangopackage) with Markdown and MkDocs for documentation.

I've also made a few other changes here and there, including:

- Use `twine` instead of `setup.py sdist upload` for releases
- Update Travis CI config to newer syntax


## Features

- Release publishing to PyPI using [twine](https://packaging.python.org/tutorials/packaging-projects/) with [TestPyPI](https://packaging.python.org/guides/using-testpypi/) support
- Documentation site generated using [MkDocs](https://www.mkdocs.org/) with the [Material for MKDocs](https://squidfunk.github.io/mkdocs-material/) theme.
- [Travis CI](https://travis-ci.org/) integration
- [EditorConfig](https://editorconfig.org/) support
- GitHub [issue template](https://help.github.com/articles/about-issue-and-pull-request-templates/)
- Fancy badges:
  - PyPI version
  - Python versions
  - Django versions
  - License
  - Travis CI build status
