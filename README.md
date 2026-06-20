# Data Cleaning & Preprocessing (Assignment)

This practice project cleans a dataset (`dirty_dataset.csv`) containing 20,300 rows and 15 columns with intentionally injected errors. 

## 15 Problems Fixed
1. Imputed missing values using median/mode.
2. Removed exact duplicate rows.
3. Dropped duplicate employee IDs.
4. Standardized 5 mixed date formats to `YYYY-MM-DD`.
5. Converted numeric values stored as strings (removed '$', 'kg').
6. Standardized inconsistent labels (Country, Gender).
7. Corrected spelling mistakes in cities and departments.
8. Capped extreme salary outliers using the IQR method.
9. Removed invalid age and price values.
10. Cleaned noisy review text.
11. Standardized boolean columns mixed with strings.
12. Corrected data types across multiple columns.
13. Enforced logical range violations.
14. Addressed target class imbalance.
15. Dropped entirely null duplicate schema columns.

## How to Run
1. Run `pip install -r requirements.txt`
2. Open `data_cleaning.ipynb`
3. Run all cells to generate `cleaned_dataset.csv`.

## Summary
The dataset is now completely free of missing values, duplicates, and outliers, with all columns correctly typed and formatted for analysis.
