# Retail Outlet Performance Analysis & Revenue Modeling

A university **group project** exploring retail outlet performance through data cleaning, exploratory data analysis (EDA), and simple linear regression.

## Project Overview

This project examines the relationship between **marketing spending and monthly revenue** across retail outlets. Python was used for data cleaning and exploratory analysis, while R was used for regression modeling.

The original dataset contained **1,245 records**. After removing 45 duplicate rows and handling missing or inconsistent values, the cleaned dataset contained **1,200 records and 10 variables**.

## Tools & Technologies

- **Python:** pandas, NumPy, matplotlib, and seaborn
- **R:** Simple linear regression (`lm()`) and diagnostic plots
- **Data Preparation:** Duplicate removal, missing-value handling, consistency checks, and data type validation

## Key Findings

- **Correlation:** Marketing spend and monthly revenue showed a strong positive relationship (*r* ≈ 0.9084).
- **Regression Equation:** Monthly Revenue = 625.42 + 18.93 × Marketing Spend
- **Model Fit:** R² ≈ 0.8253, meaning the model explained approximately **82.53%** of the observed variation in monthly revenue.

These findings describe an association in the analysed dataset. They **do not establish causation** or guarantee future revenue outcomes.

## Repository Structure

| File | Description |
|---|---|
| `analysis/EDA_Preprocessing.ipynb` | Python notebook containing preprocessing, EDA, and visualisations |
| `analysis/EDA_Preprocessing.html` | Browser-viewable export of the notebook and its outputs |
| `analysis/Regression_Analysis.R` | R script for regression analysis and diagnostics |
| `data/retail_outlets_clean.csv` | Cleaned dataset used in the analysis |
| `visuals/` | Selected project figures |

## Reproducing the Analysis

The notebook's initial preprocessing steps load `Retail_Outlets_Dataset.csv`, the **original raw dataset**, which is not included in this repository.

The cleaned CSV is provided for inspecting the processed data and running the R analysis. To reproduce the notebook from scratch, obtain the original dataset and update its file path as needed.

## Project Context

Completed in **2026** as a *Programming for Business Analytics* university group assignment.

This repository showcases the group project and does not claim that all work was completed independently. The full class presentation and recording are not included.
