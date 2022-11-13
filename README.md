# Credit_Risk_Analysis

## Overview of Analysis
This challenge aims to employ different techniques to train and evaluate models with unbalanced classes. We have been asked to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling. 

## Results

### Data Loading 
![Screen Shot 2022-11-12 at 10.12.39 PM.png](https://github.com/Simranbains1/Credit_Risk_Analysis/blob/main/Images/Screen%20Shot%202022-11-12%20at%2010.12.39%20PM.png)

### Naive Random Oversampling

- Balanced Accuracy Score: 0.66127...
- Precision Score: low for high-risk loans and high for low-risk loans
- Recall Score: high/low risk = .66/.67

![Screen Shot 2022-11-12 at 10.10.16 PM.png](https://github.com/Simranbains1/Credit_Risk_Analysis/blob/main/Images/Screen%20Shot%202022-11-12%20at%2010.10.16%20PM.png)

### SMOTE Oversampling

- Balanced Accuracy Score: 0.63032...
- Precision Score: low for high-risk loans and high for low-risk loans
- Recall Score: high/low risk = .62/.64

![Screen Shot 2022-11-12 at 10.10.32 PM.png](https://github.com/Simranbains1/Credit_Risk_Analysis/blob/main/Images/Screen%20Shot%202022-11-12%20at%2010.10.32%20PM.png)

### Undersampling

- Balanced Accuracy Score: 0.63032...
- Precision Score: low for high-risk loans and high for low-risk loans
- Recall Score: high/low risk = .63/.40

![Screen Shot 2022-11-12 at 10.11.05 PM.png](https://github.com/Simranbains1/Credit_Risk_Analysis/blob/main/Images/Screen%20Shot%202022-11-12%20at%2010.11.05%20PM.png)

### Combination Sampling 

- Balanced Accuracy Score: 0.51737...
- Precision Score: low for high-risk loans and high for low-risk loans
- Recall Score: high/low risk = .70/.57

![Screen Shot 2022-11-12 at 10.11.13 PM.png](https://github.com/Simranbains1/Credit_Risk_Analysis/blob/main/Images/Screen%20Shot%202022-11-12%20at%2010.11.13%20PM.png)

### BRFC

- Balanced Accuracy Score: 0.78776...
- Precision Score: low for high-risk loans and high for low-risk loans
- Recall Score: high/low risk = .67/.91

![Screen Shot 2022-11-12 at 10.11.57 PM.png](https://github.com/Simranbains1/Credit_Risk_Analysis/blob/main/Images/Screen%20Shot%202022-11-12%20at%2010.11.57%20PM.png)

### Easy Ensemble AdaBoost Classifier

- Balanced Accuracy Score: 0.92542...
- Precision Score: low for high-risk loans and high for low-risk loans
- Recall Score: high/low risk = .91/.94

![Screen Shot 2022-11-12 at 10.12.06 PM.png](https://github.com/Simranbains1/Credit_Risk_Analysis/blob/main/Images/Screen%20Shot%202022-11-12%20at%2010.12.06%20PM.png)

## Summary
For this set of data, the Easy Ensemble AdaBoost Classifier is the best model, due to its .93 balanced accuracy. The other models came in at .88 and below. The Easy Ensemble AdaBoost Classifier also had the highest recall score, which makes it the best model for this specific credit card analysis.
