# Data Cleaning & Preparation — Task 1

## Project Overview
This project demonstrates data cleaning and preparation using a customer dataset containing 128 records and six columns: Name, Email, City, Country, Date, and Amount.

## Data Cleaning Steps
- Removed leading and trailing spaces and standardized repeated spaces in names.
- Standardized name capitalization while preserving accents and apostrophes.
- Removed extra spaces from email addresses and converted emails to lowercase.
- Standardized capitalization in city and country fields.
- Converted dates from mixed formats to YYYY-MM-DD.
- Converted Amount values to numeric values.
- Identified and removed exact duplicate records after standardizing formatting, keeping the first occurrence.

## Results
- Records before cleaning: 128
- Exact duplicate records removed: 8
- Records after cleaning: 120
- Total columns: 6
- Date values that could not be parsed: 0
- Amount values that could not be converted to numbers: 0

## Files Included
- `SWYNEX-Data-Cleaning-Preparation.xlsx` — cleaned dataset in Excel format.
- `SWYNEX-Data-Cleaning-Preparation.csv` — cleaned dataset in CSV format.

## Data Scope and Limitations
The cleaning results apply to the 128 records provided for this project.

No blank cells were identified in the supplied records, so no missing values were filled or invented. Duplicate removal was based on exact matching records after formatting standardization.

Slash-separated dates were interpreted as day/month/year (DD/MM/YYYY).

The email addresses use the example.com domain, indicating that the dataset is sample data rather than verified customer contact information.

## Conclusion
The dataset was standardized and checked for duplicate records, date-format inconsistencies, and numeric conversion issues. The cleaned data is available in both Excel and CSV formats.
