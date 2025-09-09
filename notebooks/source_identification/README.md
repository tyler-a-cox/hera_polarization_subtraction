# Source Identification Notebooks

This directory contains Jupyter notebooks for identifying polarized sources in HERA data that leak into Stokes-I visibilities.

## Notebooks

The notebooks in this directory will help with:

1. **Source Detection**: Identifying potential polarized sources in the data
2. **Source Characterization**: Analyzing the properties of detected sources
3. **Leakage Analysis**: Understanding how polarized sources leak into Stokes-I
4. **Validation**: Verifying source identification and subtraction methods

## Usage

To use these notebooks:

1. Install the required dependencies (see main repository README)
2. Launch Jupyter: `jupyter lab` or `jupyter notebook`
3. Navigate to this directory and open the relevant notebook
4. Follow the instructions within each notebook

## Data Requirements

These notebooks expect HERA visibility data in the standard format. Ensure your data includes:
- Stokes-I visibilities
- Polarization information (Q, U, V)
- Antenna and baseline information
- Time and frequency axes