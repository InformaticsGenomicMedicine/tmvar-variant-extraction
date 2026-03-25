## Source

The Python scripts in this repository are adapted from the official NCBI PubTator API documentation:

https://www.ncbi.nlm.nih.gov/research/pubtator3/api
https://github.com/ncbi/tmVar3

Some code in this repository has been modified, as parts of the original examples provided by the NCBI PubTator API documentation appear to be outdated.

## Installation

See [INSTALLATION.md](./Installation.md) for environment setup and usage instructions.

## Dependency Modifications

This project includes a set of updated dependencies to ensure compatibility with modern Python environments.

Several packages specified in the original software were outdated or no longer maintained. The following adjustments were made:

- `cffi` upgraded to >=1.16.0 to resolve installation issues  
- `cryptography` upgraded to >=41.0.0 due to incompatibility with older versions  
- `pyOpenSSL` upgraded to >=24.0 for compatibility  
- `pycrypto` replaced with `pycryptodome` (as `pycrypto` is no longer maintained)  

These changes were necessary to successfully install and run the software.

## Input and Output Files 

The `input/` and `output/` directories are reserved for actual data processing and are excluded from version control to prevent accidental inclusion of large or sensitive files.

To support testing, `test_input/` and `test_output/` directories are provided to store sample data. Three test datasets are included in PubTator (.PubTator), XML, and JSON formats, which can be used to verify that the installation and configuration are set up correctly by following the instructions in [INSTALLATION.md](./Installation.md).


