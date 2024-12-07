# Customer Demographics and Purchase Behavior Analysis

## Overview

This repository contains the source code and documentation for the dissertation project **"Investigating Customer Demographics and Purchase Behavior: Offer Acceptance Analysis and Segmentation Using Machine Learning Techniques"**. The study explores the impact of data preprocessing techniques on customer behavior analysis, focusing on predictive modeling and segmentation using machine learning.

## Objectives

The project aims to:
1. Analyze how data preprocessing techniques (e.g., standardization, class imbalance handling, feature engineering) affect the performance of machine learning models.
2. Develop and compare predictive models to identify customer churn and offer acceptance patterns.
3. Perform customer segmentation to understand demographic and purchase behavior better.

## Key Features

- **Exploratory Data Analysis (EDA):** Comprehensive data analysis to uncover patterns and insights.
- **Data Preprocessing:** Techniques including handling missing values, standardizing numerical data, and addressing class imbalances using SMOTETomek.
- **Predictive Modeling:** Implementation of machine learning models like Logistic Regression, Random Forest, K-Nearest Neighbors, and XGBoost.
- **Customer Segmentation:** Using K-Means clustering to group customers based on demographic and behavioral data.
- **Performance Evaluation:** Metrics like accuracy, precision, recall, F1-score, ROC curve, and confusion matrix.

## Data

The dataset used for this study is sourced from Kaggle's Customer Personality Analysis dataset. It includes customer demographic details, purchase history, and campaign responses.

- **Old Dataset:** Raw features without preprocessing.
- **New Dataset:** Preprocessed data with engineered features, balanced classes, and standardized numerical variables.

## Methodology

1. **Data Preprocessing:** Address missing values, outliers, and data inconsistencies; perform scaling and class balancing.
2. **Exploratory Data Analysis:** Univariate, bivariate, and multivariate analyses to explore data distributions and relationships.
3. **Feature Engineering:** Derive meaningful features to enhance model performance.
4. **Model Training and Testing:** Train machine learning models on preprocessed datasets and evaluate their performance.
5. **Customer Segmentation:** Identify key customer groups and analyze their behavior patterns.

## Results

- **Predictive Models:** XGBoost and Random Forest outperformed other models, achieving the highest accuracy and balanced performance across classes.
- **Segmentation Insights:** High-income customers (Response 1) showed greater engagement and spending, suggesting targeted marketing potential.

## References

- Original dataset: [Kaggle - Customer Personality Analysis](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis)
- Dissertation supervisor: Dr. Sema Gunturkun

## Acknowledgments

This project was conducted as part of the MSc program in Data Science at the University of Essex, Department of Mathematical Sciences.
