# Credit_Risk_Analysis

## Credit_Risk_Analysis Overview
  The purpose of this analysis was to apply data preparation, statistical reasoning, and machine learning to predict credit card risk. 
  
## Credit_Risk_Analysis Results
  - The balanced accuracy score for RandomOverSampler is 0.618. The precision score is 0.01 and the recall score is 0.57.
  - The balanced accuracy score for SMOTE is 0.626. The precision score is 0.01 and the recall score is 0.56.
  - The balanced accuracy score for ClusterCentroids is 0.506. The precision score is 0.00 and the recall score is 0.48.
  - The balanced accuracy score for SMOTEENN is 0.646. The precision score is 0.01 and the recall score is 0.72.
  - The balanced accuracy score for BalancedRandomForestClassifier is 0.732. The precision score is 0.02 and the recall score is 0.59.
  - The balanced accuracy score for EasyEnsembleClassifier is 0.823. The precision score is 0.03 and the recall score is 0.76.

## Credit_Risk_Analysis Summary
  All of the precison scores for these models have a low risk equal to 1.00. As for the recall scores, the high risk values vary from 0.48 to 0.76. The model I recommend to use is the EasyEnsembleClassifier, as it has the highed recall scores for both risk types, and also has the greatest score on the low_risk for credit cards, which is something valuable to know for predicting users of credit card risk.
  
  
  <img src="algorithms.png" width="95%" height="95%" title="Algorithms Galore">
