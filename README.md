# Exploratory Data Analysis: All the Intermediate Colleges in Pakistan
This project provides a detailed Exploratory Data Analysis (EDA) of a dataset containing information about intermediate colleges in Pakistan. The goal is to understand the structure, patterns, and key insights within the data, and to prepare it for potential future applications such as machine learning or dashboarding.
## Dataset Description
The dataset includes various attributes of intermediate colleges, such as:
* Name
* Location
* Rating
* Study Program
* Sector
* Affiliation
## Key Steps Performed
### 1. Data Loading and Inspection
  * Loaded the dataset using pandas.
  * Viewed sample records with .head() and .tail().
  * Checked the dataset shape, column types, and summary statistics.
### 2. Data Cleaning
  * Detected and handled missing values.
  * Filled missing values where appropriate.
  * Converted "Rating" from string to float type.
  * Inferred missing "Sector" values from college names, If college name contains Govt then it fill NA with public otherwise Unkown.
### 3. Feature Classification
  * Identified categorical and numerical columns.
  * Counted unique values in each column.
### 4. Outlier Detection
  * Visualized outliers using boxplots.
### 5. Data Visualization
* Used seaborn and matplotlib for plotting:
  * Bar plots for top Study Programs.
  * Boxplots for rating distribution by Study Program.
  * Correlation heatmap for multivariate numerical features.
## Requirements
* Python
* pandas
* numpy
* seaborn
* matplotlib
* jupyter (for notebook use)
