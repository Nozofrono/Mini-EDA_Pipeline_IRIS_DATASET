# Project: Mini EDA and Pipeline Design with Scikit-Learn

This project is part of the **Data Science 2** learning series. This repository demonstrates the implementation of a complete data preprocessing workflow using the classic **Iris** dataset.

## Objective
The main goal is to consolidate the concepts of Exploratory Data Analysis (EDA) and the creation of automated workflows (Pipelines) to prepare data for Machine Learning models in an efficient and reproducible manner.

## Project Contents

1.  **Exploratory Data Analysis (Mini EDA):**
    *   Identification and classification of variable types (Continuous Numerical, Nominal Categorical).
    *   Visualization of distributions and relationships between variables using `pairplot` and correlation heatmaps with `Seaborn`.
    *   Missing value detection and descriptive statistical analysis.

2.  **Feature Engineering:**
    *   Implementation of a custom function (`calculate_area`) to obtain the petal area.
    *   Use of `FunctionTransformer` to integrate custom logic within the Scikit-Learn pipeline.

3.  **Processing Pipeline Design:**
    *   **Numerical Pipeline:** Imputation of missing values (median strategy) and scale standardization (`StandardScaler`).
    *   **Categorical Pipeline:** Encoding of nominal variables using `OneHotEncoder`.
    *   **ColumnTransformer:** Integration of multiple transformers into a single object to process the dataset in a parallel and organized way.

## Tools Used
- **Python 3**
- **Pandas** & **NumPy** (Data manipulation)
- **Matplotlib** & **Seaborn** (Visualization)
- **Scikit-Learn** (Pipelines, Preprocessing, and Transformers)

## Results
The workflow transforms the original 5 columns into a set of **8 optimized features**, including scaled variables, binary indicators (One-Hot), and newly calculated metrics, ready to be consumed by any classification algorithm.

---
**Developed by:** Juan Guillermo Marulanda Mesa  
**Date:** March 2026
