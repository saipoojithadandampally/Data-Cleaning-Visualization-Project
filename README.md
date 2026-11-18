# Data-Cleaning-Visualization-Project
Data cleaning, preprocessing, exploratory data analysis and visualization using Python, Pandas, Matplotlib and Seaborn.

# Data Cleaning and Visualization Project

## 1. Project Overview

This project focuses on cleaning, processing, analyzing, and visualizing a raw dataset using Python. The Titanic Passenger Dataset is used to demonstrate data preprocessing techniques and extract meaningful insights through exploratory data analysis (EDA).

The project identifies missing values, handles duplicate records, detects and treats outliers, and presents important findings through different visualizations.

## 2. Objectives

- Identify and handle missing values.
- Detect and remove duplicate records.
- Identify outliers using the IQR method.
- Perform data preprocessing and cleaning.
- Conduct Exploratory Data Analysis (EDA).
- Create meaningful visualizations.
- Extract useful insights from the dataset.

## 3. Dataset Description

Dataset: Titanic Passenger Dataset

The dataset contains information about passengers who travelled on the Titanic.

Important attributes include:
- Age
- Sex
- Passenger Class
- Fare
- Embarkation Port
- Survival Status

## 4. Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## 5. Project Methodology

### Step 1: Data Collection
Loaded the Titanic dataset in CSV format.

### Step 2: Data Inspection
Examined dataset dimensions, column names, data types, and statistical summaries.

### Step 3: Missing Value Analysis
Identified missing values and handled them using median and mode imputation. Removed the high-missingness deck column.

### Step 4: Duplicate Detection
Identified and removed duplicate rows.

### Step 5: Outlier Detection
Used boxplots and the Interquartile Range (IQR) method to identify unusual numerical values.

### Step 6: Outlier Treatment
Applied IQR-based capping to the age and fare columns.

### Step 7: Exploratory Data Analysis
Analyzed passenger survival, gender distribution, passenger class, age, and fare.

### Step 8: Data Visualization
Created bar charts, histograms, boxplots, and correlation heatmaps using Matplotlib and Seaborn.

## 6. Visualizations

The project includes:
- Missing Values Heatmap
- Outlier Detection Boxplots
- Passenger Survival Analysis
- Survival by Gender
- Survival by Passenger Class
- Age Distribution
- Correlation Heatmap
- Final Analysis Dashboard

## 7. Key Findings

The analysis explores:
- The distribution of passenger survival.
- Differences in survival across genders.
- Survival patterns across passenger classes.
- Passenger age distribution.
- Relationships between numerical features.

## 8. Project Files

- `Data_Cleaning_and_Visualization.ipynb` – Complete Python implementation.
- `cleaned_titanic_dataset.csv` – Processed dataset.
- `titanic_dashboard.png` – Final visualization dashboard.

## 9. Conclusion

This project demonstrates the importance of data cleaning and preprocessing before performing data analysis. By handling missing values, removing duplicate records, treating outliers, and creating visualizations, meaningful patterns and insights can be extracted from raw data.

The project provided practical experience in Python programming, data preprocessing, exploratory data analysis, and data visualization.

## 10. Author

BTech - Computer Science and Machine Learning

Project: Data Cleaning and Visualization

