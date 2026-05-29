# 🏥 Task 1: Data Cleaning and Preprocessing

## 📌 Objective
Clean and prepare a raw dataset containing missing values, duplicates, and inconsistent formats — making it ready for analysis.

---

## 📂 Dataset
- **Name:** Medical Appointment No Shows
- **Source:** [Kaggle](https://www.kaggle.com/datasets/joniarroba/noshowappointments)
- **Size:** 110,527 rows × 14 columns (before cleaning)

---

## 🛠️ Tools Used
- Python (Pandas) — Jupyter Notebook
- Microsoft Excel (Power Query)

---

## 🧹 Cleaning Steps Performed

| # | Step | Description |
|---|------|-------------|
| 1 | Renamed Columns | Converted all column names to lowercase with underscores |
| 2 | Fixed Data Types | Converted scheduled_day and appointment_day to datetime |
| 3 | Removed Invalid Age | Found and removed 1 row with age = -1 |
| 4 | Standardized Gender | Converted values to uppercase (F, M) |
| 5 | Standardized No_show | Converted values to uppercase (NO, YES) |
| 6 | Missing Values | Checked — none found |
| 7 | Duplicate Rows | Checked — none found |

---

## 📊 Before vs After

| Metric | Before | After |
|--------|--------|-------|
| Total Rows | 110,527 | 110,526 |
| Invalid Ages | 1 | 0 |
| Missing Values | 0 | 0 |
| Duplicate Rows | 0 | 0 |

---

## 📁 Repository Structure

```
elevate-labs-task1/
├── CODE/
│   └── task1_data_cleaning.ipynb
├── DATASETS/
│   ├── KaggleV2-May-2016.csv
│   └── cleaned_medical_appointments.csv
├── EXCEL/
│   ├── KaggleV2-May-2016.csv
│   └── task1_cleaned_excel.csv
└── screenshots/
    ├── task1_excel_cleaned_data.jpg
    ├── task1_info.jpg
    ├── task1_negative_age.jpg
    ├── task1_power_query.jpg
    └── task1_summary.jpg
```
## ✅ Result
Cleaned dataset with **110,526 rows and 14 columns**, fully preprocessed and ready for analysis or modelling.
