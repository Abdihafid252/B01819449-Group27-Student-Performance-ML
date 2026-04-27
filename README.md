# B01819449 — Group 27 — Student Grade Prediction Using Machine Learning

## Project Overview
This repository contains the complete implementation of the MSc Data Analytics 
dissertation project (Group 27) focused on predicting student academic grade 
outcomes using supervised machine learning techniques. The implementation follows 
a structured end-to-end pipeline encompassing data collection, pre-processing, 
feature engineering, class balancing, feature selection, model training and 
evaluation.

## Research Objectives
- Identify and pre-process a suitable student performance dataset from Kaggle
- Apply feature engineering to enrich predictive capability of the dataset
- Address class imbalance using the Synthetic Minority Oversampling Technique (SMOTE)
- Perform dimensionality reduction using Recursive Feature Elimination (RFE)
- Develop and compare three supervised machine learning classifiers
- Evaluate model performance using accuracy, F1-score, precision, recall and ROC-AUC

## Machine Learning Models
- Logistic Regression
- Decision Tree
- Random Forest (Best model — 86.11% accuracy)

## Key Techniques
- SMOTE — applied exclusively to training set to prevent data leakage
- Recursive Feature Elimination (RFE) — reduced 38 features to 15
- GridSearchCV — hyperparameter tuning for Random Forest
- 10-fold Cross-Validation — CV score 91.69%

## Tools and Technologies
- Python 3
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Matplotlib
- Seaborn

## Repository Contents
- `B01819449_Group27_ML_Implementation.ipynb` — Complete Jupyter Notebook
- `student-mat.csv` — Original dataset (Kaggle)
- `student_cleaned_group27.csv` — Pre-processed dataset

## Dataset
Student Performance Dataset — sourced from Kaggle
- Original: 395 student records, 33 features
- Working dataset: 357 records after cleaning

## Results
| Model | Accuracy | CV Score |
|---|---|---|
| Random Forest | 86.11% | 91.69% |
| Logistic Regression | 81.94% | 90.16% |
| Decision Tree | 76.39% | 87.90% |

## Author
**Abdihafid**  
Banner ID: B01819449  
Group 27 — MSc Data Analytics  
University of the West of Scotland  
2026
