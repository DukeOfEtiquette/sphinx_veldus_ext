# Sphinx Veldus Extension v0.1.1

This is a Sphinx Extension built for Veldus.

## Documentation [![Netlify Status](https://api.netlify.com/api/v1/badges/5ab1e09a-cbd5-4dc2-931d-719d02e44349/deploy-status)](https://app.netlify.com/sites/sphinx-veldus-ext/deploys)

Learn about this extension from the official [documentation](https://sphinx-veldus-ext.netlify.app/).

## PyPI

This project is distributed as a [PyPI package](https://pypi.org/project/sphinx-veldus-ext/).

## Bump version

In there files:

- `setup.py`
- `README.md`

## Package

`$ rm -rf dist/* && python3 setup.py sdist bdist_wheel`

## Upload

`$ python3 -m twine upload dist/*`