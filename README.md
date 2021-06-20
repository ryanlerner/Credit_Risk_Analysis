# Credit_Risk_Analysis

## Purpose of Analysis
This analysis was intended to predict credit risk with various machine learning models. To predict credit risk, we used oversampling methods followed by an undersampling method and a SMOTEEN method, which combines over- and undersampling. To assess the accuracy of these models, we also calculated accuracy scores and confusion matrices to evaluate their performances. These models were then compared a BalancedRandomForestClassifier and EasyEnsembleClassifier which are intended to reduce bias. 

## RESULTS

### Oversampling
- Naive Random Oversampling
  - Balanced Accuracy Score: 65%
  - Precision Score: 99%
  - Recall Score: 66%
- SMOTE Oversampling
  - Balanced Accuracy Score: 65%
  - Precision Score: 99%
  - Recall Score: 65%

### Undersampling
- ClusterCentroids
  - Balanced Accuracy Score: 53%
  - Precision Score: 99%
  - Recall Score: 45%

### Combination (Over and Under) Sampling
- SMOTEENN
  - Balanced Accuracy Score: 64%
  - Precision Score: 99%
  - Recall Score: 56%
 
### Ensemble Learners
- Balanced Random Forest Classifier
  - Balanced Accuracy Score: 79%
  - Precision Score: 99%
  - Recall Score: 91%
- Easy Ensemble AdaBoost Classifier
  - Balanced Accuracy Score: 93%
  - Precision Score: 99%
  - Recall Score: 94%
