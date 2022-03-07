# Credit_Risk_Analysis

## Overview
The aim of this study was to determine whether someone is a high or low-risk credit risk based on their loans_stats.csv file. The project utilized the scikit-learn toolkit to develop models for predicting credit risk. Various modules were created using the data we generated in different ways. 

## Results

### Naive Random Oversampling

- The Balanced Accuracy Score was 67.99%
- High Risk precision was 1% with a recall of 59%
- Low Risk precision was 100% with a recall of 68%

IMAGE 1

### SMOTE Oversampling

- The Balanced Accuracy Score was 64.44%
- High Risk precision was 1% with a recall of 61%
- Low Risk precision was 100% with a recall of 64%

IMAGE 2

### Undersampling

- The Balanced Accuracy Score was 42.92%
- High RIsk precision was 1% with a recall of 61%
- Low Risk precision was 100% with a recall of 43%

IMAGE 3

### Combination (Over and Under) Sampling

- The Balanced Accuracy Score was 54.29%
- High Risk precision was 1% with a recall of 71%
- Low Risk precision was 100% with a recall of 54%

IMAGE 4

### Balanced Random Forest Classifier

- The Balanced Accuracy Score was 90.76%
- High Risk precision was 4% with a recall of 67%
- Low Risk precision was 100% with a recall of 91%

IMAGE 5

### Easy Ensemble AdaBoost Classifier

- The Balanced Accuracy Score was 94.28%
- High Risk precision was 7% with a recall of 90%
- Low Risk precision was 100% wtih a recall of 94%

IMAGE 6

## Summary

It is clear that the various models' precision analysis was not enough to forecast a high credit risk. The Easy Ensemble Classifier model achieved the finest results, in terms of sensitivity, which was the most effective method to evaluate credit risk.

The low-risk populations for each model that was labeled as a false positive in the highest risk category might have an adverse impact on the lender if it were to decline loans to consumers who would be paid back.

Additional research should be done to fine-tune their criteria for predicting high credit risk in low-risk groups, so that the ratios are not as large.