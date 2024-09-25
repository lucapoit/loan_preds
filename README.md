# Loan Repayment Prediction - LendingClub Dataset

This project aims to predict whether a borrower will pay back their loan using data from the LendingClub dataset. The focus of the project is on data transformation, which includes significant data cleaning and feature engineering steps. The final model was built using a Sequential Neural Network.

## Table of Contents
- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Data Overview](#data-overview)
- [Data Cleaning and Feature Engineering](#data-cleaning-and-feature-engineering)
- [Modeling](#modeling)
- [Results](#results)
- [How to Use](#how-to-use)
- [Conclusion](#conclusion)

## Introduction
The LendingClub dataset contains financial data related to personal loans. The goal of this project is to classify whether or not a borrower will be able to repay their loan, providing insights that could help lending institutions better assess the risk of borrowers.

## Technologies Used
The following libraries and tools were used in this project:
- **pandas**: For data manipulation and cleaning.
- **matplotlib**: For data visualization.
- **seaborn**: For creating informative statistical plots.
- **scikit-learn (sklearn)**: For machine learning utilities, including splitting the dataset and evaluating the model.
- **numpy**: For numerical computations.
- **tensorflow**: For building and training the deep learning model.
- **keras**: The high-level API used to build the Sequential Neural Network.

## Data Overview
The LendingClub dataset includes various financial features of borrowers. The target variable in this case is whether the borrower defaulted on their loan or not (binary classification).

## Data Cleaning and Feature Engineering
One of the main focuses of the project was the data transformation phase. Key steps include:
- **Handling missing values**: Imputation or removal of records with missing data.
- **Encoding categorical variables**: Conversion of non-numeric fields into usable formats for machine learning.
- **Feature scaling**: Standardizing numerical data to ensure better performance of the model.
- **Feature creation**: Engineering new features based on the raw data.

## Modeling
The predictive model is a **Sequential Neural Network** built with TensorFlow and Keras. The architecture consists of:
- An input layer corresponding to the number of features.
- Hidden layers with activation functions to learn non-linear relationships.
- An output layer for binary classification (whether or not the borrower defaults).

The data was split into training and testing sets, and the model was evaluated using common metrics like accuracy, precision, recall, and F1-score.

## Results
The Sequential Neural Network was able to predict whether a borrower would default on their loan with reasonable accuracy after tuning and optimization. However, as with any predictive model, there is room for further improvement in terms of feature selection and model tuning.

## Conclusion
This project demonstrated the importance of thorough data cleaning and feature engineering when working with real-world financial data. The model, while not perfect, provides valuable insights into borrower behavior and can be improved further with additional feature refinement and tuning.
