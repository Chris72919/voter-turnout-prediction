# Voter Turnout Prediction

This project analyzes U.S. county-level voter turnout using socioeconomic, political, and regional variables to evaluate factors associated with turnout and compare predictive modeling approaches. Beta regression and random forest models were developed and evaluated using train/test performance results. 

## Dataset
County-level socioeconomic and voting data sourced from Kaggle:
https://www.kaggle.com/datasets/adamcuculich/county-socioeconomic-education-and-voting-data

## Methods
- Beta Regression
- Random Forest Regression
- Train/Test Split Evaluation
- Model Diagnostics
- Variable Importance Analysis

## Features Used
- Unemployment Rate
- Median Household Income
- Income Percentile
- Bachelor's Degree Percentage
- Political Affiliation
- Census Region
- Urban Influence Classification

## Results
- Random forest achieved the strongest predictive performance with a test R² of approximately 0.31.
- Beta regression provided interpretable relationships between socioeconomic variables and turnout.
- Education level, political affiliation, and regional differences were among the strongest predictors.

## Tools
- R
- dplyr
- ggplot2
- caret
- randomForest
- betareg

## Files
- `voter_turnout_prediction.Rmd` — main analysis and modeling workflow
- `Data/` — datasets used in the analysis
