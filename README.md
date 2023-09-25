# Credit Risk Classification
## Instructions
The instructions for this Challenge are divided into the following subsections:

* Split the Data into Training and Testing Sets

* Create a Logistic Regression Model with the Original Data

* Write a Credit Risk Analysis Report

### Split the Data into Training and Testing Sets
Open the starter code notebook and use it to complete the following steps:
1. Read the `lending_data.csv` data from the Resources folder into a Pandas DataFrame.
2. Create the labels set (`y`) from the “loan_status” column, and then create the features (`X`) DataFrame from the remaining columns.
3. Split the data into training and testing datasets by using `train_test_split`.

### Create a Logistic Regression Model with the Original Data
Use your knowledge of logistic regression to complete the following steps:
1. Fit a logistic regression model by using the training data (X_train and y_train).
2. Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.
3. Evaluate the model’s performance by doing the following:
a. Generate a confusion matrix.
b. Print the classification report.
4. Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

### Credit Risk Analysis Report
1. Overview of analysis: The goal of this analysis is to create a model that predicts the risk on whether to lend loans to reliable/unreliable borrowers.
2. Results: ![image](https://github.com/liceloo/credit-risk-classification/assets/90805881/d2b8ddee-7493-4df2-a0ae-a47f472181f8)
* Balanced Accuracy Score: 0.995
* Precision Score: 1.00
* Recall Score: 1.00
* F1-Score: 1.00
3. Summary: The logistic regression model has a perfect F1-score, meaning the logistic model has perfect preision and recall. With this specific data, the model will be perfect for evaluating credit risk; however, I would be cautious when running this model on unseen data. A high F1 score could be a result of overfitting. I would do a confusion matrix to see if this is what causing my F1 score to be high, or if the model is perfect.
