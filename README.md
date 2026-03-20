## Source

The Python scripts in this repository are adapted from the official NCBI PubTator API documentation:

https://www.ncbi.nlm.nih.gov/research/pubtator3/api

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

PubTator files (`.PubTator`) in the `input/` and `output/` directories are intentionally excluded from version control to prevent accidental inclusion. 

