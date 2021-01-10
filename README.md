# Credit_Risk_Analysis

## Overview of the analysis

The purpose of this project is to apply machine learning to credit card risk. To do so the following algorithms will be applied: RandomOverSampler, SMOTE, undersampling using the ClusterCentroids algorithm, and the SMOTEENN algorithm. The two new machine learning models will be compared to reduce bias (BalancedRandomForestClassifier and EasyEnsembleClassifier). The output of this analysis will be evaluation of this models and their accuracy to predict credit risk.

## Results
The balanced accuracy scores and the precision and recall scores of all six machine learning models are below:

- Naive Random Oversampling 

![alt_text](https://github.com/NassimNatA/Credit_Risk_Analysis/blob/main/Screen%20Shot%202021-01-10%20at%201.33.30%20AM.png)

**precision: 0.99, recall: 0.62, bal accuracy: 0.640324421824783**

- SMOTE Oversampling

![alt_text](https://github.com/NassimNatA/Credit_Risk_Analysis/blob/main/Screen%20Shot%202021-01-10%20at%201.33.39%20AM.png)

**precision: 0.99, recall 0.62, bal accuracy: 0.640324421824783**

- Undersampling

![alt_text](https://github.com/NassimNatA/Credit_Risk_Analysis/blob/main/Screen%20Shot%202021-01-10%20at%201.33.45%20AM.png)

**precision: 0.99, recall 0.62, bal accuracy: 0.5443043836656818**

- Combination (Over and Under) Sampling

![alt_text](https://github.com/NassimNatA/Credit_Risk_Analysis/blob/main/Screen%20Shot%202021-01-10%20at%201.33.49%20AM.png)

**precision: 0.99, recall: 0.57, bal accuracy: 0.6449163069955265**

- Balanced Random Forest Classifier

![alt_text](https://github.com/NassimNatA/Credit_Risk_Analysis/blob/main/Screen%20Shot%202021-01-10%20at%201.44.52%20AM.png)

**precision: 0.99, recall: 0.94, bal accuracy: 0.6830221521918328**

- Easy Ensemble AdaBoost Classifier

![alt_text](https://github.com/NassimNatA/Credit_Risk_Analysis/blob/main/Screen%20Shot%202021-01-10%20at%201.44.58%20AM.png)

**precision: 0.99, recall: 0.94, bal accuracy: 0.9316600714093861** 



Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
