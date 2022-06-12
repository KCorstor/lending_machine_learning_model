# Module 12 Report Template

## Overview of the Analysis



# Needs to be fixed an re-done
The purpose of this analysis is to train a model to predict the creditworthiness of borrowers. We analyzed loan size, interest rate, borrower income, debt to income, number of accounts, derogatory marks and total debt and current loan status. Our goal was to use this model to predict the likely future status of other loans. 

With our model we wanted to be able to analyze a future set of loans, and determine how many would likely go bad. To make our model, we imported an existing dataset, we split that into two parts. We did this by using train_test_split which separates the data into a 80% 20% split, taking one portion to train our model and the other smaller portion to test our model once it was completed. 

Once the data was separated we 'fit' our model. We then used that model to make predictions based on the training data, as well as the 'test data' so we could compare the difference between the two. After that we used accuracy scores, confusion matrices, and classification reports to review the data and see if we could the difference between the test data, and the data we were using to control. After that we balanced the results to reflect an even number of 'positive' data points as well as 'negative' data points so that we could refine our model and give it more accurate data points with better weight. We did this with RandomOverSampler, which manipulated our test data to have a more appropriate weight to feed the model. When that was completed we fit a new model, ran the predictions again and then ran our classification/confusion/accuracy analysis again.  


## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

 * Machine Learning Model 1:
 * Description of Model 1 Accuracy, Precision, and Recall scores.
 
 * Precision is the number of true positive results divided by the total of true positive+False positive.
 *
 * Machine Learning Model 2:
 * Description of Model 2 Accuracy, Precision, and Recall scores.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.