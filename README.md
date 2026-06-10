# Social Network Ads Purchase Prediction

This project uses a machine learning classification model to predict whether a user will purchase a product based on their **Gender**, **Age**, and **Estimated Salary**.

## Project Overview

The goal of this project is to build a simple binary classification model that predicts the `Purchased` column:

* `0` = User did not purchase
* `1` = User purchased

This is a beginner-friendly machine learning project using Scikit-learn pipelines and preprocessing techniques.

## Dataset

The dataset contains the following columns:

| Column          | Description                            |
| --------------- | -------------------------------------- |
| User ID         | Unique user identifier                 |
| Gender          | Gender of the user                     |
| Age             | Age of the user                        |
| EstimatedSalary | Estimated salary of the user           |
| Purchased       | Whether the user purchased the product |

For model training, the `User ID` column was not used because it is only an identifier and does not provide meaningful predictive information.

## Features and Target

### Features

The model uses the following input features:

```text
Gender
Age
EstimatedSalary
```

### Target

```text
Purchased
```

## Technologies Used

* Python
* Pandas
* Scikit-learn
* Jupyter Notebook

## Model Used

The model used in this project is:

```text
Logistic Regression
```

Logistic Regression was chosen because this is a binary classification problem where the target column has two possible values: `0` and `1`.

## Results

The model achieved an accuracy of:

```text
88%
```

### Confusion Matrix

```text
[[48  3]
 [ 7 22]]
```

### Classification Report

```text
              precision    recall  f1-score   support

           0       0.87      0.94      0.91        51
           1       0.88      0.76      0.81        29

    accuracy                           0.88        80
   macro avg       0.88      0.85      0.86        80
weighted avg       0.88      0.88      0.87        80
```

## Conclusion

This project demonstrates a basic machine learning classification workflow using Logistic Regression. It includes preprocessing, model training, prediction, and evaluation.

The final model achieved 88% accuracy, making it a strong beginner-level machine learning project suitable for GitHub.
::: 
