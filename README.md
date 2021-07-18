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
- The balanced accuracy score is
- The high risk precision is about only with sensitivity which makes a F1 of .
- Due to the high number of the low risk population, it's precision is with a sensitivity of .
## SMOTE
![SMOTE](https://github.com/arelysrsd87/Credit_Risk_Analysis/blob/main/Images/SMOTE.jpg)  
- The balanced accuracy score is
- The high risk precision is about only with sensitivity which makes a F1 of .
- Due to the high number of the low risk population, it's precision is with a sensitivity of .
## ClusterCentroids
![ClusterCentroids](https://github.com/arelysrsd87/Credit_Risk_Analysis/blob/main/Images/ClustersCentroids.jpg)  
- The balanced accuracy score is
- The high risk precision is about only with sensitivity which makes a F1 of .
- Due to the high number of the low risk population, it's precision is with a sensitivity of .
## SMOTEENN
![SMOTEENN](https://github.com/arelysrsd87/Credit_Risk_Analysis/blob/main/Images/SMOTEENN.jpg)  
- The balanced accuracy score is
- The high risk precision is about only with sensitivity which makes a F1 of .
- Due to the high number of the low risk population, it's precision is with a sensitivity of .
## BalancedRandomForestClassifier
![BalancedRandomForestClassifier](https://github.com/arelysrsd87/Credit_Risk_Analysis/blob/main/Images/BalancedRandomForestClassifier.jpg)  
- The balanced accuracy score is
- The high risk precision is about only with sensitivity which makes a F1 of .
- Due to the high number of the low risk population, it's precision is with a sensitivity of .
## EasyEnsembleClassifier
![EasyEnsembleClassifier](https://github.com/arelysrsd87/Credit_Risk_Analysis/blob/main/Images/EasyEnsembleClassifier.jpg)  
- The balanced accuracy score is
- The high risk precision is about only with sensitivity which makes a F1 of .
- Due to the high number of the low risk population, it's precision is with a sensitivity of .
# Summary
- Summary of the results
- Recommendation on which model to use