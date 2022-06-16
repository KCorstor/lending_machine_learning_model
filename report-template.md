
# Module 12 Report Template

  

## Overview of the Analysis



*	The purpose of this analysis is to train a model to predict the likely future status of loans. We did this by making and fitting a model based on the creditworthiness of current borrowers. We analyzed loan size, interest rate, borrower income, debt to income, number of accounts, derogatory marks, total debt and current loan status. 
  

*	To make our model, we imported an existing dataset and we split that into two parts. We did this by using train_test_split which separates the data into a 80% 20% split, taking one portion to train our model and the other smaller portion to test our model once it was completed.

  

*	Once the data was separated we 'fit' our model. We then used that model to make predictions using the model fit from the training data, to predict how the 'test data' would perform. After that we used accuracy scores, confusion matrices, and classification reports to review the data and see if we could the difference between the test data and our predictions. After that we rebalanced the input data to reflect an even number of 'positive' data points as well as 'negative' data points so that we could refine our model and get more accurate by feeding it with better weighted data. We did this with RandomOverSampler, which manipulated our test data to have a more appropriate weight to feed the model. When that was completed we fit a new model, ran the predictions again and then ran our classification/confusion/accuracy analysis again.

  
 
## Results

  


* For machine Learning Model one, our 'negative' results were predicted 100% correctly for precision, recall, and f1. Our positive results were .88 for precision, .89 for recall, and .88 for f1. 

* When we refit our model we lost 1bp for precision, but were able to raise recall to 100, and f1 to .93. Overall the model fit better and gave us better results


## Summary

 *	Overall, our second model performed better. We were able to get significantly more accurate by refitting the data.
