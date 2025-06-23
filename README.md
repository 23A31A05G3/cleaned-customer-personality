# Customer Personality Analysis – Data Cleaning & Preprocessing

## 📌 Objective
The goal of this project is to clean and preprocess the raw *Customer Personality Analysis* dataset obtained from Kaggle, ensuring it is ready for analysis or modeling.

---

## 🧹 Cleaning Steps Performed

1. *Handled Missing Values*
   - Filled missing Income values with median.
   - Dropped rows with missing Dt_Customer.

2. *Removed Duplicate Records*
   - Used .drop_duplicates() to remove 100% of duplicates.

3. *Fixed Column Names*
   - Converted all column names to lowercase.
   - Removed extra spaces and replaced spaces with underscores.

4. *Standardized Text Columns*
   - Cleaned values in education and marital_status columns by making them lowercase and stripping whitespace.

5. *Converted Data Types*
   - Parsed Dt_Customer column into proper date format (YYYY-MM-DD).
   - Ensured numeric fields like Income, Age, Membership_Years were correctly typed.

6. *Added New Features*
   - age = 2024 - year_birth
   - membership_years = Number of years since becoming a customer

---

## 📁 Files in This Repo

| File Name | Description |
|-----------|-------------|
| cleaned_customer_personality.csv | Final cleaned dataset |
| task1_data_cleaning.ipynb | Google Colab notebook used for cleaning |
| README.md | This documentation |

---

## ✅ Summary
The final dataset has:
- No missing values
- No duplicate entries
- Standardized formats for analysis
- 31 clean, ready-to-use columns

---

## 📊 Source
Dataset: [Customer Personality Analysis on Kaggle](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis)