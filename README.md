# customer-churn-prediction
Machine learning project for predicting customer churn using Python

# Customer Churn Prediction

## Project Overview

This project focuses on predicting customer churn using machine learning techniques. The objective is to identify customers who are likely to leave a telecom service provider based on their demographic information, account details, and service usage.

The project uses the Telco Customer Churn dataset and includes data preprocessing, exploratory analysis, handling of class imbalance, model training, cross-validation, and performance evaluation.

## Dataset

The project uses the Telco Customer Churn dataset.

* Records: 7,043
* Features: 21
* Target variable: `Churn`
* Target classes:

  * `0` – Customer did not churn
  * `1` – Customer churned

## Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* XGBoost
* Imbalanced-learn
* Pickle

## Project Workflow

1. Data loading
2. Data cleaning and preprocessing
3. Exploratory data analysis
4. Feature encoding
5. Train-test split
6. Handling class imbalance using SMOTE
7. Model training
8. 5-fold cross-validation
9. Model evaluation
10. Model saving using Pickle

## Data Preprocessing

The following preprocessing steps were performed:

* Removed the `CustomerID` column as it does not contribute to prediction.
* Handled missing values in the `TotalCharges` column.
* Encoded categorical variables into numerical values.
* Separated features and the target variable.
* Split the dataset into training and testing sets.
* Applied SMOTE to the training data to address class imbalance.

## Machine Learning Models

The project experimented with multiple classification algorithms:

* Decision Tree
* Random Forest
* XGBoost

The models were evaluated using classification metrics and cross-validation.

## Model Evaluation

The models were evaluated using:

* Accuracy
* Confusion Matrix
* Classification Report
* ROC-AUC Score
* 5-Fold Cross-Validation

### Random Forest Results

The Random Forest model achieved:

* Cross-validation accuracy: approximately **0.84**
* ROC-AUC: approximately **0.823**

These metrics were used to assess the model's ability to distinguish between customers who churn and those who remain.


## How to Run the Project

1. Open the `Customer_Churn_Prediction.ipynb` notebook.
2. Upload or provide access to the Telco Customer Churn dataset.
3. Run the notebook cells sequentially.
4. Install any required Python libraries if necessary.
5. Review the preprocessing steps, model training, and evaluation results.

The notebook can be opened and executed using Google Colab.

## Key Learning Outcomes

Through this project, I gained practical experience in:

* Data cleaning and preprocessing
* Exploratory data analysis
* Categorical feature encoding
* Handling imbalanced datasets using SMOTE
* Machine learning classification
* Model comparison and evaluation
* Cross-validation
* ROC-AUC analysis
* Saving trained machine learning models


