# MonkeyPox-Detection

An ongoing outbreak of monkeypox, a viral disease, was confirmed in May 2022. The initial cluster of cases was found in the United Kingdom, where the first case was detected in London on 6 May 2022 in a patient with a recent travel history from Nigeria.

## About the Dataset

This is a SYNTHETIC dataset generated based on a study published by thebmj: Clinical features and novel presentations of human monkeypox in a central London centre during the 2022 outbreak: descriptive case series.

Dataset consists of a CSV which have a record of 25,000 Patients with their corresponding features and a target variable indicating if the patient has monkeypox or not.

Features: Patient_ID, Systemic Illness, Rectal Pain, Sore Throat, Penile Oedema, Oral Lesions, Solitary Lesion, Swollen Tonsils, HIV Infection, and Sexually Transmitted Infection

Target Variable: MonkeyPox

The dataset currently contains boolean and categorical features and in future, more data and features might be added.


## Algorithms
- KNeighbors Classifier
- Logistic Regression 
- Decision Tree Classifier
- RandomForest Classifier
- Gaussian Naive Bayes
- XGBoost Classifier
- Bagging Classifier
