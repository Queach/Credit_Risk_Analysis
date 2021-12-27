# Machine Learning Analysis
## Overview of Project
An analysis of a data set using supervised machine learning

## Purpose
The purpose of this analysis is to use various types of machine learning to determine an outcome, and comparing the results of different types to each other
## Analysis and Results
### Naive Oversample

- Accuracy Score: 0.649
- Pre:0.01
- Rec:0.69

![results](https://raw.githubusercontent.com/Queach/Credit_Risk_Analysis/main/Resources/Naive.png "results")

### SMOTE

- Accuracy Score: 0.662
- Pre:0.01
- Rec:0.63

![results](https://raw.githubusercontent.com/Queach/Credit_Risk_Analysis/main/Resources/SMOTE.png "results")

### Clusters 

- Accuracy Score: 0.544
- Pre:0.01
- Rec:0.69

![results](https://raw.githubusercontent.com/Queach/Credit_Risk_Analysis/main/Resources/Cluster.png "results")

### SMOTEENN

- Accuracy Score: 0.690
- Pre:0.01
- Rec:0.80

![results](https://raw.githubusercontent.com/Queach/Credit_Risk_Analysis/main/Resources/SMOTEENN.png "results")

### Random Forest

- Accuracy Score: 0.673
- Pre:0.90
- Rec:0.35

![results](https://raw.githubusercontent.com/Queach/Credit_Risk_Analysis/main/Resources/Random%20Tree.png "results")

### EasyEnsemble

- Accuracy Score: 0.931
- Pre:0.09
- Rec:0.92

![results](https://raw.githubusercontent.com/Queach/Credit_Risk_Analysis/main/Resources/ADA.png "results")

## Summary

The results show that Forest models were better at predicting true positives, where as a SMOTEEN was better at predicting true negatives.
If the client wishes to have more precision they should use a forest model, if they want more sensitivity they should use a SMOTEEN model.
Overall no model provided any worthwhile accuracy and further development should be taken in the datasets.
