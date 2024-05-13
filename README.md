# JSON-parsed-automated-ML-modelling
JSON parsed automated Machine learning modelling with best evaluation methods and algorithm for classification and regression problems .

## Overview 
This Notebook invites to leverage Machine Learning techniques to develop a model that predicts the score or evaluation based on parsed JSON file from automating pre processing, EDA, model selection, Hyper Parameter selection , evaluation method etc. based on input from Json File. Model will contribute to a user-friendly system that empowers individuals to make informed decisions about the problem.
The Problem statement is based on problem devised from Hackathon at Imarticus Learning.

### Goal:
Develop an ML model that predicts the Scores and Evaluation of Data based on the provided data.

### JSON Parsing
As input file for JSON parsing is of **Rich Text Format**, firstly RTF file is converted to JSON file.

### Data Extraction and Model Training
Data is extracted from Input file into Pandas DataFrame for Train and test, extracting Numerical and categorical columns, selecting columns for model training, missing value imputing method, Data Scaling, categorical columns encoding, model training, hyper parameter tuning using GridSearchCV and model evaluation.
