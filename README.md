# credit-risk-classification

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

The purpose of this analysis is to create classification models for predicting and categorizing credit risk. After creating these models, they need to be compared and contrasted for their ability to classify credit risk. The financial information that was on the data consists of a borrower's lending information such as "loan size", "interest rate", "borrower income", etc. Based on this information, we need to determine if a borrower is "Not at risk" or "At risk". 

Process of machine learning:
1. Separate data into labels and features.
2. Split data into training and testing datasets.
3. Fit logisitic regression model.
4. Evaluate accuracy of model.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.

Accuracy: 99%
Precision: 100%
Recall: 99%

This model is very good at describing the scores of borrowers.
* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

Accuracy: 99%
Precision: 100%
Recall: 99%
This model is very similar to the Model 1 in that it is very accurate as well.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.

According to the data, both models perform very similarly. The only major difference between the two is that the recall section in Model 2, 1's(high-risk-loan) is at 99%. So based on this, I would say Model 2 is the model I would use for categorizing credit risk. 
