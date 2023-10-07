Insurance Customer Retention Analysis

This code performs customer retention analysis using a dataset from Kaggle, which is available at https://www.kaggle.com/code/merishnasuwal/merge-churn-analysis-data-for-auto-insurance/input. Customer retention analysis is essential for insurance companies to understand and predict customer behavior.

**Overview**

The code performs the following tasks:

Data Preprocessing: It starts by importing necessary libraries and loading the dataset. Missing data is handled by filling or imputing values. Outliers are also identified and removed from the dataset.
Exploratory Data Analysis (EDA): The code visualizes and analyzes the dataset using various plots and statistics. It explores factors such as customer demographics, home ownership, credit status, and more to understand their influence on churn.
Data Preparation: Features are transformed and prepared for modeling. This includes encoding categorical variables, handling class imbalance using techniques like oversampling (SMOTE), and splitting the data into training and testing sets.
Modeling: Three different models are used for churn prediction: Logistic Regression, Decision Tree Classifier, and Random Forest Classifier. The code trains these models, evaluates their performance, and visualizes the results.
Deep Learning Model: A deep neural network model is implemented using TensorFlow/Keras. The model is trained, and its performance is evaluated.
Gradient Analysis: Gradient analysis is performed to understand the impact of individual features on model predictions. This helps identify influential features.
Feature Sensitivity Analysis: The code analyzes how changes in specific feature values affect predictions, allowing for sensitivity analysis.

**How to Use**

### Prerequisites

- Python 3.x
- Jupyter Notebook (for running the provided Jupyter notebook)
- Libraries and dependencies mentioned in the code

### Installation

1. Clone this repository to your local machine using `git clone`.
2. Install the required dependencies 

### Dataset

Download the dataset from the Kaggle link provided and replace the file path in the code with your dataset file path.

Run the Code: Execute the code in a Jupyter Notebook or your preferred Python environment.
Customization: Customize the code as needed for your specific analysis, such as modifying model hyperparameters, adding more visualizations, or changing the feature sensitivity analysis.
Interpret Results: Analyze the model performance metrics, gradient analysis, and sensitivity analysis to draw insights about customer churn in your insurance dataset.
Feel free to adapt and expand upon this code to suit your specific analysis requirements.
