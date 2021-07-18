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
## SMOTE
![SMOTE](https://github.com/arelysrsd87/Credit_Risk_Analysis/blob/main/Images/SMOTE.jpg)
## ClusterCentroids
![ClusterCentroids](https://github.com/arelysrsd87/Credit_Risk_Analysis/blob/main/Images/ClustersCentroids.jpg)
## SMOTEENN
![SMOTEENN](https://github.com/arelysrsd87/Credit_Risk_Analysis/blob/main/Images/SMOTEENN.jpg)
## BalancedRandomForestClassifier
![BalancedRandomForestClassifier](https://github.com/arelysrsd87/Credit_Risk_Analysis/blob/main/Images/BalancedRandomForestClassifier.jpg)
## EasyEnsembleClassifier
![EasyEnsembleClassifier](https://github.com/arelysrsd87/Credit_Risk_Analysis/blob/main/Images/EasyEnsembleClassifier.jpg)
# Summary
- Summary of the results
- Recommendation on which model to use