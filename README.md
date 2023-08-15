Overview of the Analysis:
    This analysis was to predeict the healthy and high-risk loan labels. The data provided are as follows: loan size, interest rate, borrower income, debt to income ratio and total debt. Those information help me to predict whether the loans issued would be high risk or healthy loans. There were 75036 healthy loans and 2500 high-risk loans. I used the machine learning process to split the data, train and test the model in order for me to make an accurate prediction. To fit the LogisticRegression I used the training model. To make predictions I used feature data and fitted model. For the last step I calculate the accuracy of the model, generate the confusion matrix and printed the classification report.

Model Results:
    Machine Learning Model A:
    Accuracy-  0.99
    Precision- Healthy: 1.00 High-Risk: 0.85
    Recall-    Healthy: 0.99 High-Risk: 0.91
    F-1-       Healthy: 1.00 High-Risk: 0.88

    Machine Learning Model B:
    Accuracy-   0.99
    Precision-  Healthy: 1.00 High-Risk: 0.84
    Recall-     Healthy: 0.99 High-Risk: 0.99
    F-1-        Healthy: 1.00 High-Risk: 0.91

Recommendation Summary:
    Both models shows the loan labels a high level of accuracy, but, I would recommend the model B. This recommendation was based on the results of Recall and F-1. I wanted to minimize the number of high-risk loans that are inappropriately classified as healthy high loans. Utilizing the second model with higher recall means that the model can effectively identify most of the actual high-risk loans.