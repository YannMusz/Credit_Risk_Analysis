# Credit_Risk_Analysis
Supervised Machine Learning

## Overview of the loan prediction risk analysis:   
Techniques were used to train and evaluate models with unbalanced classes. Various libraries and algorithms are used to build models using resampling including: 
1. imbalanced-learn 
2. scikit-learn
3. ClusterCentroids algorithm
4. RandomOverSampler
5. SMOTEENN algorithm
6. EasyEnsembleClassifier 
7. BalancedRandomForestClassifier

## Purpose: 
1. Explain how a machine learning algorithm is used in data analytics.
2. Create training and test groups from a given data set.
3. Implement the logistic regression, decision tree, random forest, and support vector machine algorithms.
7. Use ensemble and resampling techniques to improve model performance.

## Results:
The following results for the six machine learning models including their respective balanced accuracy, precision, and recall score  

### Naive Random Oversampling
![Pic 1](https://github.com/YannMusz/Credit_Risk_Analysis/blob/main/Machine_Learning_Challege/Images/1_Naive_Random_Oversampling.PNG)     

### SMOTE Oversampling
![Pic 2](https://github.com/YannMusz/Credit_Risk_Analysis/blob/main/Machine_Learning_Challege/Images/2_SMOTE_Oversampling.PNG)     

### Undersampling
![Pic 3](https://github.com/YannMusz/Credit_Risk_Analysis/blob/main/Machine_Learning_Challege/Images/3_Undersampling.PNG)     

### Combination Under-Over Sampling
![Pic 4](https://github.com/YannMusz/Credit_Risk_Analysis/blob/main/Machine_Learning_Challege/Images/4_Combo_under_over_sampling.PNG)     

### Balanced Random Forest Classifier
![Pic 5](https://github.com/YannMusz/Credit_Risk_Analysis/blob/main/Machine_Learning_Challege/Images/5_Bal_random_forest_calssifier.PNG)     

### Easy Ensemble AdaBoost Classifier
![Pic 6](https://github.com/YannMusz/Credit_Risk_Analysis/blob/main/Machine_Learning_Challege/Images/6_easy_ensemble_adaboost_classifier.PNG)     

## Summary:
When working with balanced accuracy, the highest compared accuracy between 0 and 1 and is closest to 1 is the best machine learning model.  For credit card data set, the Easy Ensemble AdaBoost Classifier is the best model to pick.  The other models were below .80 . The precision for all models were similar and within a good range .The Easy Ensemble AdaBoost Classifier had the highest score, making it the final best machine learning model to choose for further credit card analysis.   
