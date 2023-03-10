# Classification for Heart Failure
### Problem Statement
The mission of this machine learning classification was to determine whether a patient would have heart failure, given their blood pressure, cholesterol level, chest pain, age, and several other attributes.

### Data Import and Wrangling
The data was retrieved from the Statlog (Heart) Data Set from the UC Machine Learning Repository. Data transformation was performed to make all data values numerical.

### Methodology
I built a machine learning classifier to predict if an individual would have heart failure based on specific medical information. The classifier used XGBoost, GridSearchCV, and Kfold together for the highest efficacy, while a second Keras model was also implemented.

### Algorithms Used
 - Kfold, GridSearchCV, XGBoostClassifier, Keras
 - Classified heart failure occurrence and no heart failure occurrence into numeric values of 1 and 0 respectively

### Accuracy
XGBoost Model - 93.7%
