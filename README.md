[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NikhilGaba49/AccidentSeverityPrediction_Victoria/blob/main/Code.ipynb)

# Accident Severity Prediction in Victoria
Predict the severity of road accidents in Victoria using historic crash data. 

# Project Overview
We explore how predictive some factors of road accidents are on accident severity, including seatbelt usage, age, road and atmospheric conditions and more.

# Data Sources
- Victorian road crash data, available at: https://discover.data.vic.gov.au/dataset/victoria-road-crash-data
  Specifically, the following datasets:
  - Accident
  - Atmospheric Condition
  - Person
  - Node
  - Road Surface Condition
- Filtered Vehicle Dataset (available from files)

# Project Steps
1. Extract the useful features from the various datasets, and proceed to preprocess the data (encoding, imputation, etc.)
2. Train-test split to train our model
3. Correlation methods to investigate strong associations of chosen features with accident severity and feature selection
4. Run supervised learning models including Decision Tree Classifiers and k-Nearest Neighbour
5. Evaluate the predictive power of the chosen features to predict accident severity
6. Analyse limitations and potential improvements to the investigation.

# Results

| Model                    | Accuracy | F1-Score | 
|--------------------------|----------|----------|
| Decision Tree Classifier |  63.2%   |   49.0%  |
| k-Nearest Neighbours     |  62.5%   |   51.9%  |
