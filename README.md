# Layoffs Data Analysis with MySQL

This project focuses on cleaning and analyzing a dataset of company layoffs using MySQL. The process involves data cleaning, standardization, handling null values, and conducting exploratory data analysis (EDA) to uncover insights.

## Project Overview

1. **Data Cleaning:**
   - Removed duplicate records.
   - Standardized fields like `company`, `industry`, and `country`.
   - Converted date formats for consistency.
   - Handled null and blank values.
   - Removed unnecessary columns and rows.

2. **Exploratory Data Analysis (EDA):**
   - Analyzed layoffs by company, country, and industry.
   - Identified trends over time.
   - Calculated rolling totals and ranked top companies with the highest layoffs each year.

## 🛠️ Technologies Used

- MySQL

## 📂 Files

- `layoffs_cleaning.sql` — Contains all cleaning and transformation steps.
- `layoffs_analysis.sql` — Contains exploratory queries for insights.

## 📥 Data

The dataset used in this project is publicly available and included in this repository as [`layoffs.csv`](./layoffs.csv). It contains information about company layoffs, including fields like `company`, `industry`, `total_laid_off`, `percentage_laid_off`, `date`, `stage`, and `country`.

---
