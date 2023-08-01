# Heart Disease Prediction Using Different Models

This project contains an exploration and comparison of various machine-learning models for predicting heart disease. Specifically, we examine Logistic Regression, K-Neighbors, and Random Forest classifiers to evaluate their performance in predicting the presence of heart disease.

## Introduction

Heart disease remains a leading cause of death globally. Early prediction is vital in managing and possibly preventing the disease. This project aims to compare the effectiveness of different models in predicting heart disease using a publicly available dataset.

## Data Exploration

The initial phase involves loading the dataset and performing a comprehensive exploratory analysis. Various visualizations like bar charts, pie charts, and distribution plots are used to understand the relationships between different variables such as age, gender, cholesterol levels, chest pain types, and the target variable (presence or absence of heart disease).
Source of the dataset: https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset

## Data Preparation & Modeling

The data is checked for missing values and split into training and testing sets. Three machine learning models are used for prediction:

1. **Logistic Regression**: A regression analysis method that predicts binary outcomes.
2. **K-Neighbors**: A non-parametric method used for classification, where classification is computed from a majority state of the nearest neighbors.
3. **Random Forest**: An ensemble learning method that combines multiple decision trees to produce more accurate predictions.

The models are evaluated using the f1 score, which provides insights into their precision and recall capabilities.

## Results

The Random Forest Classifier emerged as the most successful model, demonstrating superior performance compared to the other models. It was able to achieve an f1 score consistently above 97% on the test dataset.

## Getting Started

### Prerequisites

Ensure you have the following libraries installed:
- NumPy
- pandas
- Matplotlib
- seaborn
- scikit-learn

If running on Google Colab, there should be no need to install anything yourself.

### Running the Code

Clone the repository and run the Jupyter Notebook. Make sure the dataset (`heart.csv`) is available in the working directory.

