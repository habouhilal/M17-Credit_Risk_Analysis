# M17-Credit_Risk_Analysis

## Overview 

This project is about machine learning. The analysis consist of using different techniques to predict Credit risk. First, we trained and evaluated models with unbalanced classes. We also used imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.
Using the credit card credit dataset from LendingClub, we first oversample the data using the RandomOverSampler and SMOTE algorithms and undersample the data using the ClusterCentroids algorithm. Then, we used a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. At last, we evaluated the performance of these models.

## Results 

### RandomOverSampler


The balanced accuracy score for the RandomOverSampler is
The Precision for the RandomOverSampler is 
The Recall for RandomOverSampler is 

### SMOTE


The balanced accuracy score for SMOTE is 
The Precision for SMOTE is
The Recall for SMOTE is 

### Cluster Centroids


The balanced accuracy score for ClusterCentroids is 
The Precision for ClusterCentroids is 
The Recall for ClusterCentroids is 
### SMOTEENN


The balanced accuracy score for SMOTEENN is 
The Precision for SMOTEENN is 
The Recall for SMOTEENN is 

### BalancedRandomForestClassifier

The balanced accuracy score for the BalancedRandomForestClassifier is 
The Precision for BalancedRandomForestClassifier is
The Recall for BalancedRandomForestClassifier is

### EasyEnsembleClassifier

The balanced accuracy score for the EasyEnsembleClassifier is 
The Precision for EasyEnsembleClassifier is
The Recall for EasyEnsembleClassifier 

## Sammury 

In Sammury, the least accurate model was the Cluster Centroid model with a 0.51 balanced accuracy score and a recall of 0.57
The best performing models are the BalancedRandomForestClassifier and the EasyEnsembleClassifier. EasyEnsembleClassifier had the highest balanced accuracy score at 0.925 and a recall of 0.94, with BalancedRandomForestClassifier coming in with the second best scores in these two categories. 



The precision did not differ significantly between any of the methods, with all averageing 0.99. Of any of these models, EasyEnsembleClassifier would be the recommendation, followed by BalancedRandomForestClassifier.