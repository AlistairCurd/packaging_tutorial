# Packaging_tutorial

A simple Python packaging and publishing example.

# Requirements

A Python >= 3.10 environment containing pip, build, twine

# Instructions

Structure the package and follow the instructions as on [packaging.python.org](https://packaging.python.org/en/latest/tutorials/packaging-projects/).

*Tip*
To avoid pain with twine having problems with keyring, at least on WSL2 and Ubuntu 22.04.3 LTS:
  Before attempting to upload the distribution packages with twine, type `keyring --disable`.
  Then in the twine command use the username flag `-u` with your TestPyPI username.
  (You will need to have your TestPyPI API token ready, which you need to find in your TestPyPI account settings.
    
# Usage

The eventually you will be able to import a function as [instructed](https://packaging.python.org/en/latest/tutorials/packaging-projects/), which will add one to its argument.

# Author

Alistair Curd, University of Leeds, 2024

# License

[MIT License](https://github.com/AlistairCurd/packaging_tutorial/blob/main/LICENSE)
