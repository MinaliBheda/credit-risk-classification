# credit-risk-classification

# Overview of the Analysis

    Factors considered in the analysis included data on:

        1.the size of the loan
        2.its interest rate
        3.the borrower's income
        4.the debt to income ratio
        5.the number of accounts the borrower held
        6.derogatory marks against the borrower
        7.the total debt

        The dataset (77,536 data points) was split into training and testing sets. The training set was used to build logistic regression model using the LogisticRegression module from scikit-learn. Logistic Regression Model was then applied to the testing dataset. The purpose of the model was to determine whether a loan to the borrower in the testing set would be low- or high-risk and results are summarized below.

# Results:

    Precision: 93% (an average--in predicting low-risk loans, the model was 100% precise, though the model was only 87% precise in predicting high-risk loans)
    Accuracy: 94%
    Recall: 95% (an average--the model had 100% recall in predicting low-risk loans, but 89% recall in predicting high-risk loans)


# Summary:

   As The model was able to predict 100 % of precision and recall when predicting for Low risk/ healthy loan but showed only 87 % and 89% in case of unhealthy /High risk loan I wouldnt recommended the model for use by the company.
