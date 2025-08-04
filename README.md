# 🧹 Data Cleaning and Preprocessing – Internship Task 1

## 📌 Task Objective
The goal of this task was to clean and preprocess a raw dataset by:
- Handling missing values
- Removing duplicate entries
- Standardizing inconsistent data
- Converting date formats
- Renaming columns for uniformity
- Ensuring correct data types

## 🛠 Tools Used
- Python
- Pandas library
- Jupyter Notebook 

## 📂 Dataset Used
- Name: Customer Personality Analysis
- Source:https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis
- Rows: 2240  
- Columns: 29

## 🔍 Data Cleaning Steps

# 1. Missing Values
- Used .isnull().sum() to identify missing data.
- Filled missing values using:
  - Mean (for numerical columns)
  - Mode (for categorical columns)
  - Dropped rows with excessive missing data.

# 2. Duplicate Records
- Checked for duplicates using .duplicated().sum()
- Removed using .drop_duplicates()

# 3. Standardization
- Converted all categorical text (e.g., Gender, Country) to lowercase
- Stripped leading/trailing whitespaces

# 4. Date Format Consistency
- Converted all date columns to dd-mm-yyyy format using pd.to_datetime()

# 5. Column Renaming
- Renamed columns to lowercase with underscores (e.g., Join Date → join_date)

# 6. Data Type Corrections
- Converted numeric columns from string to integer/float
- Converted date strings to datetime format

# ✅ Final Outcome
- Cleaned dataset is stored as cleaned_data.csv
- No null values remain
- Uniform column naming and formatting
- Ready for analysis or visualization

*** 📎 Files Included
- task1_cleaning.ipynb – Jupyter notebook with code
- cleaned_data.csv – Final cleaned dataset
- README.md – Summary of task
- Name: Abhi Singh Yadav
- Internship:Elevate Labs
- Date: 4 August 2025
