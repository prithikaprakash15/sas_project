# Clinical Dataset Exploration and Data Quality Analysis Using SAS

## 📌 Project Overview

This project focuses on exploring a synthetic clinical patient dataset and performing data quality analysis using **SAS Studio**. It demonstrates basic data analysis techniques, descriptive statistics, duplicate record detection, missing value analysis, and validation of clinical data.

The project is designed for learning and understanding how SAS can be used to explore structured datasets and identify potential data quality issues.

## 🎯 Objectives

- Explore and understand the structure of a clinical dataset.
- Generate descriptive statistics for numerical variables.
- Identify missing values in the dataset.
- Detect duplicate patient records using patient IDs.
- Validate patient age values.
- Flag potentially unusual blood pressure readings for review.

## 🛠️ Tools and Technologies

- **Programming Language:** SAS
- **Platform:** SAS Studio (Web-based)
- **Concepts:** Data Exploration, Data Cleaning, Descriptive Statistics, Data Quality Analysis

## 📊 Dataset Description

The dataset contains 10 synthetic patient records created for educational purposes.

| Column | Description |
|---|---|
| Patient_ID | Unique identifier for each patient |
| Age | Patient's age in years |
| Gender | Patient's gender category in the synthetic dataset |
| Diagnosis | Example health-condition category |
| Blood_Pressure | Illustrative blood pressure value |
| Heart_Rate | Heart rate in beats per minute |

**Note:** This project uses fictional data for learning purposes only. No real patient information is included.

## 🔍 Project Workflow

### 1. Dataset Creation
Created a synthetic clinical dataset using the SAS DATA step and `DATALINES`.

### 2. Data Exploration
Used `PROC PRINT` to display patient records and `PROC CONTENTS` to inspect dataset variables and data types.

### 3. Descriptive Statistical Analysis
Used `PROC MEANS` to calculate:
- Mean
- Minimum
- Maximum
- Standard deviation

### 4. Missing Value Analysis
Used `N` and `NMISS` statistics to count nonmissing and missing numeric values.

### 5. Duplicate Record Detection
Used `PROC SORT` with `NODUPKEY` and `DUPOUT=` to identify duplicate patient IDs.

### 6. Data Validation
Checked patient ages against an illustrative valid range of 0–120 years.

### 7. Blood Pressure Quality Check
Applied predefined thresholds to flag potentially unusual blood pressure values for further review.

## 📈 Key Results

- Successfully created and explored 10 synthetic patient records.
- Calculated descriptive statistics for age, blood pressure, and heart rate.
- Found no missing values in the numeric variables checked.
- Found no duplicate patient IDs in the original dataset.
- Found no invalid ages based on the specified validation rules.
- Generated blood pressure review labels using predefined thresholds.

## 📂 Repository Structure

```text
Clinical-Dataset-Exploration-Using-SAS/
│
├── clinical_data_analysis.sas
└── README.md
```

The `.sas` file contains the SAS program used to create, explore, and validate the dataset.

## 🚀 How to Run the Project

1. Open SAS Studio.
2. Create a new SAS program.
3. Copy the code from `clinical_data_analysis.sas` into the editor.
4. Run the program.
5. Review the output in the Results tab and check the Log tab for errors or warnings.

## 📚 Learning Outcomes

Through this project, I gained practical experience with:

- Writing basic SAS programs.
- Creating datasets using the DATA step.
- Using SAS procedures for data exploration.
- Calculating descriptive statistics.
- Checking missing values and duplicate records.
- Applying validation rules to identify potential data quality issues.

## ⚠️ Disclaimer

This project is intended solely for educational purposes. The dataset is synthetic, and the blood pressure thresholds are illustrative data-quality rules, not medical diagnostic guidelines.

## 👩‍💻 Author

**Prithika Prakash**

Electronics and Communication Engineering Student

GitHub: [Add your GitHub profile link here]
