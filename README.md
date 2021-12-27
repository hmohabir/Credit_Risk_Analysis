# Credit_Risk_Analysis
Module 17 Supervised Machine Learning



## Overview of the loan prediction analysis

The purpose of this analysis was to determine credit risk for LendingClub, a peer-to-peer lending services company, when a loas was processed. A number of determinants were looked at. Varoius approches were used to train and test data in order to arrive at an outcome. These approaches included: 

-  Naive Random Oversampling
-  SMOTE Oversampling
-  Undersampling
-  Combination (Over and Under) Sampling
-  Balanced Random Forest Classifier
-  Easy Ensemble AdaBoost Classifier

## Results

The various approached provided varing outcomes. I will go through them individually:

### Naive Random Oversampling

![Niave Random Oversampling](https://github.com/hmohabir/Credit_Risk_Analysis/blob/main/Naive%20Random%20Oversampling.PNG)

This sampling's accuracy score was 66.6%
The Recall score was 67% for both high and low risk.
The Support are nowhere near the same.
The high risk precision score is 1%

### SMOTE Oversampling

![SMOTE Oversampling](https://github.com/hmohabir/Credit_Risk_Analysis/blob/main/SMOTE%20Oversampling.PNG)

This sampling's accuracy score was 62.6%
The Recall score was were not too far apart.
The Support are nowhere near the same.
The high risk precision score is 1% 

### Undersampling 

![Undersampling](https://github.com/hmohabir/Credit_Risk_Analysis/blob/main/Undersampling.PNG)

This sampling's accuracy score was 51.7%
The Recall score was were not too far apart.
The Support are nowhere near the same.
The high risk precision score is 1%

### Combination (Over and Under) Sampling

![Combination Sampling](https://github.com/hmohabir/Credit_Risk_Analysis/blob/main/Combination%20Sampling.PNG)

This sampling's accuracy score was 60.6%
The Recall score was were not too far apart.
The Support are nowhere near the same.
The high risk precision score is 1%

### Balanced Random Forest Classifier

![Balanced Random Forest Classifier](https://github.com/hmohabir/Credit_Risk_Analysis/blob/main/Balanced%20Random%20Forest%20Classifier.PNG)

This sampling's accuracy score was 91.8%
The Recall score was were not too far apart.
The Support are nowhere near the same.
The high risk precision score is 4%

### Easy AdaBoost Classifier

![Easy AdaBoost Classifier](https://github.com/hmohabir/Credit_Risk_Analysis/blob/main/Easy%20Ensemble%20Classifier.PNG

This sampling's accuracy score was 91.8%
The Recall score was were not too far apart.
The Support are nowhere near the same.
The high risk precision score is 4%
The weighed precision average was pretty high.

## Summary 

Lower accruacy were encountered in:

-  Naive Random Oversampling
-  SMOTE Oversampling
-  Undersampling
-  Combination (Over and Under) Sampling

However, these approached yielded over 90% accruacy:

-  Balanced Random Forest Classifier
-  Easy Ensemble AdaBoost Classifier

Of the two, the latter peovided the best combination of accuracy, high risk precision and high risk recall. Besides, the training and testing data were pretty good. As such, I would recommend this as the best fot for the best results. With regards to the other techniques, I would not write them off. More work will need to be done to see if their results would imprive with better training and testing.


