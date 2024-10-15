# PCA and Tableau Analysis

This repository contains a Jupyter notebook showcasing the use of **Principal Component Analysis (PCA)** on a dataset related to candy characteristics. The project also demonstrates how to visualize these PCA results and export the transformed data for further use.

## Overview

The project involves the following steps:

1. **Data Preprocessing**: 
   - A dataset of various candies and their attributes (such as chocolate, fruity, caramel, etc.) is loaded and prepared for analysis.
   
2. **Principal Component Analysis (PCA)**:
   - PCA is applied to reduce the dimensionality of the dataset and extract key features.
   
3. **Data Visualization**:
   - A scatter plot is generated to visualize the PCA results, helping to understand how different candies are grouped based on the selected components.

4. **Data Export**:
   - The transformed data is exported into an Excel file (`Candy_PCA.xlsx`) for further analysis or integration with other tools, such as Tableau.

## Files

- `PCA and Tableau.ipynb`: Jupyter notebook containing the full PCA analysis and visualization.
- `Candy_PCA.xlsx`: Excel file containing the PCA-transformed dataset, ready for use in other applications like Tableau.

## Requirements

To run the notebook, you will need the following Python packages:

- `pandas`
- `numpy`
- `matplotlib`
- `sklearn`
- `openpyxl` (for exporting to Excel)

You can install these packages using the following command:

```bash
pip install pandas numpy matplotlib scikit-learn openpyxl
```

## Running the Notebook

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/pca-and-tableau.git
   ```
   
2. Open the Jupyter notebook:
   ```bash
   jupyter notebook "PCA and Tableau.ipynb"
   ```

3. Follow the steps in the notebook to load the dataset, apply PCA, visualize the results, and export the transformed data.

## Data Visualization with Tableau

The Excel file `Candy_PCA.xlsx` can be imported into Tableau for further visual analysis, enabling the creation of dashboards and interactive visualizations.
