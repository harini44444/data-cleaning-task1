# Task 1: Data Cleaning and Preprocessing

##  Objective:
To clean and prepare a raw dataset by identifying and fixing issues like missing values, duplicates, inconsistent formatting, and wrong data types.

## Tools Used:
- Microsoft Excel

## Dataset:
- Customer Dataset (based on Mall Customer Segmentation)

## Cleaning Steps Performed:

1. **Missing Values:**
   - Filled empty 'Join Date' cells with default date `01-01-2022`
   - Verified other columns for missing values

2. **Duplicate Records:**
   - Removed duplicate entry with Customer ID 1011

3. **Standardization:**
   - Gender values standardized to `Male` and `Female`
   - Country names standardized to:
     - `United States` for US, USA, united states
     - `India` for india, INDIA
     - `China` for china, CHINA

4. **Date Formatting:**
   - Converted all 'Join Date' entries to format `dd-mm-yyyy`

5. **Data Types:**
   - Verified data types:
     - Age → float (example: 33.5)
     - Join Date → consistent date format
     - Gender → standardized text

## Files Included:
- cleaned_customer_data.xlsx (cleaned dataset)
- README.md

##  Outcome:
- A clean and structured dataset ready for analysis or machine learning models.

