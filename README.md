# Week1-Data-Cleaning
Week 1 internship project: Data cleaning and exploration using Python and Pandas in Google Colab.

# Data leaning and Exploring the Applicant Dataset

## Project Overview
This project was completed as part of the Week 1 data science internship task. The objective was to practice data inspection, data cleaning, standardization, and basic exploration using Python and Pandas in Google Colab.

## Tools Used
- Python
- Pandas
- Google Colab
- GitHub

## Dataset Information
The dataset contains applicant information in five columns:
- Applicant_ID
- Name
- Email
- Age
- City

The original dataset contained 100 rows and 5 columns.

## Data Cleaning Steps
1. Inspected the dataset using `shape`, `head()`, `info()`, and missing-value checks.
2. Identified and handled missing values.
3. Checked and removed duplicate records where appropriate.
4. Validated email addresses and handled invalid email entries.
5. Standardized city names and removed unnecessary whitespace.
6. Checked age values and converted the Age column to a numeric data type.
7. Verified the cleaned dataset for remaining missing values and data types.
8. Exported the cleaned dataset as a CSV file.

## Final Results
- Final dataset shape: 98 rows and 5 columns.
- Missing values: 0 in all five columns, according to the final validation.
- Applicant_ID data type: `int64`
- Age data type: `float64`
- Name, Email, and City data types: `object`

## Project Files
- `Week1_Data_Cleaning.ipynb`: Notebook containing the code, explanations, and outputs.
- `applicants_cleaned.csv`: Final cleaned dataset.
- `applicants.csv`: Original dataset, if included.

## Learning Outcomes
- Understanding data quality issues.
- Handling missing values and duplicate records.
- Validating email formats.
- Standardizing text data.
- Checking data types and validating cleaning results.
- Documenting data-cleaning decisions using Markdown.

## Author
Hafza Nazar
BS Mathematics Student
