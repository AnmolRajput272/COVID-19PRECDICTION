Name - Anmol Rajput , 
College - Lovely Professional University , 
Project Name - Covid-19 Prediction Using Machine Learning

## Model Predictors and Exact Variable Names (True = 1, False = 0)
* **Age over 60** - Age_60
* **Sex** - Male (Male=1, Female=0)
* **Cough** - Cough
* **Shortness of breath** - Shortness_of_breath
* **Fever** - Fever
* **Sore throat** - Sore_throat
* **Headache** - Headache
* **Contact with a confirmed individual** - Contact_with_confirmed



## Model Outcome
The probability of being diagnosed with a COVID-19 infection.


## Use
1. Import lgbm_model_*.txt using LightGBM 2.3.1 on Python 3.6.

2. Predict using your data.

## Files in this repository

* **lgbm_model_all_features.txt** - The predictor that uses all 8 features
* **lgbm_model_balanced_features.txt** - The predictor that uses only balanced symptoms
* **hyperparameters.txt** - The hyperparameters used by lightGBM
* **data/corona_tested_individuals_ver_0083.english.csv.zip** - The tested individuals dataset downloaded from https://data.gov.il/dataset/covid-19 on November 15, 2020 and translated into English
* **data/corona_tested_individuals_ver_006.english.csv.zip** - The tested individuals dataset downloaded from https://data.gov.il/dataset/covid-19 on May 4, 2020 and translated into English. This is the version we used for the analysis.

