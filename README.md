# Handling-Imbalance_Data
What is imbalanced data?
Imbalanced data refers to those types of datasets where the target class has an uneven distribution of observations, 
i.e one class label has a very high number of observations and the other has a very low number of observations. 


the main problem with imbalanced dataset prediction is how accurately are we actually predicting both majority and minority class?
 Let’s assume we are going to predict disease from an existing dataset where for every 100 records only 5 patients are diagnosed with the disease. So, the majority class is 95% with no disease and the minority class is only 5% with the disease.
 Now, assume our model predicts that all 100 out of 100 patients have no disease.
 For an imbalanced class dataset F1 score is a more appropriate metric
Methods Solution:
A) SMOTE 
B)Resample the training set 1) Oversampling  , 2) Undersampling  , 3) Use K-fold Cross-Validation
C) Use the right evaluation metrics
D) BalancedBaggingClassifier.
