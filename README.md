# Titanic Data Cleaning & Exploration 🚢

This project focuses on **data cleaning and preprocessing** of the Titanic dataset, using Python and Jupyter Notebook.  
The dataset is loaded from seaborn’s built-in sample datasets.

---

## 📊 Main Steps
- **Data Exploration**: Checking dataset structure, summary statistics, and missing values.
- **Data Cleaning**:
  - Dropped the `deck` column (too many missing values).
  - Handled missing values with median/mode imputation.
  - Removed duplicate rows.
- **Outlier Treatment**:
  - Detected outliers in `fare` and `age` using the Interquartile Range (IQR).
  - Adjusted extreme values in `sibsp` and `parch`.
- **Visualization**:
  - Boxplots before and after cleaning to confirm outlier handling.

---

## 🎯 Project Goal
To practice **data preprocessing and cleaning techniques** as the first step of a data science workflow.

---