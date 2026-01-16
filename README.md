# Elevate_Task2

# Task 2: Data Cleaning & Missing Value Handling

# Project Overview

This task focuses on cleaning and validating a real-world dataset to ensure it is suitable for data analysis and machine learning. The primary goal is to identify missing values, handle them appropriately, and verify overall data quality.

# Dataset Used

Medical Appointment No Shows Dataset

Source: Kaggle

File name: KaggleV2-May-2016.csv

Description:
The dataset contains medical appointment records, including patient details, appointment scheduling information, and whether the patient showed up for the appointment.

# Tools & Technologies

Python

Pandas

NumPy

Matplotlib

# Objectives

Identify missing values in the dataset

Visualize missing data patterns

Handle missing values using appropriate techniques

Perform data quality checks

Validate the dataset after cleaning

# Steps Performed

1. Load Dataset

The dataset is loaded using Pandas and basic inspection is performed to understand its structure.

2. Identify Missing Values

Column-wise missing values are identified using built-in Pandas functions.

Observation:
No missing values were found in any column.

3. Visualize Missing Values

A bar chart is used to visualize missing values across columns.
Since all columns contain zero missing values, the graph appears empty, indicating good data quality.

4. Data Quality Validation

Additional checks were performed to improve data reliability:

Removed records with invalid (negative) age values

Converted date columns to datetime format

Checked and removed duplicate records

5. Handle Missing Values

As no missing values were present, imputation techniques such as mean, median, or mode were not required. This step was included as a validation measure.

6. Final Validation

The dataset was rechecked after cleaning to ensure:

No missing values exist

All records are valid and consistent

# Results

Dataset contains zero missing values

Invalid records were removed

Data consistency improved

Dataset is ready for Exploratory Data Analysis (EDA) and machine learning


# Conclusion

The Medical Appointment No Shows dataset was found to be well-maintained with no missing values. Minor data validation steps ensured improved quality and readiness for further analysis.


# Outputs

<img width="812" height="563" alt="Image" src="https://github.com/user-attachments/assets/8f98f511-69a5-4e38-9133-f905c4c1da3c" />

<img width="894" height="589" alt="Image" src="https://github.com/user-attachments/assets/240193cb-4884-4ec3-a920-8206adf1e7bd" />
