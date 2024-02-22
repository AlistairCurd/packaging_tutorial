# Packaging_tutorial

A simple Python packaging and publishing example.

# Requirements

A Python >= 3.10 environment containing pip, build, twine

# Instructions

Structure the package and follow the instructions as on [packaging.python.org](https://packaging.python.org/en/latest/tutorials/packaging-projects/).

**Tip**

If twine having problems with keyring backends, at least on WSL2 and Ubuntu 22.04.3 LTS:

* Before attempting to upload the distribution packages with twine, type `keyring --disable`.
* Then in the twine command use the username flag `-u` with your TestPyPI username.
* (Whether doing this or not, you will need to have your TestPyPI API token ready for the upload, which you need to find in your TestPyPI account settings.)
    
# Usage

When the package is [installed](https://packaging.python.org/en/latest/tutorials/packaging-projects/), you will be able to import a function as instructed, which will add one to its argument.

# Author

Alistair Curd, University of Leeds, 2024

# License

[MIT License](https://github.com/AlistairCurd/packaging_tutorial/blob/main/LICENSE)
