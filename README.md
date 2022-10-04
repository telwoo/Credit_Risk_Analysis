# Credit_Risk_Analysis

## Overview of the analysis: 
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. I'll be employing different techniques to train and evaluate models with unbalanced classes. I will use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling. I will use the following functions:
- imbalanced-learn
- scikit-learn
- RandomOverSampler
- SMOTE
- ClusterCentroids
- SMOTTEENN
- BalancedRandomForestClassifier
- EasyEnsembleClassifier

## Results: 
The results for the 6 machine learning models including their respective balanced accuracy, precision, and recall scores are as follows:

Naive Random Oversampling

![NAIVE_over](https://user-images.githubusercontent.com/106715923/193709120-4ca9fce3-de3b-48d6-a6ff-52ea7786f3b8.png)



SMOTE Oversampling

![smote_OVER](https://user-images.githubusercontent.com/106715923/193709163-d23de37e-133b-45f5-9d1a-6c139d3b928a.png)


Undersampling

![UNDER](https://user-images.githubusercontent.com/106715923/193709202-b82b39e1-91ad-44b9-87ad-a52b2e2b9d3c.png)



Combination Under-Oversampling

![combo_over_under](https://user-images.githubusercontent.com/106715923/193709058-7795dce3-e95c-4082-88f9-18a648bc06d4.png)


Balanced Random Forest Classifier

![balanced_random_forest](https://user-images.githubusercontent.com/106715923/193709002-3ad85abc-171b-45d7-83d8-2ecd66ece30e.png)



Easy Ensemble AdaBoost Classifier

![east_ensemble](https://user-images.githubusercontent.com/106715923/193708914-c651704c-095d-410f-bd03-bfe9355c044c.png)
blana




## Summary: 
Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.

