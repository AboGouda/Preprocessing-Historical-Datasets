# Historical Data Cleaning and Matching

This project focuses on cleaning and standardizing a historical dataset for further analysis. It handles missing values, inconsistent formats, and duplicates, with a focus on the "Country" and "Age of Death" columns.

## Key Steps

- **Country Cleaning**: Extracted and standardized country names from free-text fields using a keyword-matching function and custom dictionary.
- **Age Recalculation**: Fixed incorrect or missing ages by recalculating from birth and death years or estimating based on similar entries.
- **Missing Data Handling**: Filled missing values with logical defaults (e.g., "Unknown") or estimated values.
- **Deduplication**: Prioritized rows with complete country data, removed duplicates, and reset the dataset index.
- **Final Output**: Cleaned dataset exported as `cleaned_data.csv` for analysis.

## Challenges Addressed

- Inconsistent or missing country values.
- Mismatched or missing age data.
- Duplicate name records with conflicting information.

## Tools Used

- Python (Pandas, NumPy)
- Jupyter Notebook

---

🎯 The cleaned dataset is ready for further analysis or visualization.
