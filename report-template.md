# Module 12 Report Template

## Overview of the Analysis

Predicting lending risk is critical for any lending company to maintain financial stability, ensuring regulatory compliance, and providing fair, equitible, and efficient lending services to customer. Risk Management helps reduce the likelihood of defaults on loans and potenital financial losses. It is also important for maintaining profitability by offering more favorable lending terms to low risk customers and higher interest rates to higher risk customers fo compensate for the risk. 

This analysis used various techniques to train and evaluate a model based on loan risk. I used a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers. In order to create the logical regression model, I had to split the data into training and testing sets. After fitting the training data to the model I saved the predictions on the testing data. Finally, I evaluated the model with a confusion matrix and classification report to determine the accuracy of the model.

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
Classification scores for high-risk loans:

Accuracy Score - 99%
Even though the accuracy is near perfect, it is almost too good to trust. This is evident when the f1 score for high-risk loans is down to 89%.
Precision Score - 85%
Out of all the borrowers that the model predicted would be high-risk, 85% actually were.
Recall Score - 93%
Out of all the borrowers that ended up being high-risk, the model made correct predictions 93% of the time.

## Summary

The model predicts fairly accurately and with moderate percision. With an accuracy 