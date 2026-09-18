# Pandas Data Analysis Practice

This repository contains my hands-on practice with **Pandas**, one of the most widely used Python libraries for data analysis and manipulation.

The purpose of this repository is to build a strong foundation in Pandas by working with Series, DataFrames, data selection, filtering, missing values, sorting, aggregation, and groupby operations.

## Topics Covered

* Creating Pandas Series
* Creating Series with Custom Index
* Creating DataFrames
* Taking User Input to Create DataFrames
* Inspecting DataFrames
* Selecting Rows and Columns
* Using `loc` and `iloc`
* Filtering Data
* Adding and Deleting Columns
* Handling Missing Values
* Sorting Data
* Aggregation Functions
* Department-wise Data Analysis using `groupby()`

## Pandas Operations Practiced

Some of the important Pandas functions and methods practiced in this repository are:

```python
pd.Series()
pd.DataFrame()
df.head()
df.tail()
df.shape
df.columns
df.dtypes
df.info()
df.describe()
df.loc[]
df.iloc[]
df.isnull()
df.dropna()
df.fillna()
df.sort_values()
df.groupby()
df.sum()
df.mean()
df.max()
df.min()
df.count()
```

## Example Analysis

The practice includes working with student and employee datasets.

### Student Data

The student DataFrame includes information such as:

* Roll Number
* Name
* Age
* Marks
* Grade

Operations performed include filtering students based on marks, calculating average marks, finding maximum and minimum marks, and handling missing values.

### Employee Data

The employee DataFrame includes:

* Employee Name
* Department
* Salary

Department-wise salary analysis is performed using `groupby()` to calculate:

* Average Salary
* Maximum Salary
* Minimum Salary

Example:

```python
df.groupby("department")["salary"].agg(["mean", "max", "min"])
```

## Technologies Used

* Python
* Pandas
* Jupyter Notebook

## Learning Objective

The main objective of this repository is to strengthen my practical understanding of Pandas and develop the data manipulation skills required for **Data Science and Machine Learning**.

This repository represents my learning and practice journey as I continue building my skills in Python and Data Analysis.

## Repository Contents

```text
Pandas-Data-Analysis-Practice/
│
├── Pandas_Practice.ipynb
└── README.md
```

## Future Learning

I plan to continue building on these concepts by practicing:

* NumPy
* Data Cleaning
* Data Visualization
* Matplotlib
* Seaborn
* Exploratory Data Analysis (EDA)
* Machine Learning with Scikit-learn

---

**Learning by practicing, one dataset at a time.**
