# Credit_Risk_Analysis

## Overview:
In this project, machine learning was used to employ techniques to train and evaluate models to determine the performance of the provided credit card dataset. Jupyter Notebook’s **imbalanced-learn** and **scikit-learn** libraries were used to build and evaluate the models.


## Results:


**Table of Model’s Scores**

![ScreenShot](https://github.com/dmyrick/Credit_Risk_Analysis/blob/main/Image/ML_table.png)

*The table is supported by the data below.*

**Naive Random Oversampling**

![ScreenShot](https://github.com/dmyrick/Credit_Risk_Analysis/blob/main/Image/T1.png)

**SMOTE Oversampling**

![ScreenShot](https://github.com/dmyrick/Credit_Risk_Analysis/blob/main/Image/T2.png)

**Cluster Centroids Undersampling**

![ScreenShot](https://github.com/dmyrick/Credit_Risk_Analysis/blob/main/Image/T3.png)

**SMOTEENN Combination**

![ScreenShot](https://github.com/dmyrick/Credit_Risk_Analysis/blob/main/Image/T4.png)

**Balanced Random Forest Classifier**

![ScreenShot](https://github.com/dmyrick/Credit_Risk_Analysis/blob/main/Image/T5.png)

**Easy Ensemble AdaBoost Classifier**

![ScreenShot](https://github.com/dmyrick/Credit_Risk_Analysis/blob/main/Image/T6.png)



## Summary:
1.	The credit risk resampling analysis used the first four models to test the credit card dataset. The **Naive Random Oversampling** had an accuracy score of 0.72 and was the highest score of the model tested. The Naive Random Oversampling **would be the recommended model to use** over the SMOTE Oversampling, Cluster Centroids Undersampling, or SMOTEENN Combination.
2.	The credit risk ensemble analysis used the Balanced Random Forest Classifier and the Easy Ensemble AdaBoost Classifier to test the predictions of low-risk and high-risk credit applications. The **Easy Ensemble AdaBoost Classifier** had an accuracy score of 0.93. This model was able to predict the credit applications’ risk accurately. The Easy Ensemble AdaBoost Classifier **would be the recommended model to use**.
