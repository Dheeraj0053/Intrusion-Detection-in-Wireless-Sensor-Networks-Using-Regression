# Intrusion Detection in Wireless Sensor Networks Using Regression

## Project Overview
This project focuses on predicting the number of barriers required to secure Wireless Sensor Networks (WSNs) based on network parameters using machine learning regression techniques. The dataset includes features like the area of the WSN, sensing and transmission ranges, and the number of sensor nodes.

## Features
- **Dataset:** 182 samples from the UCI Machine Learning Repository.
- **Regression Techniques Explored:**
  - Linear Regression
  - Decision Trees
  - Random Forest
  - Support Vector Machines (SVM) with various kernels
  - AdaBoost
  - Gradient Boosting
- **Best Model:** Gradient Boosting, achieving:
  - Mean Squared Error: 42.55
  - R² Score: 0.988

## Highlights
1. **Baseline Models:** Initial experiments with default hyperparameters.
2. **Hyperparameter Tuning:** Optimized models for better performance.
3. **Feature Reduction:** Applied PCA to reduce dimensions while maintaining high accuracy.
4. **Feature Selection:** Used SelectPercentile to retain the most impactful features.
5. **Data Visualization:** Implemented t-SNE for 2D visualization of feature distributions.

