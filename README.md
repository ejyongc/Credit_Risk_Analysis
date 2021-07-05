# Credit_Risk_Analysis

## Overview of the analysis:     
In this project we will be analysing credit card dataset from LendingClub to help measure credit card risk. We'll be testing six different ML methods in order to make recommendations on which method is the best at making predictions. 

## Results: 
In the first section, we resampled data utilizng three different methods (Random Oversampling, SMOTE, and Undersampling) in order to determine which one is the most accurate. Our *Balanced Accuracy Scores* were the following: 
- Naive Random Oversampling: 0.640324421824783
- SMOTE : 0.6514992150524688
- Undersampling : 0.5447046721744204
![imgage](xxx)

In addition to the tests above, we also applied a combination of our over and undersampling methods (SMOOTEENN) to determine if we have a better credit risk prediction. The results once again showed that the SMOTE oversampling method is the most accurate. 

![image](xxx)

From the results of this analysis we can identify that the *SMOTE Oversampling* method is the most accurate with a 65% accuracy score among the four resampling methods we utilized. 

In addition to the four ML methods applied above, we ran two ensemble algorithm that gave a much higher accuracy compared to the previous resampling models: 
- Balanced Random Forest Classifier: 0.7885466545953005
- Easy Ensemble AdaBoost Classifier: 0.9316600714093861

![image](xxx)

From the imbalanced classification reports we can see that the *Easy Ensemble ADABoost Classifier* has a high *acuracy* (93%), high *prediction* (94%), and *F1* (97%)

## Summary: 

From the results of the machine learning models we tested above, we can conlude that the *Easy Ensemble AdaBoost Classifier* would be the recommended ML model to predict credit risk. Unlike the other methods we tested, this method has the highest *accuracy*, *prediction*, *recall*, and *F1* scores. Although the precision on *high-risk* predictions is low, the sensitivity allows us to flag high-risk credits.  

![image](xxx)
