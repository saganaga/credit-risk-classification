# credit-risk-classification
## Purpose
To use various techniques to train and evaluate a model based on loan risk. To use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.
## Overview
The to-do list is the following:
### Split the Data into Training and Testing Sets
- [x] Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.
- [x] Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns. 
- [x] Split the data into training and testing datasets by using train_test_split.
### Create a Logistic Regression Model
- [x] Fit a logistic regression model by using the training data (X_train and y_train).
- [x] Save the predictions on the testing data labels by using the testing feature data (X_test) and the fitted model.
Evaluate the model’s performance by doing the following:
- [x] Generate a confusion matrix.
- [x] Generate a classification report.
- [x] Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?
### Coding Conventions and Formatting
- [x] Place imports at the top of the file, just after any module comments and docstrings and before module globals and constants.
- [x] Name functions and variables with lowercase characters, with words separated by underscores.
- [x] Follow DRY (Don’t Repeat Yourself) principles, creating maintainable and reusable code.
- [x] Use concise logic and creative engineering where possible.
### Code Comments
- [x] Be well commented with concise, relevant notes that other developers can understand.
## Results
For results see the credit_risk_classification.ipynb file.