# Chicago Food Inspections - Excel Data Quality Assessment Project

The original and assessed datasets are large (over GitHub's upload size limit), so they are not included in this repository. The project focuses on the data quality assessment process and documentation.

## Project Overview

This project focuses on assessing the quality of a real-world food inspection dataset using Microsoft Excel.

The main objective was to check whether the dataset contained common data quality issues such as duplicate records, missing values, inconsistent text, invalid values, incorrect data types, blank rows, and unnecessary columns before using it for further analysis.

Instead of making unnecessary changes, every issue was carefully reviewed and only verified corrections were made.

---

## Dataset Information

- **Dataset Name:** Chicago Food Inspections
- **Source:** Chicago Open Data Portal
- **Domain:** Food Safety / Public Health
- **Tool Used:** Microsoft Excel
- **Rows:** 312,448
- **Columns:** 17
- **File Format:** CSV

---

## Project Objectives

- Check the overall quality of the dataset.
- Identify common data quality issues.
- Make only verified corrections where necessary.
- Document every quality check and decision.
- Prepare the dataset for future analysis.

---

## Data Quality Checks Performed

### 1. Duplicate Rows

**Status:** Completed

- Checked the entire dataset for duplicate records.
- No duplicate rows were found.
- Since every inspection had a unique Inspection ID, no rows were removed.

---

### 2. Missing Values

**Status:** Completed

- Checked missing values column-wise.
- Most missing values could not be verified from other columns.
- These values were retained to avoid making incorrect assumptions.
- A few missing city names were verified using Address, State, and ZIP Code and were updated.

---

### 3. Blank Rows

**Status:** Completed

- Checked the dataset for completely blank rows.
- No blank rows were found.
- No rows were removed.

---

### 4. Date Format

**Status:** Completed

- Reviewed the Inspection Date column.
- All dates were already stored in a consistent format.
- No formatting changes were required.

---

### 5. Text Consistency

**Status:** Completed

- Reviewed text columns for inconsistent values.
- Corrected a few verified city name typos.
- Business names (DBA Name and AKA Name) were not modified because they represent official registered business names and changing them could affect data accuracy.

---

### 6. Leading and Trailing Spaces

**Status:** Completed

- Checked important text columns for unnecessary spaces.
- Minor spacing issues were identified.
- Since removing spaces in a very large dataset using formulas could unintentionally affect original records in Excel, no bulk replacement was performed.
- Original values were retained.

---

### 7. Data Types

**Status:** Completed

- Reviewed all columns.
- Applied appropriate data formats for text, numbers, and dates.
- No incorrect data types remained.

---

### 8. Invalid Values

**Status:** Completed

- Checked important columns such as Risk, Results, State, ZIP Code, Latitude, and Longitude.
- No invalid values were found.
- No corrections were required.

---

### 9. Unnecessary Columns

**Status:** Completed

- Reviewed all columns to determine whether any were unnecessary.
- Every column provides useful information for analysis.
- No columns were removed.

---

## Key Findings

- No duplicate records were found.
- No blank rows were found.
- Date formats were already consistent.
- Data types were corrected where required.
- A few verified city name typos were corrected.
- Missing values were retained unless they could be verified.
- All columns were useful for analysis.
- The dataset was generally well maintained.

---

## Files Included

- Chicago_Food_Inspections_raw.xlsx
- Chicago_Food_Inspections_assessed.xlsx
- Data_Quality_Assessment.xlsx
- README.md

---

## Skills Demonstrated

- Microsoft Excel
- Data Quality Assessment
- Missing Value Analysis
- Duplicate Detection
- Data Validation
- Text Standardization
- Data Type Validation
- Documentation

---

## Conclusion

This project demonstrates the process of assessing the quality of a real-world dataset before analysis.

Although only a few corrections were required, each quality check was performed carefully, and every decision was documented. The assessment showed that the dataset is well maintained and suitable for further data analysis.