# German Credit Risk Analysis
## Overview
This project focuses on developing a credit risk classification model using the Statlog (German Credit Data) dataset. The goal is to predict whether a customer is a good (1) or bad (2) credit risk. Various machine learning models are applied after preprocessing, feature selection, and transformation techniques.

## Project Workflow

### Data Preprocessing

1. Imported data and checked Information Value (IV) for feature selection.
2. Selected features with IV between 0.02 and 0.6.
3. Created bins for bivariate analysis.
4. Transformed feature values using Weight of Evidence (WoE).

### Feature Selection

1. Selected features based on bivariate graphs while ensuring monotonicity.
2. Applied LASSO for dimensionality reduction.
3. Evaluated feature importance using correlation matrices.

### Model Training & Evaluation

1. Logistic Regression: Used as a baseline model for performance comparison.
2. Random Forest: Applied for robust classification and feature importance analysis.
3. Artificial Neural Networks (ANN): Trained with multiple layers for deep learning-based classification.
Model evaluation performed using Accuracy, Precision, Recall, F1-Score, and AUC-ROC.

## Results & Conclusion

1. Random Forest achieved the best balance between accuracy, generalizability, and efficiency.
2. ANN performed well but required extensive tuning.
3. Logistic Regression was effective but less suitable for complex patterns.

## Final Decision: 
Random Forest is the most suitable model for this dataset.

### Data Source :
https://archive.ics.uci.edu/dataset/144/statlog+german+credit+data

