# BrailleBlaster User Documentation

This repository contains the user documentation for the [BrailleBlaster software](https://github.com/aphtech/brailleblaster). Built versions of the documentation can be viewed at [BrailleBlaster documentation website](https://aphtech.github.io/brailleblaster-docs).

## Building the documentation

This documentation is built using sphinx. You will need Python installed. To get the required sphinx packages perform the following, ideally within a Python virtual environment but the choice is yours:
```bash
pip install -e .
```
Then to build the documentation run the following:
```bash
make html
```
