# Credit_Risk_Analysis
## Overview of the Analysis
FastLending, a peer-to-peer lending services company wants to use machine learning to predict credit risk. In this situation, I will build and evaluate several machine learning algorithms to predict credit risk. The techniques I will be using include:
- Oversampling: RandomOverSampler and SMOTE algorithms
- Undersampling: ClusterCentroids algorithm
- Combinatorial approach of over- and undersampling: SMOTEENN algorithm
- Predict credit risk: BalancedRandomForestClassifier and EasyEnsembleClassifier
## Results
### Oversampling (RandomOverSampler)
- Balanced accuracy score of 64%
- Percision score of 99%
- Recall score of 60%

![oversampling](https://user-images.githubusercontent.com/110861876/205739147-7a003b2b-2a41-4aa4-b973-869bee10cd29.png)
### Oversampling (SMOTE)
- Balanced accuracy score of 66%
- Percision score of 99%
- Recall score of 69%

![SMOTE](https://user-images.githubusercontent.com/110861876/205739393-93b4233b-5b91-46de-96cc-7fd1996cdac4.png)
### Undersampling
- Balanced accuracy score of 54%
- Percision score of 99%
- recall score of 40%

![Undersampling](https://user-images.githubusercontent.com/110861876/205739565-041e4c77-5428-4372-8517-76f105767efa.png)
### Combination (SMOTEENN)
- Balanced accuracy score of 64%
- Percision score of 99%
- Recall score of 57%

![Combination](https://user-images.githubusercontent.com/110861876/205739779-459df33f-b65a-4a0d-afb6-656bdfdb445a.png)
### Ensemble Learners (BalancedRandomForestClassifier)
- Balanced accuracy score of 78%
- Percision score of 99%
- Recall score of 87%

![Random Forest](https://user-images.githubusercontent.com/110861876/205740037-ebfdc2e4-64e0-4f11-8e24-95e46b7d46b8.png)
### Ensemble Learners (Easy Ensemble AdaBoost Classifier)
- Balanced accuracy score of 93%
- Percision score of 99%
- Recall score of 94%

![AdaBoost](https://user-images.githubusercontent.com/110861876/205740203-420d4f06-3d03-4989-8334-1df878046c3f.png)
## Summary
In summary, if we were to use a model in the future for predicting whether loan applications will pass or fail, we would use the EasyEnsembleClassifier model. This was the most accurate and had the best recall percentage out of all the models.
