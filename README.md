# credit-risk-classification

Instructions
The instructions for this Challenge are divided into the following subsections:

    Split the Data into Training and Testing Sets

    Create a Logistic Regression Model with the Original Data

    Write a Credit Risk Analysis Report

Split the Data into Training and Testing Sets
Open the starter code notebook and use it to complete the following steps:

    1. Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.

    2. Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.

    3. Split the data into training and testing datasets by using train_test_split.

Create a Logistic Regression Model with the Original Data
Use your knowledge of logistic regression to complete the following steps:

    1. Fit a logistic regression model by using the training data (X_train and y_train).

    2. Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.

    3. Evaluate the model’s performance by doing the following:

        Generate a confusion matrix.

        Print the classification report.

    4. Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

Write a Credit Risk Analysis Report
Write a brief report that includes a summary and analysis of the performance of the machine learning models that you used in this homework. You should write this report as the README.md file included in your GitHub repository.

Structure your report by using the report template that Starter_Code.zip includes, ensuring that it contains the following:

    1. An overview of the analysis: Explain the purpose of this analysis.

    2.The results: Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.

    3. A summary: Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.


    Credit Risk Analysis Report

    The purpose of this analysis is to create and evaluate the accuracy of a data model that predicts the credity worthiness of potential borrowers from peer-to-peer lending services.

Model Number 1

Balanced Accuracy Score: 95.20% --> this means that when taking into account the sensitivity (recall and/or true positive rate) and specificity (true negative rate) of the model, the balanced prediction accuracy was 95.2%.

Precision Score: 92% --> This means 92% of predicted positives were correct.

Recall Score: 95% --> this means that the model was 95% precise in measuring true positive values our of all positive predictions made.

Model Number 2

Balanced Accuracy Score: 99.45% --> this means that when taking into account the sensitivity (recall and/or true positive rate) and specificity (true negative rate) of the model, the balanced prediction accuracy was 99.4%.

Precision Score: 99% --> This means 99% of predicted positives were correct.

Recall Score: 99% --> this means that the model was 99% precise in measuring true positive values our of all positive predictions made.

While the second model outperforms the first by 4%, I would recommend using either one of these models to predict the creditworthiness of borrowers, because the first model has over 95% accuracy in predicting the outcome of the repayment of the initial loan and the second model has a 99% accuracy. That accuracy range could be easily molded into a business risk profile to ensure sufficient capital flow for the lenders to remain in business/make a profit.
