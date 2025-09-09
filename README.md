# HERA Polarization Subtraction

Repository for identifying and subtracting polarized sources that leak into Stokes-I visibilities in HERA data.

## Overview

This package provides tools and workflows for:
- Identifying polarized sources in HERA visibility data
- Analyzing polarization leakage into Stokes-I measurements
- Developing and testing subtraction algorithms
- Interactive analysis through Jupyter notebooks

## Repository Structure

```
hera_polarization_subtraction/
├── hera_pol_sub/           # Main Python package
│   └── __init__.py
├── notebooks/              # Jupyter notebooks for analysis
│   └── source_identification/  # Notebooks for identifying sources
│       └── README.md
├── pyproject.toml          # Package configuration
├── README.md               # This file
├── LICENSE                 # MIT License
└── .gitignore             # Git ignore rules
```

## Installation

Clone the repository and install in development mode:

```bash
git clone https://github.com/tyler-a-cox/hera_polarization_subtraction.git
cd hera_polarization_subtraction
pip install -e .
```

For development with additional dependencies:
```bash
pip install -e ".[dev,notebooks]"
```

## Usage

### Notebooks
The `notebooks/source_identification/` directory contains Jupyter notebooks for interactive analysis of polarized sources. See the README in that directory for more details.

### Python Package
Import the package in your Python scripts:
```python
import hera_pol_sub
```

## Contributing

This is a research repository for the HERA collaboration. Please follow standard Python development practices and ensure all notebooks run without errors before committing.
