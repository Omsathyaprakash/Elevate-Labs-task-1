# 🧹 Data Cleaning and Preprocessing – Customer Personality Analysis (Excel)

This project involves cleaning and preprocessing the **Customer Personality Analysis** dataset from [Kaggle](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis) using **Microsoft Excel and Power Query**.

## 📊 Dataset
- **Source:** Kaggle - Customer Personality Analysis
- **Format:** CSV

## 🛠️ Tools Used
- Microsoft Excel
- Power Query (Excel's built-in ETL tool)

---

## 📌 Task Objective
Clean and prepare a raw dataset with:
- Null values
- Duplicates
- Inconsistent text/date formats
- Irregular column headers and data types

---

## 🔧 Steps Performed

1. **Imported the CSV file** into Excel from Kaggle.
2. **Loaded the dataset into Power Query** for transformation.
3. **Removed duplicate rows** using Power Query.
4. **Checked for null values** via Column Quality pane.
   - Replaced `null` values in the **Income** column with `0`.
5. **Standardized text values** (e.g., Gender, Education, Marital Status).
6. **Formatted date columns** to `dd-mm-yyyy`.
7. **Cleaned column headers** (removed special characters, ensured uniform naming).
8. **Fixed data types** (e.g., Income as Decimal, Dates as Date).
9. **Closed and loaded** the cleaned dataset into an Excel worksheet.

---

## 📂 Files in This Repo

- `Customer_Personality_Transformed.xlsx` – Final cleaned version


---
