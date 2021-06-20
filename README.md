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

## Summary
Based on the results above, it appears that the Ensemble Learners are the most effective in predicting credit risk in terms of their accuracy and recall scores. The precision scores for all six models used are very similar, but the accuracy scores for the ensemble learning models are much higher. Based on these scores, the Easy Ensemble AdaBoost Classifier is the most accurate in predicting credit risk with a score of 93%, while the recall score is also highest at 94%. 
