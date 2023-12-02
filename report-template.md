# Module 12 Report Template

## Overview of the Analysis

Overview of the Analysis
Lending companies lend money/properties to borrowers with the expectation that the borrower will either return the asset or repay the lender. Credit Risk is associated with a borrower not returning an asset or paying a loan back causing a lender to lose money. This is measured by lenders in many ways, however in this analysis we will use Machine Learning to analyze a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

Using a machine learning model, I will try to determine which loans are healthy (low-risk) or non-healthy (high-risk) based on the loan status provided by the lending company. The Logistic Regression Algorithm is the best tool to use for our machine learning model since it is widely used to predict the probability of a target variable in classification problems.

Using the dataset provided by the lending company, I created a Logistic Regression Model that generated an accuracy score of 94%. Although the model generated a high-accuracy, the models recall value (89%) for non-healthy loans is lower than the recall value (100%) for healthy loans. This indicates that the model will predict loan status's as healthy better than being able to predict loan status's as non-healthy. This can be attributed to the dataset being imbalanced, meaning that most of the data belongs to one class label (in this case healthy loans (0) greatly outweighed non-healthy loans (1)). The value_count function of the y labels (step 3 of "Split the Data into Training and Testing Sets") showed that the data is highly imbalanced by indicating healthy loans (majority class) and non-healthy loans (minority class)having responses of 75036 and 2500 respectively.
## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
