# Credit Risk Analysis
## Overview
The purpose of this analysis was to evaluate several machine learning models to predict credit risk. We first oversampled with Random Oversampling and SMOTE, then undersampled with the Cluster Centroid approach, and finally, used a combinatory analysis with over- and under-sampling with the SMOTEENN algorithm. We then utilized two machine learning models, Balanced Random Forest Classifier and Easy Ensemble Classifier, to reduce bias within the models. We will then compare the performance of these machine learning models to determine the best approach to predict credit risk.
## Results
**Random Oversampling**\
Balanced Accuracy Score:\
![ro-bac](https://github.com/carrotdip/Credit_Risk_Analysis/blob/58def611a103adffb76b543d0ca2e5fa32a5b76d/Images/NRO%20-%20balanced%20accuracy%20score.png)\
Confusion Matrix:\
![ro-cm](https://github.com/carrotdip/Credit_Risk_Analysis/blob/58def611a103adffb76b543d0ca2e5fa32a5b76d/Images/NRO%20-%20confusion%20matrix.png)\
Imbalanced Classification Report:
![ro-icr](https://github.com/carrotdip/Credit_Risk_Analysis/blob/58def611a103adffb76b543d0ca2e5fa32a5b76d/Images/NRO%20-%20imbalanced%20classification%20report.png)\
In the random oversampling model, there is a 64% balanced accuracy score with high-risk precision (HRP) at 1% and high-risk sensitivity (HRS) at 59%, and an F1 score of 2%. As for the low_risk precision (LRP) and low_risk sensitivity (LRS), the values are 100% and 69% respectively, with an F1 score of 82%.\
**SMOTE**\
Balanced Accuracy Score:\
![smote-bac](https://github.com/carrotdip/Credit_Risk_Analysis/blob/58def611a103adffb76b543d0ca2e5fa32a5b76d/Images/SMOTE%20-%20balanced%20accuracy%20report.png)\
Confusion Matrix:\
![smote-cm](https://github.com/carrotdip/Credit_Risk_Analysis/blob/58def611a103adffb76b543d0ca2e5fa32a5b76d/Images/SMOTE%20-%20confusion%20matrix.png)\
Imbalanced Classification Report:
![smote-icr](https://github.com/carrotdip/Credit_Risk_Analysis/blob/58def611a103adffb76b543d0ca2e5fa32a5b76d/Images/SMOTE%20-%20imbalanced%20classification%20report.png)\
For the Synthetic Minority OverSampling Technique (SMOTE), there is a 62% balanced accuracy score with HRP at 1%, HRS at 59%, LRP at 100%, and LRS at 66%. There is an F1 score of 2% and 79% for the high risk and low risk categories, respectively.\
**Cluster Centroids**\
Balanced Accuracy Score:\
![us-bac](https://github.com/carrotdip/Credit_Risk_Analysis/blob/58def611a103adffb76b543d0ca2e5fa32a5b76d/Images/US%20-%20balanced%20accuracy%20score.png)\
Confusion Matrix:\
![us-cm](https://github.com/carrotdip/Credit_Risk_Analysis/blob/58def611a103adffb76b543d0ca2e5fa32a5b76d/Images/US%20-%20confusion%20matrix.png)\
Imbalanced Classification Report:
![us-icr](https://github.com/carrotdip/Credit_Risk_Analysis/blob/58def611a103adffb76b543d0ca2e5fa32a5b76d/Images/US%20-%20imbalanced%20classification%20report.png)\
As for the undersampling model, there is a balanced accuracy score of 53%, HRP of 1%, HRS of 61%, LRP of 100%, and LRS of 45%. There is an F1 score of 1% and 62% for the high risk and low risk categories, respectively.\
**SMOTEENN**\
Balanced Accuracy Score:\
![smoteen-bac](https://github.com/carrotdip/Credit_Risk_Analysis/blob/58def611a103adffb76b543d0ca2e5fa32a5b76d/Images/SMOTEENN%20-%20balanced%20accuracy%20score.png)\
Confusion Matrix:\
![smoteen-cm](https://github.com/carrotdip/Credit_Risk_Analysis/blob/58def611a103adffb76b543d0ca2e5fa32a5b76d/Images/SMOTEENN%20-%20confusion%20matrix.png)\
Imbalanced Classification Report:
![smoteen-icr](https://github.com/carrotdip/Credit_Risk_Analysis/blob/58def611a103adffb76b543d0ca2e5fa32a5b76d/Images/SMOTEENN%20-%20imbalanced%20classification%20report.png)\
For the over- and under- sampling model with SMOTEEN, there is a balanced accuracy score of 64%, HRP of 1%, HRS of 69%, LRP of 100%, and LRS of 58%. There is an F1 score of 1% and 73% for the high risk and low risk categories, respectively.\
**Balanced Random Forest Classifier**\
Balanced Accuracy Score:\
![brfc-bac](https://github.com/carrotdip/Credit_Risk_Analysis/blob/58def611a103adffb76b543d0ca2e5fa32a5b76d/Images/BRFC%20-%20balanced%20accuracy%20score.png)\
Confusion Matrix:\
![brfc-cm](https://github.com/carrotdip/Credit_Risk_Analysis/blob/58def611a103adffb76b543d0ca2e5fa32a5b76d/Images/BRFC%20-%20confusion%20matrix.png)\
Imbalanced Classification Report:
![brfc-icr](https://github.com/carrotdip/Credit_Risk_Analysis/blob/58def611a103adffb76b543d0ca2e5fa32a5b76d/Images/BRFC%20-%20imbalanced%20classification%20report.png)\
For the balanced random forest classifier model, there is a balanced accuracy score of 79%, HRP of 4%, HRS of 67%, LRP of 100%, and LRS of 91%. There is an F1 score of 7% and 95% for the high risk and low risk categories, respectively.\
**Easy Emsemble Classifier**\
Balanced Accuracy Score:\
![eec-bac](https://github.com/carrotdip/Credit_Risk_Analysis/blob/58def611a103adffb76b543d0ca2e5fa32a5b76d/Images/EEC%20-%20balanced%20accuracy%20score.png)\
Confusion Matrix:\
![eec-cm](https://github.com/carrotdip/Credit_Risk_Analysis/blob/58def611a103adffb76b543d0ca2e5fa32a5b76d/Images/EEC%20-%20confusion%20matrix.png)\
Imbalanced Classification Report:
![eec-icr](https://github.com/carrotdip/Credit_Risk_Analysis/blob/58def611a103adffb76b543d0ca2e5fa32a5b76d/Images/EEC%20-%20imbalanced%20classification%20report.png)\
For the easy emsemble classifier model, there is a balanced accuracy score of 93%, HRP of 7%, HRS of 91%, LRP of 100%, and LRS of 94%. There is an F1 score of 14% and 97% for the high risk and low risk categories, respectively.\
## Summary
