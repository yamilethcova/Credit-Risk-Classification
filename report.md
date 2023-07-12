# Module 12 Report 

## Overview of the Analysis

The purpose of evaluating this analysis is to develop and predict if the data's loans are high-risk or healthy. Using machine learning models where I have to process, train and evaluate the data to get proper accuracy, precision, and recall   

The variables inside of the data have been labelled as 0 = Low Risk 
                                                       1 = High Risk

The machine learning models used were:

Machine Learning Model 1: Logistic Regression
Machine Learning Model 2: Ransom over Sampler - To balance the data 

## Results

Machine Learning Model 1 (Logistic Regression):

Precision for label 0 (healthy loan): 1.00
Recall for label 0: 1.00
F1-score for label 0: 1.00
Precision for label 1 (high-risk loan): 0.85
Recall for label 1: 0.91
F1-score for label 1: 0.88

For this ML Module 1, we can conclude: 
Accuracy: 0.99

Machine Learning Model 2 (Ransom over Sampler)

Precision for label 0 (healthy loan): 1.00
Recall for label 0: 0.99
F1-score for label 0: 1.00
Precision for label 1 (high-risk loan): 0.84
Recall for label 1: 1.00
F1-score for label 1: 0.91

For this ML Module 2: 
Accuracy: 0.99

## Summary

Both ML models demonstrated strong performance in predicting high-risk, both models show a very close balance score has model 1 = 95% and Model 2 =99%, however, the data from model 1 is imbalance due to the number of the healthy loan being 17036 and unhealthy one 2500 the difference is very big, saying that is why I decide to use the Ransom over sampler to balance the data and get a realistic prediction on the model. regarding which label is better to predict I will say both, 0 and 1 so you can get properly evaluate the data and know if it balances or not and minimize the possible misclassification of a healthy or high-risk loan 




