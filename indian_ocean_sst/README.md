# Indian Ocean SST Analysis

This directory contains the evolution of the Indian Ocean Sea Surface Temperature (SST) analysis project through multiple versions, showcasing improvements in both analysis techniques and code documentation.

## Project Files

### [Flexible_Indian_Ocean_SST_Analysis_v2.0.0.ipynb](./Flexible_Indian_Ocean_SST_Analysis_v2.0.0.ipynb)
**Latest Version (2.0.0)** - The most comprehensive and well-documented version with:
- Extensive documentation and markdown sections
- Enhanced regional analysis with seasonal statistics
- File size display in file selection
- Timestamp-based file naming for better organization
- Version tracking for individual code sections

### [flexible_sst_analysis.v1.ipynb](./flexible_sst_analysis.v1.ipynb)
**Version 1.0** - Intermediate version with:
- Flexible data file selection
- Basic seasonal and regional analysis
- Simple timestamp-based output naming

### [indian_ocean_sst_seasonal_analysis.ipynb](./indian_ocean_sst_seasonal_analysis.ipynb)
**Original Version** - Initial implementation with:
- Basic SST analysis implementation
- Simple seasonal cycle detection
- Regional focus capabilities

## Key Features

- Analysis of sea surface temperature patterns across the Indian Ocean
- Seasonal temperature cycle detection and visualization
- Regional analysis focused on the Arabian Sea and Bay of Bengal
- Enhanced geographical visualization using Cartopy
- Statistical analysis with proper spatial weighting

## Input Data Requirements

- Format: NetCDF (.nc)
- Variable: sst (Sea Surface Temperature)
- Dimensions: time, latitude, longitude
- Region: Indian Ocean (approximately 30-120°E, -30-30°N)

## Output Files

1. **Seasonal Cycle Plot**
   - Shows monthly variations in sea surface temperature

2. **Enhanced Seasonal Maps**
   - Four-panel plot showing seasonal temperature patterns

3. **Regional Analysis Maps**
   - Separate plots for each region (Arabian Sea, Bay of Bengal)

4. **Statistics File**
   - Contains detailed statistical analysis by region and season

## Usage Instructions

1. Ensure all dependencies are installed (see main README)
2. Place your NetCDF data files in the repository's data directory
3. Open the latest version notebook in Jupyter
4. In Section 2, update the `current_file` variable to your desired data file
5. Run all cells to generate analysis and visualizations
