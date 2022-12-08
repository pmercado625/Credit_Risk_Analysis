# Overview
The purpose of this project is to employ various machine learning algorithms to assess risk of loans based on multiple factors within a loan database.

# Results
![accuracy](https://github.com/pmercado625/Credit_Risk_Analysis/blob/main/images/Accuracy.png?raw=true)
![precision](https://github.com/pmercado625/Credit_Risk_Analysis/blob/main/images/Classification.png?raw=true)  
Listed above are the accuracy, precision, and sensitivity of the various machine learning models.
In terms of Accuracy, the highest accuracy learning models are in order as following:
1. AdaBoost Classifier
2. Balanced Random Forest Classifier  <br>
3. Combination Sampling
4. SMOTE OverSampling
5. Naive Random Oversampling
6. Cluster Centroids 
<br>
In terms of precision, the machine learning algorithms achieved very similar results with only the AdaBoost and Random Forest classifiers performing slightly better in terms of assessing high risk.  <br>  
In terms of sensitivty (recall), only one of them performed a significant amount better, with that being the AdaBoost Classifier model. Slightly behind it would be the Balanced Random Forest Model, with Combination Sampling, Naive Radom Oversampling, and SMOTE oversampling, and Cluster Centroids performing argueably the worst.

# Summary
In examining all of these models, it's clear that the Adaptive Boosting Algorithm seemed to perform the best with the test dataset that was given. Additionally, the AdaBoosting had the highest F1 score (which takes into account both recall and precision), with the Balanced Random Forest Model slightly falling behind it. Either of these two models would be the acceptable over the rest. The only point of contention would be the considerably low precision in identifying high_risk cases. Overall, there can always be additional investigations to conduct in order to assess these high risk cases that may help alleviate some of the issues seen with the two top models.
