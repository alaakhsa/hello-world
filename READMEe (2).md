# LOAN Status Prediction
## Team members:
- Saeed 
- Alaa  Alsalman
- Arwa 

# Introduction

The goal of this project is to develop machine learning models that can predict LOAN Status, by using some of the background information of the applicant like the applicant’s gender, marital status, income, and education. By training and evaluating different models, we aim to identify the most accurate.


# Dataset Overview and Source

The dataset was sourced from https://www.kaggle.com/datasets/burak3ergun/loan-data-set . It contains a total of 614 rows and 13 columns.


The dataset was preprocessed and split into training and testing sets for model development and evaluation.

The dataset used for this project consists of information about mobile apps, including their reviews, number of installs, type (free or paid), price, and rating. The dataset was sourced from https://www.kaggle.com/datasets/lava18/google-play-store-apps. It contains a total of 10841 rows and 18 columns.

The dataset was preprocessed and split into training and testing sets for model development and evaluation.

# Model Evaluation Results

The table below summarizes the final results of the machine learning models evaluated in this project:

| Model                 | Accuracy | MAE   | MSE   | RMSE  |
|-----------------------|----------|-------|-------|-------|
| Logistic Regression   | 0.782    | 0.249 | 0.319 | 0.564 |
| Random Forest         | 0.725    | 0.310 | 0.391 | 0.625 |

Note: Accuracy represents the proportion of correct predictions, MAE measures the average absolute difference between predicted and actual values, MSE calculates the average squared difference, and RMSE is the square root of MSE.

The table provides a clear comparison of the performance metrics for each model, allowing for an easy assessment of their effectiveness in predicting app ratings.
