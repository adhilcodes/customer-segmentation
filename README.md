# Customer Segmentation Project

## Overview

This repository contains code and documentation for a customer segmentation project using machine learning techniques. The project aims to segment customers of an automobile company based on their behavior and characteristics, enabling the company to tailor marketing strategies to different customer groups.


## Data

- The dataset used in this project contains [details about customers](https://www.kaggle.com/datasets/vetrirah/customer) in the existing market.
- It includes 89 features and 11430 observations.

## Exploratory Data Analysis (EDA)

- Conducted EDA to understand the data, including summary statistics, data distributions, and correlations among features.
- Visualized data using histograms, box plots, heatmaps, and pair plots.
- Explored categorical features through bar plots.

## Data Preprocessing

- Handled missing values and outliers.
- Applied label encoding to categorical features.
- Standardized numerical features to prepare the data for clustering.

## Clustering

- Performed K-Means clustering to segment customers.
- Determined the optimal number of clusters using the Elbow Method.
- Evaluated cluster assignments and analyzed cluster sizes.

## Dimensionality Reduction

- Applied Principal Component Analysis (PCA) for dimensionality reduction.
- Conducted K-Means clustering on PCA components to visualize clusters in lower-dimensional space.

## Results and Visualization

- Visualized clustering results using scatter plots in 2D and 3D.
- Analyzed cluster characteristics and made inferences.
- Documented the project's findings and insights.

## Dependencies

- Python 3.x
- Libraries: NumPy, pandas, matplotlib, seaborn, scikit-learn, Plotly (for 3D visualization)


