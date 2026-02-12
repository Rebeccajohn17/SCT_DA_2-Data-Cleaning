# SCT_DA_2
Data Cleaning and Preparation using Python and Pandas
# 🧹 Data Cleaning and Preparation using Python and Pandas

## 📌 Project Overview

This project focuses on cleaning and preparing raw data using Python and Pandas to ensure accuracy, consistency, and reliability before performing analysis.

Data cleaning is a critical step in the data analytics process, as poor data quality can lead to incorrect insights and decisions.

---

## 🎯 Objective

To clean and preprocess a raw dataset by:

- Identifying missing values
- Handling duplicates
- Correcting data types
- Standardizing inconsistent entries
- Preparing the dataset for further analysis

---

## 📁 Dataset Information

The dataset contained:

- Missing values
- Duplicate records
- Inconsistent formatting
- Incorrect data types

The goal was to transform the raw dataset into a structured and analysis-ready format.

---

## 🛠 Steps Performed

### 1️⃣ Data Inspection
- Used `.head()`, `.info()`, and `.describe()` to understand structure
- Checked data types
- Identified null values

### 2️⃣ Handling Missing Values
- Used `.isnull().sum()` to detect missing data
- Removed or filled missing values using:
  - Mean / Median (for numerical columns)
  - Mode (for categorical columns)

### 3️⃣ Removing Duplicates
- Used `.drop_duplicates()` to eliminate repeated records

### 4️⃣ Data Type Correction
- Converted columns to appropriate types:
  - Dates → `datetime`
  - Numeric fields → `int` / `float`

### 5️⃣ Data Standardization
- Standardized text fields (e.g., lowercase conversion)
- Removed extra spaces
- Ensured consistent category naming

---

## 📊 Key Learning Outcomes

- Understood the importance of data quality
- Learned practical data cleaning techniques using Pandas
- Improved dataset reliability and integrity
- Prepared structured data for further EDA or modeling

---

## 🧰 Tools & Technologies Used

- Python  
- Pandas  
- Jupyter Notebook  

---

## 📌 Project Outcome

Successfully transformed raw, inconsistent data into a clean and structured dataset ready for analysis, ensuring improved accuracy and reliability in decision-making.
