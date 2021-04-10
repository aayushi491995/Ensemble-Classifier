# Ensemble-Classifier
Ensemble Classifier Modeling  - Ensemble method for preparing models

### Objective
The objective is to predict wheather a person will suffer from a heart disease based on previous medical history.


This project is meant to explore, analyse, visualize and predict hosue prices of california using below feature and target variables:
    1. age
    2. sex
    3. cp
    4. trestbps
    5. chol
    6. fbs
    7. restecg
    8. thalach
    9. exang
    10. oldpeak
    11. slope
    12. ca
    13. thal
    14. target    - Binary output 0 (the person doesnot suffer from hear disease), 1 (the person suffer from hear disease)

### Machine Learning Steps Follwed to acheve the objective.

    1. Import necessary Libraries
    2. Read the csv dataset
    3. Check for the null values and the unwanted values in the dataset
         - We checked for the null values but there are no null and unwanted values present in the dataset.
    4. Performed RandomForest on the dataset.
    5. Prediction of Train data
         - We got the accuracy of  - 0.791208
    6. Perform Hyperparameter tuninng and following are the best params:
         - 'max_depth': 3
         - 'max_features': 1
    7. Accuracy of Test data post hyper parameter tuning is - 0.81318
