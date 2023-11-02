# Unsupervised-Learning for Near-Earth Objects (NEOs)

## Description
This project focuses on the analysis of Near-Earth Objects (NEOs) using unsupervised learning techniques. The primary goal is to utilize methods like clustering and Principal Component Analysis (PCA) to uncover underlying patterns and groupings in NEO data. These techniques help in understanding the characteristics of NEOs such as their diameter, velocity, miss distance from Earth, and identifying potentially hazardous objects.

## Data Source
The analysis is based on the `neo.csv` dataset, which includes details like estimated diameter, relative velocity, miss distance, and whether the object is considered potentially hazardous. The data was sourced from Kaggle ([https://neo.jpl.nasa.gov/](https://www.kaggle.com/code/adityadeepak/nasa-neo)), providing a comprehensive understanding of NEOs that come close to Earth.

## Methodology
The project is structured into three main parts:

### 1. Data Preprocessing and EDA
- Cleaning the data by handling missing values and outliers.
- Conducting exploratory data analysis to understand the distribution and relationships between various features.

### 2. Feature Engineering
- Creating new features that may help in better analysis and predictions, such as categorizing objects based on their size or computing the kinetic energy based on diameter and velocity.

### 3. Models
- Applying different unsupervised learning techniques like clustering to group NEOs based on similarities in their features.
- Using PCA to reduce the dimensionality of the data and to identify the principal components that capture the most variance in the dataset.

## Results
The findings from the EDA are presented in the form of visualizations and statistical summaries. Insights on the distribution of NEO sizes, potential hazards, and the groupings from clustering are discussed. The PCA results are also analyzed to understand the data's structure and the contribution of different features to the variance.

## Future Improvements
- **In-depth Cluster Analysis**: Further analysis of the clusters found during the unsupervised learning phase to better understand the defining characteristics of each group. This can include statistical analysis and profiling of clusters to determine common traits and anomalies within the data.
- **Predictive Modeling**: Building supervised learning models to predict the potential hazard of NEOs based on cluster membership and other features.
- **Temporal Analysis**: Investigating the change in NEO characteristics over time to predict trends and future occurrences.


