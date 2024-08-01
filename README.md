# ADNI1-INITIAL
The first analysis with ADNI dataset

Exploratory Data Analysis on ADNIMERGE Dataset

This Jupyter Notebook performs exploratory data analysis on the ADNIMERGE dataset. The analysis includes:

Data Loading: The ADNIMERGE dataset is loaded from an Excel file ('ADNIMERGE_03May2024.xlsx').

Data Overview: The notebook displays the first few rows of the dataset, a summary of rows and columns, column labels, row labels, data types, and memory usage. It also provides descriptive statistics of the dataset.

ADNI1 Protocol Analysis:

The number of participants in the ADNI1 protocol is calculated.
A bar chart visualizes the relationship between patient identification number (RID) and visit code (VISCODE) for the first 50 participants in ADNI1.
Another bar chart visualizes the relationship between RID and diagnosis at baseline (DX_bl) for the first 50 participants in ADNI1.
Correlation Analysis:

Pearson correlation coefficients are calculated between age, APOE4 status, TAU, PTAU, and MMSE scores.
A heatmap visualizes the correlation matrix.
Scatter Plots:

Scatter plots are generated to visualize the relationships between pairs of variables: AGE vs. APOE4, AGE vs. TAU, AGE vs. PTAU, APOE4 vs. TAU, APOE4 vs. PTAU, APOE4 vs. MMSE, PTAU vs. TAU, MMSE vs. TAU, and MMSE vs. PTAU.
This analysis provides insights into the distribution of variables, relationships between variables, and potential correlations within the ADNIMERGE dataset, particularly focusing on the ADNI1 protocol.
