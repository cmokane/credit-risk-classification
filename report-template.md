# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* The purpose of the analysis is to investigate factors that deal with loan risk.
* The financial information the data was on is past lending transactions from a platform, and we used it to predict how good of credit a borrower had.
* We used the data we had to break it up into 2 groups so we can split the logistic regression model.

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.
    * Healthy loans had a precision score of 100% and a recall score of 100%
    * Unhealthy loans had a precision score of 87% and a recall score of 89%
    * weighted average had a score score of 99% 

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
- It seems this model works very well for healthy loans however there seem to be no false positives and no comparison to be made so I would not recommend this model unless its for healthy.
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
- I think it is important for predicting both performances in order to compare the findings from the data. 
If you do not recommend any of the models, please justify your reasoning.
- I would recommend depending on what we are trying to find. I would use it for healthy loans but need more model examples for other types of loans. 