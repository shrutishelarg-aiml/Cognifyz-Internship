# Level 1 - Task 1: Data Exploration and Preprocessing

## Overview

This task focuses on exploring and preprocessing the restaurant dataset to understand its structure, identify missing values, verify data types, and analyze the target variable.

## Objectives

- Explore the dataset and determine the number of rows and columns.
- Examine column names and data types.
- Identify missing values in each column.
- Handle missing values appropriately.
- Perform data type conversion if required.
- Analyze the distribution of the target variable (`Aggregate Rating`).
- Identify any class imbalance in the target variable.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Steps Performed

### 1. Dataset Exploration
- Loaded the dataset using Pandas.
- Checked the dataset shape.
- Examined column names and data types.

### 2. Missing Value Analysis
- Identified missing values in each column.
- Handled missing values in the `Cuisines` column.

### 3. Data Type Verification
- Verified data types of all columns.
- Confirmed that no major type conversion was required.

### 4. Target Variable Analysis
- Analyzed the distribution of the `Aggregate Rating` column.
- Created visualizations to understand rating patterns.
- Examined the frequency of different rating values.

### 5. Class Imbalance Check
- Investigated the distribution of ratings.
- Identified the presence of a large number of unrated restaurants (`0.0` rating), indicating class imbalance.

## Key Findings

- The dataset contains 9,551 restaurant records and 21 columns.
- Only a small number of missing values were found in the `Cuisines` column.
- Most columns already had appropriate data types.
- The target variable (`Aggregate Rating`) is not evenly distributed.
- A significant number of restaurants have a rating of `0.0`, indicating class imbalance.

## Conclusion

Data exploration and preprocessing provided a better understanding of the dataset and ensured that the data was ready for further analysis. The insights obtained from the target variable distribution will be useful for future data analysis and machine learning tasks.

## Author

Shruti Shelar