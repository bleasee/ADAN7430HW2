# ADAN7430HW2

# HW2 – Stroke Prediction (Kaggle)

## Overview
This project builds binary classification models to predict whether a patient is likely to experience a stroke using demographic and health features.

## Modeling Pipeline
- Data cleaning and one-hot encoding of categorical variables
- Train/validation split with stratification
- Logistic Regression as the primary model
- K-Nearest Neighbors as an alternative model
- Evaluation using Accuracy, Precision, Recall, F1, and ROC AUC

## Models Used
- Logistic Regression
- K-Nearest Neighbors (k=5)

## Evaluation Results (Validation Set)
See `Output/metrics.txt` for full results.

## Kaggle Performance
Here is a screenshot of my score on the Spring 2025 Classification Competition. However, I did not see my name or score on the leaderboard, likely because the competition closed in March 2025. 
<img width="1265" height="722" alt="Screenshot 2025-12-17 at 5 48 39 PM" src="https://github.com/user-attachments/assets/6a6ed4d7-c5a3-4f13-8946-4ef6941fe29b" />
<img width="1299" height="658" alt="Screenshot 2025-12-17 at 5 47 01 PM" src="https://github.com/user-attachments/assets/1fd3c589-9e90-4296-a062-2c5be42d3639" />


## Reflections
This project reinforced the importance of proper preprocessing, class imbalance awareness, and model comparison even with relatively simple algorithms.
