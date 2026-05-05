# Voter Turnout Prediction

This project analyzes U.S. county-level voter turnout using socioeconomic and regional variables. Multiple statistical and machine learning models were developed to evaluate predictive performance and identify key turnout predictors.

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
