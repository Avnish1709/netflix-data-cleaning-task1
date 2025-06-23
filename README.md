# Netflix Data Cleaning - Elevate Labs Internship Task 1

## 📌 Task Overview
As part of the Elevate Labs Data Analyst Internship Task 1, this project demonstrates the process of cleaning and preprocessing a raw dataset using **Excel**.

## 🧹 Cleaning Steps Performed (Excel)
- Removed duplicate rows using Excel's **Remove Duplicates** tool.
- Handled missing values:
  - `director` → "Unknown"
  - `cast` → "Not Available"
  - `country` → "Unknown"
  - `rating` → "Not Rated"
  - `duration` → "0"
  - `date_added` → "01 January 2000"
- Standardized date format in `date_added` to **dd-mm-yyyy**
- Cleaned column headers and converted text to proper format
- Final dataset is cleaned and ready for analysis

## 📁 Files Included
- `cleaned_netflix_data_humanized.xlsx` → Cleaned Excel dataset
- `README.md` → This summary file

## 📊 Dataset Source
- [Netflix Movies and TV Shows - Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
