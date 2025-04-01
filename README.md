# Proteomics Data Analysis

This Python script performs proteomics data analysis on an Excel file containing protein data. The analysis includes statistical tests and filtering of significant proteins based on p-values and false discovery rate (FDR). The script reads the data from an Excel file, performs statistical analysis, and provides a summary of significant proteins.

## Features

- Load proteomics data from an Excel file.
- Perform t-tests to find significant differences between groups.
- Adjust p-values using the Benjamini-Hochberg method to control for multiple testing.
- Output the filtered list of significant proteins based on adjusted p-values (FDR).
- Option to visualize results using a heatmap.

## Prerequisites

Before running the script, make sure you have the following Python libraries installed:

- pandas
- numpy
- scipy
- matplotlib
- seaborn
- statsmodels

You can install these libraries using pip:

```bash
pip install pandas numpy scipy matplotlib seaborn statsmodels

