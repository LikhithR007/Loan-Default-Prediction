# Loan Default Prediction Project

## Introduction

This project aims to build a machine learning model to predict loan defaults based on historical data from a German bank. The dataset contains information on customer attributes, credit history, savings balance, and other relevant features.

## Dataset

- **Domain**: Banking
- **Context**: The dataset contains historical data of customers who have taken loans from a German bank, and the bank aims to predict whether a customer will default on their loan based on their historical data.
- **Features**: The dataset consists of 17 columns, including attributes such as checking balance, months loan duration, credit history, purpose of the loan, amount, savings balance, employment duration, percentage of income, years at residence, age, and more.
- **Target Variable**: The target variable is "default," indicating whether a customer defaulted on their loan.

## Project Structure

The project is organized into the following sections:

1. **Data Preprocessing and Exploratory Data Analysis (EDA)**:
   - Load the dataset and perform data exploration.
   - Encode categorical variables using one-hot encoding and label encoding.
   - Generate visualizations to understand the data distribution and relationships.

2. **Model Training and Evaluation**:
   - Scale the features using StandardScaler.
   - Split the data into training and testing sets.
   - Train an XGBoost classifier and evaluate its performance using accuracy, precision, recall, and F1 score.

3. **Research Questions**:
   - Analyze the influence of customer attributes and credit history on loan default rates.
   - Calculate default rates based on specified customer attributes and credit history with savings balance.

4. **Model Comparison**:
   - Train and evaluate multiple classification algorithms (Random Forest, Logistic Regression, Support Vector Machine, Decision Tree).
   - Compare the performance metrics of each model.

## How to Run

To run the project, follow these steps:

1. Install Jupyter Notebook if you haven't already:

2. Open a terminal or command prompt and navigate to the project directory.

3. Start Jupyter Notebook by running the following command:

4. In the Jupyter Notebook interface, open the file named "GermanBankLoan.ipynb".

5. Run each cell in the notebook sequentially to execute the code and reproduce the analysis.

## Conclusion

This project provides valuable insights into predicting loan defaults using machine learning techniques. By analyzing customer attributes and credit history, we can better understand the factors influencing loan default rates and build models to mitigate risks for the bank.
