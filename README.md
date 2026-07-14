# Task 1-:Data Cleaning & Pre-procrssing

## Objective

The objective of this project is to clean and preprocess the Titanic dataset to improve its quality and prepare it for further data analysis, visualization, and machine learning applications. The project focuses on handling missing values, removing inconsistencies, optimizing data types, and ensuring the dataset is reliable for future use.

---

## Tools Used

* **Python**
* **Pandas** library
* **Jupyter Notebook**

---

## Steps Performed

### 1. Data Loading
- Imported the Pandas library.
- Loaded the Titanic dataset into a DataFrame.

### 2. Data Exploration
- Displayed the first few records using `head()`.
- Examined dataset information using `info()`.
- Generated summary statistics with `describe()`.
- Identified missing values using `isnull().sum()`.

### 3. Data Cleaning
- Filled missing values in the **Age** column using the mean.
- Filled missing values in the **Embarked** column using the mode.
- Removed the **Cabin** column because it contained a large number of missing values.
- Removed duplicate records to improve data quality.

### 4. Data Preprocessing
- Converted the **Age** column to integer type.
- Converted the **Survived** column to the category data type.
- Renamed columns for better readability:
  - `PassengerId` → `Passenger_Id`
  - `Pclass` → `Passenger_Class`
  - `Sex` → `Gender`

### 5. Export
- Saved the cleaned dataset as:

``
Cleaned_titanic_dataset.csv

## Outcome

After completing the preprocessing steps, the Titanic dataset became cleaner, more consistent, and better structured. Missing values and duplicate records were addressed, unnecessary data was removed, and data types were optimized. The final dataset is now suitable for:

* Exploratory Data Analysis (EDA)
* Data Visualization
* Statistical Analysis
* Machine Learning Model Development

---

## Key Insights

* Multiple columns contained missing values that required preprocessing.
* The **Cabin** column had a high percentage of null values and was removed.
* Duplicate records were identified and eliminated.
* Data types were optimized to improve analysis efficiency.
* Overall dataset quality and consistency improved significantly after preprocessing.

---

## Conclusion

This project demonstrates the importance of data cleaning and preprocessing as a foundational step in the data science workflow. By preparing the Titanic dataset through systematic preprocessing techniques, the data becomes reliable, consistent, and ready for meaningful analysis and predictive modeling.
