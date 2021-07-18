# Credit_Risk_Analysis
# Overview of the analysis
In this project, we use Python to build and evaluate several machine learning models to predict credit risk.
We adopted the following procedure:
- Oversample the data using the RandomOverSampler and SMOTE algorithms.
- Undersample the data using the ClusterCentroids algorithm.
- Use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm.
- Compare two machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier.
We will evaluate the performance of these models and make a recommendation on whether they should be used to predict credit risk.

# Results
## RandomOVerSampler
![RandomOVerSampler](https://github.com/arelysrsd87/Credit_Risk_Analysis/blob/main/Images/NaiveRandomOversampling.jpg)  
- The balanced accuracy score is 66.0 %.
- The high risk precision is about only 1% with sensitivity of 66% which makes a F1 of 2%.
- Due to the high number of the low risk population, it's precision is almost 100% with a sensitivity of 67%.
## SMOTE
![SMOTE](https://github.com/arelysrsd87/Credit_Risk_Analysis/blob/main/Images/SMOTE.jpg)  
- The balanced accuracy score is 65.7%
- The high risk precision is about only 1% with sensitivity of 62% which makes a F1 of 2%.
- Due to the high number of the low risk population, it's precision is 100% with a sensitivity of 64%.
## ClusterCentroids
![ClusterCentroids](https://github.com/arelysrsd87/Credit_Risk_Analysis/blob/main/Images/ClustersCentroids.jpg)  
- The balanced accuracy score is 51.0%.
- The high risk precision is about only 1% with sensitivity of 59% which makes a F1 of 1%.
- Due to the high number of the low risk population, it's precision is 100% with a sensitivity of 43%.
## SMOTEENN
![SMOTEENN](https://github.com/arelysrsd87/Credit_Risk_Analysis/blob/main/Images/SMOTEENN.jpg)  
- The balanced accuracy score is 65.7%.
- The high risk precision is about only 1% with sensitivity of 74% which makes a F1 of 2%.
- Due to the high number of the low risk population, it's precision is 100% with a sensitivity of 58%.
## BalancedRandomForestClassifier
![BalancedRandomForestClassifier](https://github.com/arelysrsd87/Credit_Risk_Analysis/blob/main/Images/BalancedRandomForestClassifier.jpg)  
- The balanced accuracy score is 53.6%.
- The high risk precision is about only 1% with sensitivity of 90% which makes a F1 of 1%.
- Due to the high number of the low risk population, it's precision is 100% with a sensitivity of 17%.
## EasyEnsembleClassifier
![EasyEnsembleClassifier](https://github.com/arelysrsd87/Credit_Risk_Analysis/blob/main/Images/EasyEnsembleClassifier.jpg)  
- The balanced accuracy score is 93%.
- The high risk precision is about only 9% with sensitivity of 92% which makes a F1 of 16%.
- Due to the high number of the low risk population, it's precision is 100% with a sensitivity of 94%.
# Summary
- Summary of the results
- Recommendation on which model to use