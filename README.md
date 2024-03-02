## Problem Statement
The objective of this project is to develop a machine learning model that can accurately predict whether a person has heart disease based on various demographic and health-related features. 

## Data Dictionary
-Age: Age of the patient (numerical).
-Sex: Gender of the patient (binary: 1 = male, 0 = female).
-Chest pain type: Type of chest pain experienced by the patient (categorical: 1 = typical angina, 2 = atypical angina, 3 = non-anginal pain, 4 = asymptomatic).
-BP: Resting blood pressure (numerical).
-Cholesterol: Serum cholesterol level in mg/dl (numerical).
-FBS over 120: Fasting blood sugar level greater than 120 mg/dl (binary: 1 = true, 0 = false).
-EKG results: Electrocardiogram results (categorical: 0 = normal, 1 = having ST-T wave abnormality, 2 = showing probable or definite left ventricular hypertrophy).
-Max HR: Maximum heart rate achieved (numerical).
-Exercise angina: Exercise-induced angina (binary: 1 = yes, 0 = no).
-ST depression: ST depression induced by exercise relative to rest (numerical).
-Slope of ST: Slope of the peak exercise ST segment (categorical: 1 = upsloping, 2 = flat, 3 = downsloping).
-Number of vessels fluro: Number of major vessels (0-3) colored by fluoroscopy (numerical).
-Thallium: Thallium stress test result (categorical: 3 = normal, 6 = fixed defect, 7 = reversible defect).
-Heart Disease: Presence or absence of heart disease (binary: 'Presence' = heart disease present, 'Absence' = heart disease absent).

### Preprocessing done on the data
Raw data is being scaled using sklearn's StandardScaler() scaler

### Models Used for this task
1. Logistic Regression (90.70% accuracy)
2. Support Vector Classifier (88.88% accuracy)
3. Random Forest Classifier (85.18% accuracy)
