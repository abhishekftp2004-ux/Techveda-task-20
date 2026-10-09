# Task 20 — Data Types and Type Conversion (Ultra Expanded)

## Objective
Inspect DataFrame data types and convert columns to appropriate string, integer, float, Boolean and datetime types.

## Project files
- `Task_20.py` — complete Python program
- `Task_20.ipynb` — notebook walkthrough
- `passenger_raw.csv` — source data
- `passenger_cleaned.csv` — converted data
- `data_type_inspection_report.csv` — before/after type report
- `Task_20_Data_Types_and_Type_Conversion_ULTRA_EXPANDED.pdf` — detailed study guide

## Main methods
`df.dtypes`, `df.info()`, `df.shape`, `astype()`, `pd.to_numeric()`, `pd.to_datetime()`, `errors='coerce'`, `str.strip()`, `replace()`, `map()`, `isna()`, and `notna()`.

## Run
1. Install Pandas: `pip install pandas`
2. Keep `Task_20.py` and `passenger_raw.csv` in the same folder.
3. Run: `python Task_20.py`

## Important
Conversion may turn invalid values into NaN or NaT. Inspect these values rather than automatically replacing them with zero or deleting them.

## Top 5 skills
1. Pandas
2. Data Type Inspection
3. Type Conversion
4. Data Cleaning
5. Python Data Analysis
