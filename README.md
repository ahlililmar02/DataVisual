# ERA5 vs BMKG Indonesia Wind Speed Data Evaluation

This project provides scripts to evaluate **ERA5** reanalysis wind speed data against **BMKG Indonesia** observational data. The Python tools in this repository help researchers and analysts compare wind speed data from these two sources, calculate statistical metrics, and visualize differences, allowing for an in-depth assessment of ERA5 data accuracy over Indonesia.

## Features

- **Data Extraction**: Reads and formats ERA5 and BMKG datasets to allow for direct comparison.
- **Statistical Analysis**: Computes key metrics like bias, Root Mean Square Error (RMSE), and correlation coefficient to quantify differences.

## Requirements

- **Python** 3.6 or higher
- Required packages:
  - **`pandas`**: For data handling
  - **`xarray`**: For working with ERA5 NetCDF data files
  - **`numpy`**: For calculations
