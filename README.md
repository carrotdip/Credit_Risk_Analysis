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
**SMOTE**
Synthetic Minority OverSampling Technique
Balanced Accuracy Score:\
![smote-bac](https://github.com/carrotdip/Credit_Risk_Analysis/blob/58def611a103adffb76b543d0ca2e5fa32a5b76d/Images/SMOTE%20-%20balanced%20accuracy%20report.png)\
Confusion Matrix:\
![smote-cm](https://github.com/carrotdip/Credit_Risk_Analysis/blob/58def611a103adffb76b543d0ca2e5fa32a5b76d/Images/SMOTE%20-%20confusion%20matrix.png)\
Imbalanced Classification Report:
![smote-icr](https://github.com/carrotdip/Credit_Risk_Analysis/blob/58def611a103adffb76b543d0ca2e5fa32a5b76d/Images/SMOTE%20-%20imbalanced%20classification%20report.png)\
**Cluster Centroids**
Balanced Accuracy Score:\
![us-bac](https://github.com/carrotdip/Credit_Risk_Analysis/blob/58def611a103adffb76b543d0ca2e5fa32a5b76d/Images/US%20-%20balanced%20accuracy%20score.png)\
Confusion Matrix:\
![us-cm](https://github.com/carrotdip/Credit_Risk_Analysis/blob/58def611a103adffb76b543d0ca2e5fa32a5b76d/Images/US%20-%20confusion%20matrix.png)\
Imbalanced Classification Report:
![us-icr](https://github.com/carrotdip/Credit_Risk_Analysis/blob/58def611a103adffb76b543d0ca2e5fa32a5b76d/Images/US%20-%20imbalanced%20classification%20report.png)\
**SMOTEENN**
Balanced Accuracy Score:\
![smoteen-bac](https://github.com/carrotdip/Credit_Risk_Analysis/blob/58def611a103adffb76b543d0ca2e5fa32a5b76d/Images/SMOTEENN%20-%20balanced%20accuracy%20score.png)\
Confusion Matrix:\
![smoteen-cm](https://github.com/carrotdip/Credit_Risk_Analysis/blob/58def611a103adffb76b543d0ca2e5fa32a5b76d/Images/SMOTEENN%20-%20confusion%20matrix.png)\
Imbalanced Classification Report:
![smoteen-icr](https://github.com/carrotdip/Credit_Risk_Analysis/blob/58def611a103adffb76b543d0ca2e5fa32a5b76d/Images/SMOTEENN%20-%20imbalanced%20classification%20report.png)\
**Balanced Random Forest Classifier**
Balanced Accuracy Score:\
![brfc-bac](https://github.com/carrotdip/Credit_Risk_Analysis/blob/58def611a103adffb76b543d0ca2e5fa32a5b76d/Images/BRFC%20-%20balanced%20accuracy%20score.png)\
Confusion Matrix:\
![brfc-cm](https://github.com/carrotdip/Credit_Risk_Analysis/blob/58def611a103adffb76b543d0ca2e5fa32a5b76d/Images/BRFC%20-%20confusion%20matrix.png)\
Imbalanced Classification Report:
![brfc-icr](https://github.com/carrotdip/Credit_Risk_Analysis/blob/58def611a103adffb76b543d0ca2e5fa32a5b76d/Images/BRFC%20-%20imbalanced%20classification%20report.png)\
**Easy Emsemble Classifier**
Balanced Accuracy Score:\
![eec-bac](https://github.com/carrotdip/Credit_Risk_Analysis/blob/58def611a103adffb76b543d0ca2e5fa32a5b76d/Images/EEC%20-%20balanced%20accuracy%20score.png)\
Confusion Matrix:\
![eec-cm](https://github.com/carrotdip/Credit_Risk_Analysis/blob/58def611a103adffb76b543d0ca2e5fa32a5b76d/Images/EEC%20-%20confusion%20matrix.png)\
Imbalanced Classification Report:
![eec-icr](https://github.com/carrotdip/Credit_Risk_Analysis/blob/58def611a103adffb76b543d0ca2e5fa32a5b76d/Images/EEC%20-%20imbalanced%20classification%20report.png)\
