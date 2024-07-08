# Homestays Data Analysis and Price Prediction

## Introduction

This repository encompasses the Homestays Data Analysis and Price Prediction project. The core objective revolves around constructing a robust predictive model to estimate the `log_price` of homestay listings through an exhaustive analysis of their attributes, amenities, and host information.

## Tasks Overview

### 1. Feature Engineering

- Derived `Host_Tenure`, `Amenities_Count`, and `Days_Since_Last_Review` to enrich the dataset.

### 2. Exploratory Data Analysis (EDA)

- Explored correlations between pricing (`log_price`) and various features.
- Employed statistical tools and visualizations for exploration.

### 3. Geospatial Analysis

- Investigated regional pricing trends using geographical data.
- Visualized price distribution on a map and analyzed neighborhood influences.

### 4. Sentiment Analysis on Textual Data

- Extracted sentiment scores from `description` texts to evaluate their impact on listing prices.

### 5. Amenities Analysis

- Analyzed the relationship between amenities and prices utilizing statistical tests.

### 6. Categorical Data Encoding

- Transformed categorical data into a suitable format for machine learning analysis using one-hot encoding.

### 7. Model Development and Training

- Designed and trained predictive models such as linear regression, RandomForest, and GradientBoosting.
- Documented the model-building process and rationale.

### 8. Model Optimization and Validation

- Optimized models using techniques like grid search and validated choices through cross-validation.

### 9. Feature Importance and Model Insights

- Analyzed trained models using SHAP values to identify significant features impacting `log_price`.

### 10. Predictive Performance Assessment

- Evaluated the performance of the final model using metrics like RMSE and R-squared.