Data Cleansing and Profiling using Python

Overview

This repository contains a structured approach to data cleansing and profiling techniques using Python. The tasks focus on cleaning and analyzing customer transaction data to improve data quality and reliability.

Scenario

Your team has been hired to clean and analyze a dataset containing customer transaction information. The dataset includes common data quality issues such as missing values, inconsistent formatting, duplicate entries, and outliers. The goal is to implement various data cleansing and profiling techniques to ensure accuracy and consistency.

Tasks Breakdown

The task is divided into 10 smaller tasks, each worth 4 marks. The tasks should be completed as a group, with well-documented code and clear explanations of outputs.

1. Import and Explore the Dataset

Load the dataset (customer_transactions.csv).

Display the first 10 rows and summarize its structure (columns, data types, missing values).

Deliverable: Summary report on the dataset.

2. Identify and Handle Missing Values

Identify columns with missing values and their percentage.

Fill missing values with appropriate substitutes (e.g., mean, median, mode).

Deliverable: Updated dataset with missing values handled.

3. Check for Duplicates

Identify duplicate rows.

Remove duplicates and count how many were removed.

Deliverable: Cleaned dataset with duplicates removed.

4. Standardize Column Names

Ensure all column names are consistent (e.g., lowercase, no spaces, or special characters).

Deliverable: Dataset with standardized column names.

5. Correct Data Types

Identify and convert incorrect data types (e.g., dates as strings, numeric values as objects).

Deliverable: Dataset with corrected data types.

6. Detect and Handle Outliers

Use boxplots to detect outliers in numerical columns.

Replace or remove outliers using appropriate techniques.

Deliverable: Clean dataset with outliers handled.

7. Validate and Clean String Data

Check for inconsistencies in string columns (e.g., state names, customer IDs).

Standardize the format of string data.

Deliverable: Dataset with cleaned string columns.

8. Identify and Remove Irrelevant Features

Identify columns with no significant contribution to analysis (e.g., constant columns).

Remove irrelevant columns from the dataset.

Deliverable: Dataset with irrelevant features removed.

9. Generate a Data Quality Report

Summarize the data cleansing steps performed (missing values, duplicates, outliers, etc.).

Include visualizations (e.g., bar charts for missing values, boxplots for outliers).

Deliverable: Comprehensive data quality report.

10. Profile the Dataset

Perform basic profiling using Python (e.g., Pandas Profiling, summary statistics).

Highlight key insights (e.g., distribution of numerical data, correlations).

Deliverable: Profiling report with visualizations and insights.
