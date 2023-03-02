# Predicting Coupon Redemption

This project is a machine learning project that aims to predict whether or not a customer will redeem a coupon based on customer demographics and the campaign used to distribute the coupon.

## Project Overview

The project is divided into two parts:

1. Data Exploration and Preprocessing
2. Model Training and Evaluation

The data was obtained from the Analytics Vidhya website, and it contains customer demographic information, coupon distribution campaigns, and coupon redemption data.

The objective of this project is to build a classification model that accurately predicts whether or not a customer will redeem a coupon. To achieve this, we will use an XGBoost classifier and perform grid search optimization to determine the best hyperparameters.

## Data Exploration and Preprocessing

In this section, we explored the data and performed the following preprocessing steps:

- Handle missing values
- Convert date columns to datetime format
- One-hot encode categorical features
- Assign values to age, family size, and number of children columns
- Drop unnecessary columns

## Model Training and Evaluation

In this section, we trained an XGBoost classifier using the preprocessed data. We performed grid search optimization to find the best hyperparameters, and we evaluated the model's performance using accuracy, precision, recall, and F1 score.

The final model achieved an accuracy of 0.94, a precision of 0.87, a recall of 0.56, and an F1 score of 0.68.

## Conclusion

This project demonstrated how to preprocess data and build a classification model to predict coupon redemption. The final model achieved an accuracy of 0.94, which suggests that it can accurately predict whether or not a customer will redeem a coupon based on customer demographics and the campaign used to distribute the coupon.
