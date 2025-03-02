# credit-risk-classification
Instructions
The instructions for this Challenge are divided into the following subsections:

Split the Data into Training and Testing Sets

Create a Logistic Regression Model with the Original Data

Write a Credit Risk Analysis Report

Split the Data into Training and Testing Sets
Open the starter code notebook and use it to complete the following steps:

Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.

Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.
Create a Logistic Regression Model with the Original Data
Use your knowledge of logistic regression to complete the following steps:

Fit a logistic regression model by using the training data (X_train and y_train).

Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.

Evaluate the model’s performance by doing the following:

Generate a confusion matrix.

Print the classification report.

Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?


Credit Risk Analysis Report

Overview of the Analysis 
This analysis is to evaluate a machine learning model for credit risk classification to build a model that can identify the creditworthiness of borrowers. The dataset contains financial information about loan applicants, and our goal is to forecast whether a loan is high or low risk based on given data. A machine learning analysis will identify the possible risk of loans which is good or risky loans.

Process: 
1. Data Preparation: 
•	The dataset was loaded and preprocessed.
•	The target variable (loan status) was separated from the features. 
2. Model Selection: 
•	Logistic Regression model for classification. 
3. Model Evaluation: 
•	We examined performance using accuracy, precision, and recall metrics. 

Results 
Machine Learning Model: Logistic Regression 
•	Accuracy: >99% 
•	Precision (for class 1): 84% 
•	Recall (for class 1): 94% 
•	F-score (for class 1): 89%
•	Precision 100%, Recall 99%, and F-Score are all 100% for class 0.
Summary
 The accuracy level was more than 99% so we can say that the logistic regression model performed very well. Given the nature of credit risk classification, recall is particularly important as it ensures we correctly identify as many high-risk loans as possible. With a recall score of 95%, the model effectively captures most of the high-risk cases, making it a viable choice for credit risk assessment. 

Recommendation: 
•	As Given its high accuracy and strong recall performance, we recommend this model to use for credit risk classification. 
