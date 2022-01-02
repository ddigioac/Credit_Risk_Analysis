# Amazon Vine Analysis

## Overview of the Credit Risk Analysis

### Purpose

In this analysis I will be employing different techniques to train and evaluate models. Once complete, I will evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.


## Credit Risk Analysis Results

1. Naive Random Oversampling

- Balanced Accuracy Test: 65.47%
- Precision Score: 
- Recall Score: 

Imbalanced Classification Report: 
![This is an image](https://github.com/ddigioac/Credit_Risk_Analysis/blob/a0fa26b0ebd0033e6f2fc1a87a3fba099852c9ae/Images/%231%20-%20Naive%20Random%20Oversampling%20.png) 

2. SMOTE Oversampling

- Balanced Accuracy Test: 66.27%
- Precision Score: 
- Recall Score: 

Imbalanced Classification Report: 
![This is an image](https://github.com/ddigioac/Credit_Risk_Analysis/blob/a0fa26b0ebd0033e6f2fc1a87a3fba099852c9ae/Images/%232%20-%20SMOTE%20Oversampling.png) 

3. Undersampling

- Balanced Accuracy Test: 66.20%
- Precision Score: 
- Recall Score: 

Imbalanced Classification Report: 
![This is an image](https://github.com/ddigioac/Credit_Risk_Analysis/blob/a0fa26b0ebd0033e6f2fc1a87a3fba099852c9ae/Images/%233%20-%20Undersampling.png) 

4. Combination (Over and Under) Sampling

- Balanced Accuracy Test: 54.47%
- Precision Score: 
- Recall Score: 

Imbalanced Classification Report: 
![This is an image](https://github.com/ddigioac/Credit_Risk_Analysis/blob/a0fa26b0ebd0033e6f2fc1a87a3fba099852c9ae/Images/%234%20-%20Combination%20(Over%20and%20Under)%20Sampling.png) 

5. Balanced Random Forest Classifier

- Balanced Accuracy Test: 77.28%
- Precision Score: 
- Recall Score: 

Imbalanced Classification Report: 
![This is an image](https://github.com/ddigioac/Credit_Risk_Analysis/blob/a0fa26b0ebd0033e6f2fc1a87a3fba099852c9ae/Images/%235%20-%20Balanced%20Random%20Forest%20Classifier.png) 

6. Easy Ensemble AdaBoost Classifier

- Balanced Accuracy Test: 93.16%
- Precision Score: 
- Recall Score: 

Imbalanced Classification Report: 
![This is an image](https://github.com/ddigioac/Credit_Risk_Analysis/blob/a0fa26b0ebd0033e6f2fc1a87a3fba099852c9ae/Images/%236%20-%20Easy%20Ensemble%20AdaBoost%20Classifier.png) 


## Credit Risk Summary
After employing the different techniques to train and evaluate the models, Combination Sampling scored the lowest on the Balanced Accuracy Test. In conclusion, one can observe that the Easy Ensemble AdaBoost Classifier model produced the highest recall percentage along with the highest balanced accuracy score and therefore is the best model for the credit risk analysis. 
