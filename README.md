## Source

The Python scripts in this repository are adapted from the official NCBI PubTator API documentation:

https://www.ncbi.nlm.nih.gov/research/pubtator3/api
https://github.com/ncbi/tmVar3

Some code in this repository has been modified, as parts of the original examples provided by the NCBI PubTator API documentation appear to be outdated.

## Installation

See [INSTALLATION.md](./Installation.md) for environment setup and usage instructions.

## Dependency Modifications

This project is configured to run on Python 3.10.

Several dependencies were bumped to maintain compatibility with modern Python environments. Some of the original package versions were outdated, no longer supported, or incompatible with newer Python releases.

These updates were required to ensure the project can be installed and run successfully.

## Input and Output Files 

The `input/` and `output/` directories are intended for actual data processing and are excluded from version control to prevent accidental inclusion of large or sensitive files.

For testing and validation, `test_input/` and `test_output/`directories are provided. These contain sample datasets in PubTator (.PubTator), XML, and JSON formats.

You can use these test files to verify that your installation and configuration are working correctly by following the steps in [INSTALLATION.md](./Installation.md).


