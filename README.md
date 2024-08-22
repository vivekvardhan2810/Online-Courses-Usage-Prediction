# Online Courses Usage Analysis and Prediction

This project aims to analyze and predict trends in online courses usage using various machine learning models including LSTM, K-Nearest Neighbors (KNN), and K-Means Clustering. The dataset provided includes various features related to online learning platforms, user activity, and other relevant factors.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Requirements](#requirements)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Data Preprocessing](#data-preprocessing)
- [Modeling](#modeling)
  - [LSTM Model](#lstm-model)
  - [K-Nearest Neighbors (KNN) Model](#k-nearest-neighbors-knn-model)
  - [K-Means Clustering](#k-means-clustering)
- [Visual Reporting](#visual-reporting)
- [Analysis](#analysis)
  - [Trends in Online Learning](#trends-in-online-learning)
  - [Comparison of Platforms](#comparison-of-platforms)
- [Results and Conclusion](#results-and-conclusion)

## Project Overview
The objective of this project is to analyze historical data on online courses usage and build predictive models to understand trends, compare platforms, and make future predictions. The project involves the following key tasks:
- Exploratory Data Analysis (EDA)
- Data preprocessing
- Training models (LSTM, KNN, K-Means Clustering)
- Visual reporting and analysis
- Predictive modeling

## Dataset
The dataset used in this project contains features such as:
- `feature1`: Description of feature 1
- `feature2`: Description of feature 2
- `target_column`: The target variable for prediction
- `date_column`: Date information for time series analysis
- `platform_column`: Categorical variable representing different online platforms

*Note: Replace `feature1`, `feature2`, etc., with the actual column names from your dataset.*

**Credits**: https://www.kaggle.com/datasets/mitul1999/online-courses-usage-and-history-dataset

## Requirements
To run the project, you need to install the following Python libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- keras (for LSTM)

You can install the required packages using:
```
$ pip install pandas numpy matplotlib seaborn scikit-learn keras
```

## Exploratory Data Analysis (EDA)
The project begins with an EDA to understand the dataset, visualize correlations, and identify any missing values. Various plots such as correlation matrix, histograms, and box plots are used to analyze the data.

## Data Preprocessing
Data preprocessing steps include:
- Handling missing values
- Converting categorical variables to numerical
- Standardizing the data
- Splitting the data into training and testing sets

## Modeling

### LSTM Model
A Long Short-Term Memory (LSTM) model is used to predict future trends based on historical data. The LSTM model is trained and evaluated, with its performance measured by accuracy.

### K-Nearest Neighbors (KNN) Model
A KNN classifier is built to predict the target variable based on the features. The model is trained and its accuracy is calculated to evaluate performance.

### K-Means Clustering
K-Means Clustering is used to group the data into clusters based on similarities in features. The silhouette score is used to evaluate the effectiveness of the clustering.

## Visual Reporting
The project includes visual reporting with plots to illustrate trends, model training history, and clustering results. This helps in interpreting the model outputs and making data-driven decisions.

## Analysis

### Trends in Online Learning
A time series analysis is conducted to identify trends in online learning over time. This helps in understanding how user activity changes across different periods.

### Comparison of Platforms
Box plots and other visualizations are used to compare different online learning platforms, providing insights into their performance and user engagement.

## Results and Conclusion
The project concludes with a summary of the model performances and insights gained from the analysis. The accuracy of the models is reported, with a target accuracy of 80% and above.
