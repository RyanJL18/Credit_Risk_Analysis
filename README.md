# Credit_Risk_Analysis
## Overview

The purpose of this assignment was to use Supervised Machine Learning algorithms to make predictions based on the provided data set. The data provided includes information about credit loans, leaving us to use machine learning to predict potential risky investments.

## Results

The following includes all the results for each of the 6 machine leaning modules present:

### **Naive Random Oversampling**

![Naive Random Oversampling.PNG](https://github.com/RyanJL18/Credit_Risk_Analysis/blob/main/Resources/Naive_Oversampling.png)

Balanced Accuracy: 0.6293939430565123
Recall: High/Low: .57/.68
Precision: Low for High-Risk Loans, High for Low Risk

### **SMOTE Oversampling**

![SMOTEOversampling.PNG](https://github.com/RyanJL18/Credit_Risk_Analysis/blob/main/Resources/SMOTE_Oversampling.png)

Balanced Accuracy: 0.6277008271188627
Recall: High/Low: .62/.63
Precision: Low for High Risk Loans, High for Low Risk

### **UnderSampling**

![Undersampling.PNG](https://github.com/RyanJL18/Credit_Risk_Analysis/blob/main/Resources/Undersampling.png)

Balanced Accuracy: 0.6277008271188627
Recall: High/Low: .60/.43
Precision: Low for High Risk, High for Low

### **Combination Under-Over Sampling**

![ComboOVUnsampling.PNG](https://github.com/RyanJL18/Credit_Risk_Analysis/blob/main/Resources/ComboOverUnderSampling.png)

Balanced Accuracy: 0.5138873780775228
Recall: High/Low: .70/.61
Precision: Low for High Risk Loans, High for Low Risk

### **Balanced Random Forest Classifier**

![BalancedForestClass.PNG](https://github.com/RyanJL18/Credit_Risk_Analysis/blob/main/Resources/BalancedRandomForest.png)

Balanced Accuracy: 0.7877672625306695
Recall: High/Low: .67/.91
Precision: Low for High Risk Loans, High for Low Risk

### **Easy Ensemble Classifier**
There was an error with the enviornemnt using Easy Ensemble Classifier. Could not calculate the values with this Ensemble Classifier. 

## Summary

The best maching learning model can be determined by the balanced accuracy. Balanced accuracy qorks on a scale from 0 to 1 and ut is best to have a balanced accuracy as close to 1 as possible. With the values determined from these models above, the closest to 1 was the Balanced Random Forest Classifier, however the value .78 still allows for some improvement. For whatever reason the Easy Ensemble Classifier did not work due to an attribute error (potentially with my virtual enviornment) but it has the potential to be the best fit had the balanced accuracy been higher than .78. The same sort of scale is used when measuring the recall scores as well, looking for scores as close to 1 as possible. Most scores provided have lower High-Risk scores while the Balanced Random Forest Classifier also had the highest Low-Risk score (at .91). The highest score for High-Risk models was the Combination Over-Under Sampling. Given the provided information, the best fit would be the Balanced Forest Classifier, but there is still room for the Easy Ensemble Classifier to be a better fit if the scores had been measurable.  
