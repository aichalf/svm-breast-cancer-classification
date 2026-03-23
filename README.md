# Support Vector Machine for Breast Cancer Classification

This project applies Support Vector Machines (SVM) to the Breast Cancer Wisconsin dataset using Python and scikit-learn.

## Objective
The goal is to classify tumors as malignant or benign using a complete machine learning workflow:
- data exploration
- preprocessing
- train/test split
- Linear SVM
- RBF SVM
- hyperparameter tuning
- evaluation and interpretation

## Dataset
Breast Cancer Wisconsin dataset from scikit-learn.

- 569 observations
- 30 numerical features
- Binary target: malignant vs benign

## Methods
The notebook compares:
1. Linear SVM
2. RBF SVM
3. Tuned RBF SVM with GridSearchCV

## Results
- Linear SVM achieved about 97% test accuracy
- RBF SVM achieved about 98% test accuracy
- Hyperparameter tuning produced similar performance, suggesting the dataset is already well-structured

## Main Insight
The small performance gap between linear and RBF SVM suggests that the dataset is close to linearly separable. This supports the maximum-margin principle introduced by Cortes and Vapnik (1996).

## Technologies
- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- scikit-learn

## Reference
Cortes, C., & Vapnik, V. (1996). Support-vector networks.
