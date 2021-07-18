# Credit_Risk_Analysis
# Overview of the analysis
Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.
# Results
## RandomOVerSampler
![RandomOVerSampler](https://github.com/arelysrsd87/Credit_Risk_Analysis/blob/main/Images/NaiveRandomOversampling.jpg)  
- The balanced accuracy score is 66.0%.
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
- The balanced accuracy score is 93.1%.
- The high risk precision is about only 9% with sensitivity of 92% which makes a F1 of 16%.
- Due to the high number of the low risk population, it's precision is 100% with a sensitivity of 94%.
# Summary
- All the models used to perform the credit risk analysis show weak precision in determining if a credit risk is high.
- The ensemble models brought a lot more improvment, specially, on the sensitivity of the high risk credits.
- The EasyEnsembleClassifier model shows a recall of 93% so it detects almost all high risk credit. On another hand, with a low precision, a lot of low risk credits are still falsely detected as high risk which would penalize the bank's credit strategy and infer on its revenue by missing those business opportunities.
- For those reasons, I would not recommend the bank to use any of these models to predict credit risk.
