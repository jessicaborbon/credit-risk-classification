# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).

Building a model that can accurately identify the creditworthiness of borrowers is crucial for P2P lending services. Such a model allows lenders to evaluate the risk associated with lending to a particular borrower, set appropriate interest rates, and make well-informed decisions about loan approvals. By leveraging historical borrower data and various financial indicators, lenders can assess the probability of default and make more reliable lending decisions. In this project, I used a dataset containing the historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers. The dataset contained features such as loan size, interest rate, borrower income, debt to income ratio, number of account the borrower posseses, a count of derogatory remarks, as well as their total debt while the loan status formed the label.
## Results
Description of Model Accuracy, Precision, and Recall scores.
From the confusion matrix (Fig. 2) the logistic model predicted 18,663 as healthy loans correctly and 102 as healthy loans incorrectly from a total loan status of 18,765 which were healthy (i.e., low-risk).
The model predicted 563 as high-risk loans correctly and 56 high-risk loans incorrectly from a total loan status of 619 which were high-risk.
The classification report which takes into account the model's accuracy revealed that the healthy loans had a precision score of 100%, and a recall of 99%. For the non-healthy loans, the precision and recall were 85% and 99%, respectively. The overall performance of the model was calculated to be 99%.


Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.
Description of Model Accuracy, Precision, and Recall scores after Resampling:
From the confusion matrix (Fig. 3) the logistic model predicted 18,663 as healthy correctly and 102 as healthy incorrectly from a total loan status of 18,765 which were healthy (i.e., low-risk).
The model predicted 563 as high-risk loans correctly and 56 high-risk loans incorrectly from a total loan status of 619 which were high-risk.
After resampling using the oversampling method, the classification report showed that the healthy loans had a precision score of 100%, and a recall of 99%. For the non-healthy loans, the precision and recall were 84% and 99%, respectively. The overall performance of the model was calculated to be 99%.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
Overall, the accuracy seems to be good enough to start exploring this kind of algorithms in a bank, however, I would prefer to start running a pilot with new data to assess model's reliability.
It's important to note that the effectiveness of the creditworthiness model heavily depends on the quality and relevance of the data collected. Therefore, it's crucial to have a comprehensive and reliable dataset to achieve accurate predictions.
As part of next steps, it will be imperative to identify the most relevant features that are likely to impact the creditworthiness of borrowers and then run a pilot with new data sets of data to assess model's reliability.

If you do not recommend any of the models, please justify your reasoning.
