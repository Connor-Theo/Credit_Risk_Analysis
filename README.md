# Credit_Risk_Analysis

## Overview:  
With the use of a peer-to-peer credit risk dataset from Lending Club we employed several modeling techniques on an imbalanced class dataset to model whether a loan is low-risk or high risk. The techniques on display for this project are Resampling, Oversampling, SMOTE, Undersampling, Balanced Random Forest Classifier, and Easy Ensamble Adaboost Classifer.  
An imbalanced data set is defined as ‘those types of datasets where the target class has an uneven distribution of observations, i.e one class label has a very high number of observations and the other has a very low number of observations.’  Since good loans tend to outnumber bad loans, this dataset makes for an excellent example for imbalanced machine learning.

## Results:
The results of each technique can be measured by a metric known as ‘balanced accuracy score’.  A metric for how accurate each model is at predicting an imbalanced dataset. Let’s see how each test performed!
•	Naive Random Oversampling: 
o	BAS: 66.14%
•	SMOTE Oversampling
o	BAS: 65.81%
•	Under Sampling
o	BAS: 58.90%
•	Combination (over & under) Sampling
o	BAS: 64.49%
•	Balanced Random Forest Classifier
o	BAS: 78.77%
•	Easy Ensemble AdaBoost Classifier
o	BAS: 92.54%
o	 ![image](https://user-images.githubusercontent.com/101610050/180672198-40bf10d4-6817-4236-81b1-3836343d759b.png)



## Summary:
The results show a clear leader among the classifier techniques, Easy Ensemble AdaBoost Classifier with a balanced accuracy score of 92% was the most accurate predictor of the bunch.  Outside of the Balanced Random Forest Classifier algorithm the other tests could not give the user any reliability on its predictions. Loan lenders are not keen to hand out money on a coin flip chance they have a low-risk loan or not. In this instance I can confidently state that Easy Ensemble AdaBoost Classifier is our most reliable algorithm. 
