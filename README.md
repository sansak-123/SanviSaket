# Exploratory Data Analysis (EDA) – Phase 1, Phase 2 & Phase 3

## Overview

This project is part of the **BCSE331L - Exploratory Data Analysis (TH)** course project. The objective is to understand and analyze the **Gunnels.csv** dataset through statistical analysis, data cleaning, transformation, visualization, dimensionality reduction, manifold learning, and clustering techniques.

The project is divided into three phases:

- **Phase I:** Exploratory Data Analysis and Visualization
- **Phase II:** Statistical Analysis and Clustering
- **Phase III:** Dimensionality Reduction, Manifold Learning, and Regression Analysis

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

---

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

---

# Phase III – Dimensionality Reduction, Manifold Learning and Regression Analysis

### 1. Principal Component Analysis (PCA)

PCA was applied to reduce the dimensionality of the numerical dataset while preserving as much variance as possible.

The analysis included:

- Feature standardization
- Calculation of principal components
- Explained variance ratio
- Cumulative explained variance
- Visualization of principal components
- Analysis of dimensionality reduction

### 2. Singular Value Decomposition (SVD)

SVD was performed to decompose the numerical data matrix into its constituent matrices.

The analysis included:

- Matrix decomposition
- Singular value calculation
- Identification of important components
- Understanding the relationship between SVD and dimensionality reduction

### 3. Factor Analysis and Intrinsic Dimensionality

Factor Analysis was used to investigate underlying factors that explain relationships among the observed numerical variables.

The analysis included:

- Identification of latent factors
- Factor-based representation of variables
- Examination of the underlying structure of the dataset
- Exploration of intrinsic dimensionality

### 4. Multidimensional Scaling (MDS)

MDS was applied to represent high-dimensional observations in a lower-dimensional space while preserving their pairwise distances as much as possible.

The analysis included:

- Calculation of pairwise distances
- Dimensionality reduction
- Two-dimensional visualization
- Examination of similarities and differences between observations

### 5. Manifold Learning – Isomap and LLE

Manifold learning techniques were explored to understand the nonlinear structure of the dataset.

The methods included:

**Isomap (Isometric Mapping)**

- Construction of a neighborhood graph
- Calculation of geodesic distances
- Dimensionality reduction
- Visualization of the lower-dimensional representation

**Locally Linear Embedding (LLE)**

- Identification of nearest neighbors
- Calculation of local reconstruction weights
- Preservation of local neighborhood relationships
- Lower-dimensional visualization

### 6. Self-Organizing Map (SOM)

A Self-Organizing Map was used to explore the organization and grouping of observations in a lower-dimensional representation.

The analysis included:

- Feature preparation and standardization
- SOM initialization
- Training the SOM
- Mapping observations to neurons
- Visualization of the resulting map
- Examination of similarities and patterns among observations

### 7. Simple Linear Regression (SLR)

Simple Linear Regression was implemented to examine the relationship between two numerical variables.

The selected variables were:

- **Independent Variable (X):** Fromlow
- **Dependent Variable (Y):** Time

The analysis included:

- Data preparation
- Training and testing data separation
- Model training
- Prediction generation
- Actual versus predicted value comparison
- Regression line visualization
- Residual analysis

Model performance was evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R-squared (R²)

---

# Results

The three phases provided a comprehensive understanding of the Gunnels.csv dataset through exploratory analysis, statistical methods, clustering, dimensionality reduction, and regression.

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

### Phase III Results

The third phase extended the analysis by exploring dimensionality reduction, nonlinear data structures, and predictive modelling.

The analysis provided insights into:

- Dimensionality reduction and variance preservation using PCA
- Matrix decomposition and singular values using SVD
- Latent variable relationships using Factor Analysis
- Lower-dimensional distance-preserving representations using MDS
- Nonlinear manifold structures using Isomap and LLE
- Observation organization and grouping using SOM
- Predictive relationships between Fromlow and Time using Simple Linear Regression

Regression performance was evaluated using MAE, MSE, RMSE, and R² to understand prediction errors and model performance.

Overall, Phase III extended the project beyond traditional exploratory and statistical analysis by introducing advanced data analysis and machine learning techniques.

---

# How to Run

1. Open the notebooks in Google Colab.
2. Run all cells sequentially.
3. The dataset is loaded directly from GitHub, so no additional dataset download is required.
4. Run the Phase I, Phase II, and Phase III sections to reproduce the complete analysis.

## Author

**Sanvi Saket**  
**23BDS0210**  
B.Tech CSE (Data Science)  
VIT Vellore
