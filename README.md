# Exploratory Data Analysis (EDA) – Phase 1

## Overview
This project is part of the Exploratory Data Analysis (EDA) course project. The objective is to understand the dataset by performing statistical analysis, data cleaning, transformation, and visualization.

## Dataset
- **Dataset Name:** Gunnels.csv
- **Source:** https://raw.githubusercontent.com/salemprakash/EDA/main/Data/Gunnels.csv

## Tools and Libraries
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Project Workflow

### 1. Dataset Loading
- Imported the dataset using Pandas.
- Displayed the first few rows.
- Checked dataset dimensions and column names.

### 2. Basic Statistical Analysis
- Generated descriptive statistics using `describe()`.
- Examined data types using `info()`.
- Determined dataset size using `shape`.

### 3. Missing Value Analysis
- Checked for missing values using `isnull().sum()`.
- No missing values were found.

### 4. Data Cleaning
- Checked for duplicate records.
- Removed duplicate rows if present.

### 5. Data Transformation
- Verified that all columns were already stored in appropriate numeric data types.
- No datatype conversion was required.

### 6. Exploratory Data Analysis

#### Univariate Analysis
- Histogram
- Box Plot
- Count Plot

#### Bivariate Analysis
- Scatter Plot
- Box Plot
- Bar Plot

#### Multivariate Analysis
- Correlation Heatmap
- Pair Plot
- Scatter Plot with Hue

## Results
The analysis provided insights into the distribution of variables, relationships between features, and correlations within the dataset. The dataset was clean, with no missing values and appropriate data types.

## How to Run

1. Open the notebook in Google Colab.
2. Run all cells sequentially.
3. The dataset is loaded directly from GitHub, so no additional downloads are required.

## Author

Sanvi Saket
23BDS0210
B.Tech CSE (Data Science)
VIT Vellore
