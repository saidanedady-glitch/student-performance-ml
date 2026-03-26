# Student Performance ML

## Overview
This project predicts whether a student will pass or fail based on academic and personal data.

## Model
- Random Forest Classifier
- Data preprocessing with label encoding
- Train/test split evaluation

## Metrics
- Accuracy
- Precision
- Recall
- F1-score

## Error Analysis
The initial model showed bias toward the majority class (pass).  
Using class_weight='balanced' improved recall for failing students and increased overall F1-score.

## Structure
- model.py → core ML model
- data/ → dataset
  
Additional notes on model performance
Improved documentation and error analysis
