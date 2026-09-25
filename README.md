# Exploratory Data Analysis (EDA) – Phase 1 & Phase 2

## Overview

This project is part of the **BCSE331L - Exploratory Data Analysis (TH)** course project. The objective is to understand and analyze the **Gunnels.csv** dataset through statistical analysis, data cleaning, transformation, visualization, and clustering techniques.

The project is divided into two phases:

- **Phase I:** Exploratory Data Analysis and visualization
- **Phase II:** Statistical analysis and clustering

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
- Scikit-learn
- SciPy

## Project Workflow

# Phase I – Exploratory Data Analysis

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

- Verified that the columns were stored in appropriate numeric data types.
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

---

# Phase II – Statistical Analysis and Clustering

### 1. 1D Statistical Analysis

Performed detailed statistical analysis on the numerical variables, including:

- Mean
- Median
- Mode
- Variance
- Standard Deviation
- Minimum and Maximum
- First Quartile (Q1)
- Third Quartile (Q3)
- Interquartile Range (IQR)
- Skewness
- Kurtosis

Visual analysis was performed using:

- Box plots
- Histograms
- Distribution plots

### 2. 2D Statistical Analysis

Performed pairwise statistical analysis to study relationships between numerical variables.

The analysis included:

- Covariance
- Correlation
- Pearson correlation
- Correlation matrix
- Correlation heatmap
- Scatter plots
- Regression-based relationship visualization

### 3. 3D Statistical Analysis

Three numerical variables were analyzed simultaneously using 3D visualization.

The analysis included:

- 3D scatter plots
- Three-variable relationship analysis
- Correlation analysis among the selected variables

The variables used for the 3D analysis include:

- Time
- Fromlow
- Slope

### 4. K-Means Clustering

K-Means clustering was applied to group observations based on their numerical characteristics.

The workflow included:

- Feature selection
- Feature standardization using `StandardScaler`
- Determination of the number of clusters using the Elbow Method
- K-Means clustering
- Cluster assignment
- Cluster-wise statistical analysis
- 3D cluster visualization

### 5. Hierarchical Clustering

Hierarchical clustering was performed to identify groups of similar observations.

The analysis included:

- Feature standardization
- Ward linkage
- Hierarchical clustering
- Dendrogram visualization
- Selection of clusters
- Cluster-wise analysis
- Visualization of the resulting clusters

## Results

The analysis provided insights into the distribution, variability, relationships, and clustering structure of the dataset.

### Phase I Results

The exploratory analysis helped identify:

- Distribution of individual variables
- Relationships between pairs of variables
- Correlations among numerical variables
- Overall structure and characteristics of the dataset

The dataset was found to have no missing values, and the variables were in appropriate numeric formats.

### Phase II Results

The statistical analysis provided additional information about:

- Central tendency and dispersion of numerical variables
- Distribution characteristics through skewness and kurtosis
- Relationships between numerical variables through covariance and correlation
- Three-dimensional relationships among selected variables

The clustering analysis further grouped observations based on their numerical characteristics using both **K-Means** and **Hierarchical Clustering**.

The Elbow Method was used to examine an appropriate number of clusters for K-Means, while a dendrogram was used to visualize the hierarchical clustering structure.

## How to Run

1. Open the notebook in Google Colab.
2. Run all cells sequentially.
3. The dataset is loaded directly from GitHub, so no additional dataset download is required.
4. Run both Phase I and Phase II sections to reproduce the complete analysis.

## Author

**Sanvi Saket**  
**23BDS0210**  
B.Tech CSE (Data Science)  
VIT Vellore
