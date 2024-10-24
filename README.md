### Project Overview
Early detection of type 2 diabetes is vital for preventing complications and managing the disease effectively. In this project, we apply and compare three different machine learning models to predict the risk of type 2 diabetes based on patient diagnostic data. The models evaluated are:
- Naive Bayes Classifier
- Logistic Regression
- Multi-Layer Neural Network (MLNN)
  
Our goal is to identify the model that provides the highest performance in terms of accuracy, precision, recall, and overall reliability for predicting type 2 diabetes. The results will help guide future selection of machine learning models in similar medical diagnostics and binary classification tasks.

### Machine Learning Models
#### 1. Naive Bayes Classifier - The Naive Bayes Classifier is a probabilistic model based on the Bayes Theorem. It assumes independence between the predictors. While simple, this model often performs well in medical diagnostics.

#### Accuracy: 92.31%
#### Confusion Matrix:
- True Negatives: 61
- False Positives: 5
- False Negatives: 1
- True Positives: 11
#### 2. Logistic Regression
Logistic Regression is a widely used model for binary classification tasks. It estimates the probability that an instance belongs to a certain class (in this case, diabetic or non-diabetic).

#### Accuracy: 91.03%
#### Confusion Matrix:
- True Negatives: 64
- False Positives: 2
- False Negatives: 5
- True Positives: 7
#### 3. Multi-Layer Neural Network (MLNN)
The MLNN is a more complex model with multiple layers of neurons that learn to identify patterns in the data through backpropagation. It can handle more complex data relationships but requires more computational power.

#### Accuracy: 92.31%
#### Confusion Matrix:
- True Negatives: 63
- False Positives: 3
- False Negatives: 3
- True Positives: 9
### Results & Evaluation
- We compared the models based on accuracy, precision, recall, and confusion matrices. All models achieved similar accuracy, but there are differences in their ability to correctly identify diabetic patients (True Positives) and non-diabetic patients (True Negatives).

- Naive Bayes Classifier and MLNN showed the highest accuracy at 92.31%, while Logistic Regression achieved slightly lower accuracy at 91.03%.
The confusion matrices reveal that each model has varying strengths in detecting positives and negatives.
