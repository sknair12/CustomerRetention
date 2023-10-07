# Insurance Customer Retention Analysis

Insurance industry is highly dependent on data to run the business since many of its day- to-day functions like product pricing, underwriting, claim etc. are all data driven. Just like any other industry, customer acquisition and retention are two key aspects of insurance industry too. Given that, customer acquisition cost is high in terms of agent commissions, direct-to-customer capital investments, it is important to focus on customer retention to offset the acquisition cost and be profitable in longer term. As part of this project, a predictive engine will be built and trained using available insurance policy data which can predict the customer churn probability based on other customers with similar profile.

This code performs customer retention analysis using a dataset from Kaggle, which is available at https://www.kaggle.com/code/merishnasuwal/merge-churn-analysis-data-for-auto-insurance/input.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Dataset](#dataset)
- [Run the Code](#run-the-code)
- [License](#license)

### Introduction

The code performs the following tasks:

Data Preprocessing: It starts by importing necessary libraries and loading the dataset. Missing data is handled by filling or imputing values. Outliers are also identified and removed from the dataset.
Exploratory Data Analysis (EDA): The code visualizes and analyzes the dataset using various plots and statistics. It explores factors such as customer demographics, home ownership, credit status, and more to understand their influence on churn.
Data Preparation: Features are transformed and prepared for modeling. This includes encoding categorical variables, handling class imbalance using techniques like oversampling (SMOTE), and splitting the data into training and testing sets.
Modeling: Three different models are used for churn prediction: Logistic Regression, Decision Tree Classifier, and Random Forest Classifier. The code trains these models, evaluates their performance, and visualizes the results.
Deep Learning Model: A deep neural network model is implemented using TensorFlow/Keras. The model is trained, and its performance is evaluated.
Gradient Analysis: Gradient analysis is performed to understand the impact of individual features on model predictions. This helps identify influential features.
Feature Sensitivity Analysis: The code analyzes how changes in specific feature values affect predictions, allowing for sensitivity analysis.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook (for running the provided Jupyter notebook)
- Libraries and dependencies mentioned in the code

### Installation

1. Clone this repository to your local machine using `git clone`.
2. Install the required dependencies mentioned in requirements.txt

### Dataset

Download the dataset from the Kaggle link provided and replace the file path in the code with your dataset file path.
Kaggle Link: https://www.kaggle.com/code/merishnasuwal/merge-churn-analysis-data-for-auto-insurance/input

## Run the Code

Execute the code in a Jupyter Notebook or your preferred Python environment.
Customization: Customize the code as needed for your specific analysis, such as modifying model hyperparameters, adding more visualizations, or changing the feature sensitivity analysis.
Interpret Results: Analyze the model performance metrics, gradient analysis, and sensitivity analysis to draw insights about customer churn in your insurance dataset.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
Feel free to adapt and expand upon this code to suit your specific analysis requirements.
