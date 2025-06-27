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
2. Train-test split to train our model and 


Victorian road crash data, by first preprocessing the chosen features, using correlation methods to investigate 
strong associations with accident severity and finally, evaluate the predictive power of the chosen features to predict
accident severity based off the historical accident data. The discussion of the methods chosen and limitations to the 
analysis is included in the project report.

To execute the code for operations and visualisations, please follow the steps:
1. Download the following datasets from "https://discover.data.vic.gov.au/dataset/victoria-road-crash-data":
2. Download the "filtered_vehicle.csv" from the zip file.
3. Upload all the .csv files to a folder in google drive named "a2-datasets"
4. Also upload the "EoDP_A2.ipynb" to a folder in google drive, 
named "Colab Notebooks".
5. Since the datasets and the code is now in google drive, the code can be executed by opening the notebook in Google Colaboratory, either manually from Google Drive or using "Open Colab" from Colab
6. Execute using Runtime -> Run all 
