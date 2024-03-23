# **Machin learning with Data Zoom camp**
 This Project is Churn Prediction which is taught in Data Talk channel.
## Churn Prediction with Logistic Regression

This project investigates customer churn using machine learning techniques. The goal is to build a model that predicts whether a customer is likely to churn (cancel their service) in the future.

### Project Background

Customer churn is a significant challenge for businesses across various industries. Identifying customers at risk of churning allows companies to take proactive measures like targeted marketing campaigns or loyalty programs to retain them. This project explores the use of logistic regression for churn prediction on a telecommunications company dataset.

### Data Collection Method

The publicly available Telco-Customer-Churn dataset from Kaggle was used for this project. This dataset contains information about telecommunications customers, including their demographics, service plans, and churn status. 

### Data Preprocessing

The raw data likely underwent several cleaning and preprocessing steps before model training. These steps may have included:

* Handling missing values: imputation with a constant value have been used to address missing data points.
* Feature Selection : Churn Rate among different types of customers
* Feature scaling: use Risk Ratio and mean method to scaling features
* Data transformation: Categorical features  have been encoded using techniques of one-hot encoding.


### Model Training

A logistic regression model was chosen for this project. Logistic regression is a well-suited algorithm for binary classification problems like churn prediction. The model was trained on the preprocessed Telco-Customer-Churn dataset.

### Results

The document outlining this project contain the evaluation metrics for the trained logistic regression model. These metrics might include:

* Accuracy: Proportion of correct predictions made by the model = 0.80
* Precision: Ratio of true positives to the total number of positive predictions = 0.32
* Recall: Ratio of true positives to the total number of actual positive cases = 0.54
* F1-score: Harmonic mean of precision and recall = 0.40 ?
* AUC-ROC curve: Visualization of the model's performance in classifying churned and non-churned customers = 0.857


