In this repository, I have placed my notebooks with works on feature selection. The aim of doing the work is to gain hands-on experience, building intuition, and getting familiar with the most frequent approaches (filter, wrapper, embedded and hybrid methods) when working on feature selection. Feature selection itself is done with usage of scikit-learn==0.23.2 and imbalanced-learn==0.7.0 libraries.

## Table of Contents

1. **01_FILTER_METHODS_Constant_Quasi_Constant_Duplicates**
	1. Removing Constant Features
	2. Removing Quasi-Constant Features
	3. Removing Duplicated Features

2. **02_FILTER_METHODS_Correlation**
	1. Removing Correlated Features 
	2. Basic Selection Methods + Correlation - Pipeline

3. **03_FILTER_METHODS_Filter_Statistical_Tests**
	1. Mutual Information
	2. Chi-square distribution
	3. Anova
	4. Basic Selection Methods + Statistical Methods - Pipeline

4. **04_FILTER_METHODS_Other_Metrics**
	1. Univariate roc-auc, mse, etc.

5. **05_WRAPPER_METHODS**
	1. Step Forward Feature Selection
	2. Step Backward Feature Selection
	3. Exhaustive Feature Selection

6. **06_EMBEDED_METHODs_Linear_Coefficients**
	1. Logistic Regression Coefficients
	2. Linear Regression Coefficients
	3. Effect of Regularization on Coefficients
	4. Basic Selection Methods + Correlation + Embedded - Pipeline 

7. **07_EMBEDED_METHODS_Embedded_Lasso**
	1. Lasso 
	2. Basic Selection Methods + Correlation + Lasso - Pipeline 

8. **08_EMBEDED_METHODs_Embedded-Tree_Importance**
	1. Random Forest derived Feature Importance
	2. Tree importance + Recursive Feature Elimination
	3. Basic Selection Methods + Correlation + Tree importance - Pipeline

9. **09_HYBRID_METHODS**
	1. Feature Shuffling
	2. Recursive Feature Elimination
	3. Recursive Feature Addition

=======================================================

**Required Packages**:
- autopep8==1.5.4
- imbalanced-learn==0.7.0
- matplotlib==3.3.2
- numpy==1.19.2
- pandas==1.1.3
- scikit-learn==0.23.2
- scipy==1.5.2
- seaborn==0.11.0
- yapf==0.30.0
- yellowbrick==1.2
