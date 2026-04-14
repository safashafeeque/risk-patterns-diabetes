# Exploratory Analysis of Clinical Risk Factors in Diabetes Using Python

## Overview

This project explores a clinical diabetes dataset using Python to identify which variables show the strongest association with diabetes outcome. The analysis includes data cleaning, grouped comparison, correlation analysis, and visualisation of key clinical variables.

## Research Question

Which clinical variables show the strongest association with diabetes outcome in this dataset?

## Dataset

This project uses the Pima Indians Diabetes dataset, which contains clinical variables such as glucose, blood pressure, skin thickness, insulin, BMI, age, and diabetes outcome.

## Methods

- Loaded and inspected the dataset using pandas
- Replaced invalid zero values in selected clinical variables with missing values
- Imputed missing values using the median
- Compared average clinical variables across diabetes outcome groups
- Generated a correlation matrix to examine variable relationships
- Visualised glucose, BMI, and age distributions using boxplots
- Explored the relationship between BMI and glucose using a scatterplot

## Results

- Glucose showed the strongest association with diabetes outcome in this dataset
- BMI showed a moderate association with diabetes outcome
- Age showed a weaker but still relevant association
- BMI overlapped considerably across groups and did not clearly separate diabetic and non-diabetic individuals on its own
- Data cleaning was necessary because several variables contained implausible zero values

## Tools Used

- Python
- pandas
- NumPy
- matplotlib
- seaborn
- Google Colab

## Files

- `clinical_risk_factor_analysis_diabetes.ipynb` — main notebook containing the full analysis
- `diabetes.csv` — dataset used in the project

## Conclusion

This project helped me understand how data cleaning, grouped comparison, correlation analysis, and visualisation can be used to interpret real-world clinical data.

