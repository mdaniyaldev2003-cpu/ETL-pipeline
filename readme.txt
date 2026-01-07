# Border Crossing Data Cleaning & Database Insertion

This project demonstrates a **data engineering workflow** using Python.  
It focuses on **cleaning, transforming, and loading (ETL)** border crossing data using **Pandas, NumPy, and SQL**.

---

## 📌 Project Overview

The script performs the following steps:

1. Reads raw border crossing data from a CSV file
2. Cleans and preprocesses the dataset
3. Converts data types for consistency
4. Exports cleaned data to a new CSV file
5. Inserts the cleaned data into a SQL database table

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- SQL (MySQL / PostgreSQL compatible)
- CSV File Handling

---

## 🔄 Data Processing Steps

### 1️⃣ Load Dataset
- Reads `border.csv` using Pandas

### 2️⃣ Data Cleaning
- Removes duplicate rows
- Handles missing values
- Renames columns to snake_case
- Converts date column to proper datetime format
- Converts numeric columns to correct data types

### 3️⃣ Data Transformation
- Selects required columns only
- Formats date as `YYYY-MM-DD`

### 4️⃣ Export Cleaned Data
- Saves cleaned dataset as `border_cleaned.csv`

### 5️⃣ Load into Database
- Inserts data into `border_crossing` SQL table using parameterized queries

---

## 📂 File Structure

