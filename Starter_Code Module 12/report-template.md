# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

The purpose of this analysis was to take historical data of healthy and high-risk loans that have already been issued and create a Logitic Regression model to predict if a borrower has the credit worthiness to be considered high-risk or low-risk. This was done by splitting the data into training and testing sets and using the model-fit-predict-evaluate pattern. The data was also resanpled via oversampling and was run through the same process. 

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
Machine Learning Model 1 had a balanced accuracy of 95%. THe predictions for healthy loans had 100% precision and 99% recall scores. The predictions for high-risk loans had 85% precission and 91% recall scores. 


* Machine Learning Model 2:
Machine Learning Model 2 had a balanced accuracy of 99%. THe predictions for healthy loans had 100% precision and 99% recall scores. The predictions for high-risk loans had 84% precission and 99% recall scores. 


## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

I believe the Machine Learning Model 2 with the resampled data performs the best due to the fact that although both models have the same precision and recall when predicting healthy loans, when predicting high-risk loans Model 2 has a significantly higher score with recall. This is definately a key factor into its balanced accuracy being 5% higher than Model 1. Also, since the problem at hand is trying to determine if borrowers are creditworthy of a loan, the ability to predict high-risk loans more effeciently is more important.  
