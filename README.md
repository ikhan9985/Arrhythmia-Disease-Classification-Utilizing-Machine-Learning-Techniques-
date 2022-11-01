# Arrhythmia-Disease-Classification-Utilizing-Machine-Learning-Techniques-
Arrhythmia Disease Classification Utilizing Machine Learning Techniques 

## Justification of choosing the classification algorithms: 
- SVM is useful when most of the predictors are numerical. So, in the arrythmia data contains numeric data from 1 – 16. That’s why we choose Support Vector Machine. 
- KNN Its purpose is to use a database in which the data points are separated into several classes (in our case it is) to predict the classification. 
- Logistic Regression is most commonly used when the data in question has binary output, so when it belongs to one class or another, or is either a 0 or 1. But arrythmia contains 16 classes in its label or out. So, logistic regression deals it one by one. It’s works like:  If we do for class-1 then it takes class one as one category and other 15 class as second category. If we do for class-2 then it takes class-2 as one category and other 15 as second group. Logistic regression does it for all classes one by one. 
 
## Scientific Rationale of Hyper Parameters: 
- We use GridSearchCV() class that automatically get best hyperparameter for accuracy. We use this class by importing: 
"from sklearn.model_selection import GridSearchCV" 
- We implement this library’s class on arrythmia data set, once for SVM and KNN. There is no need of using GridSearchCV in logistic regression, because we know it’s only treats with two classes and it already gives 97.8% of accuracy. 
