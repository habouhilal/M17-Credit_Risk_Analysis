# M17-Credit_Risk_Analysis

## Overview 

This project is about machine learning. The analysis consist of using different techniques to predict Credit risk. First, we trained and evaluated models with unbalanced classes. We also used imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.
Using the credit card credit dataset from LendingClub, we first oversample the data using the RandomOverSampler and SMOTE algorithms and undersample the data using the ClusterCentroids algorithm. Then, we used a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. At last, we evaluated the performance of these models.

## Results 

### RandomOverSampler

<img width="883" alt="RandomOverSampler" src="https://user-images.githubusercontent.com/91625564/153980541-9cbc9a25-6895-4abf-b74a-55d8f9822af6.png">


The balanced accuracy score for the RandomOverSampler is 65%
The high-risk precision is about 1% only with 69% recall and F1 of 2%.
The low-risk precision is almost 100% with a recall of 59%.

### SMOTE

<img width="883" alt="SMOTE" src="https://user-images.githubusercontent.com/91625564/153980325-3f30ee6d-72c3-4ada-b327-8ea2ce5c54b1.png">


The balanced accuracy score  is 65%
The high-risk precision is about 1% only with 69% recall and F1 of 2%.
The low-risk precision is almost 100% with a recall of 59%.

### Cluster Centroids

<img width="883" alt="Cluster Centroids" src="https://user-images.githubusercontent.com/91625564/153980435-4bdab07b-f5ae-473c-9dd0-af8354d48176.png">


The balanced accuracy score for ClusterCentroids is 54%
The high-risk precision is still 1% with 69% sensitivity and a F1 of 1%.
The low-risk recall is at 40%.


### BalancedRandomForestClassifier

<img width="883" alt="Balanced Random Forest" src="https://user-images.githubusercontent.com/91625564/153981715-a077530e-8e6b-46d3-9789-5cfab621111d.png">


The balanced accuracy score for the BalancedRandomForestClassifier is 78% 
The high-risk precision is still low at 3% only with 70% recall and F1 of only 6%.
The low-risk recall is now 87% with 100% precision.

### EasyEnsembleClassifier

<img width="883" alt="EasyEnsembleClassifier" src="https://user-images.githubusercontent.com/91625564/153980485-221d0966-58a8-4b0f-96f2-cb5c2bb0cc10.png">

The balanced accuracy score for the EasyEnsembleClassifier is 93%
The high-risk precision is at 9% with a 92% recall and F1 of 16%.
The low-risk precision is at 100% with the recall at 94%.

## Sammury 

In Sammury, the least accurate model was the Cluster Centroid model with a 0.54 balanced accuracy score and a recall of 0.40. The best performing model is the EasyEnsembleClassifier. EasyEnsembleClassifier had the highest balanced accuracy score at 0.93 and a recall of 0.94. 
RandomOverSampler,  SMOTE and Cluster Centroids these models may not be the best for preventing fraudulent loan applications because the model's accuracy is low, and the precision and recall are not good enough to state that the models will be good at classifying fraudulent loan applications.
For this analysis, the most accurate model is EasyEnsembleClassifier. 
