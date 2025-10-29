# Customer Segmentation Clustering

## Description
This project performs **customer segmentation** using **K-Means clustering** on a dataset containing customer demographics and spending information. The goal is to identify distinct customer groups to guide marketing strategies and business decisions.

## Key Features & Steps

### 1. Data Cleaning & Preparation
- Checked for missing values and duplicates.
- Encoded categorical variables (`Gender` → 0/1).
- Selected features: `Gender`, `Age`, `Annual Income (k$)`, `Spending Score (1-100)`.

### 2. Exploratory Data Analysis (EDA)
- Visualized distributions (histograms, boxplots) and relationships (scatter plots, pairplots).
- Detected outliers and analyzed correlations between variables.

### 3. Data Standardization
- Standardized numerical features using `StandardScaler` for clustering.

### 4. Optimal K Selection
- Tested `k` values from 2 to 10.
- Used **Elbow method, Silhouette Score, Davies-Bouldin Index, Calinski-Harabasz Score**.
- Chose **k = 5** as the optimal number of clusters.

### 5. K-Means Clustering & Profiling
- Trained final K-Means model with `k=5`.
- Added cluster labels to the dataset.
- Profiled clusters to analyze average characteristics per segment.

### 6. Visualizations & Insights
- Scatter plots: `Annual Income vs Spending Score`, `Age vs Spending Score`.
- Pairplots and boxplots to explore clusters.
- Identified five distinct customer segments with unique demographics and spending patterns.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Outcome
- Provides actionable insights for customer segmentation.
- Supports targeted marketing, personalized services, and business strategy decisions.
