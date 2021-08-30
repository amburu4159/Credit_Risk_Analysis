# Credit_Risk_Analysis

## Overview of the analysis
The purpose of this analysis is to review credit risk and to predict a borrower’s risk status. The analysis uses various machine learning models like the Resampling Models, the SMOTEENN Algorithm and Ensemble Classifiers to Predict Credit Risk.


## Results

o Naive Random Oversampling - The balanced accuracy tests it 66% and the precision for the high-risk has a low positivity at 1% and the recall is 67% avg/total	
![Naive](https://github.com/amburu4159/Credit_Risk_Analysis/blob/main/images/Naive%20Random%20Oversampling.PNG)


o SMOTE oversampling - The accuracy score is 63% and the precision for the high-risk loans has a low positivity at 1% and recall is 64% avg/total
![SMOTE](https://github.com/amburu4159/Credit_Risk_Analysis/blob/main/images/SMOTE.PNG)


o Undersampling - The balanced accuracy score is 63.03% and the precision is at 99% while the recall is 45% avg/total
![Undersampling](https://github.com/amburu4159/Credit_Risk_Analysis/blob/main/images/Undersampling.PNG)


o Combination (Over and Under) Sampling - The balanced accuracy score is 53% and the precision is at 99% while the recall is 57% avg/total
![Combination](https://github.com/amburu4159/Credit_Risk_Analysis/blob/main/images/Combination.PNG)


o Balanced Random Forest Classifier - The balanced accuracy score is 83% and the precision is at 99% while the recall is 89% avg/total
![Balanced Random Forest Classifier](https://github.com/amburu4159/Credit_Risk_Analysis/blob/main/images/random%20forest.PNG)


o Easy Ensemble AdaBoost Classifier - The balanced accuracy score is 92% and the precision is at 99% while the recall is 94% avg/total
![Easy Ensemble AdaBoost Classifier](https://github.com/amburu4159/Credit_Risk_Analysis/blob/main/images/Adaboost.PNG)


## Summary 
All the models used in the analysis show weak precision in determining credit worthiness. The Ensemble models provide better analysis and record improved sensitivity of the high-risk credits.
The EasyEnsembleClassifier model shows a recall of 92% so it detects the highest percentage of high-risk credit, however with a 
low precision, plenty of low-risk credits are still wrongly returned as high risk which would lead to bad decisions and the bank potentially missing out on those opportunities. penalize the bank's credit 
strategy and infer on its revenue by missing those business opportunities. I would advise the bank to proceed with caution, and if they must use one of these models, to use the EasyEnsembleClassifier, but understand the downsides of the model.
