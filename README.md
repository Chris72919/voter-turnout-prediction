# Voter Turnout Prediction

This project analyzes U.S. county-level voter turnout using socioeconomic, political, and regional variables to evaluate factors associated with turnout and compare predictive modeling approaches. Beta regression and random forest models were developed and evaluated using train/test performance metrics.

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
- Random forest achieved the strongest predictive performance with a test R² of approximately 0.31 and RMSE of approximately 12.8 percentage points.
- Beta regression achieved a test R² of approximately 0.19 while providing interpretable relationships between socioeconomic variables and turnout.
- Education level, political affiliation, and regional differences were among the strongest predictors.

## Key Insights
- Higher bachelor’s degree attainment was associated with higher voter turnout.
- Political affiliation and regional indicators were among the strongest predictors in both regression and random forest models.
- Counties in the South tended to show lower expected turnout relative to the reference region.
- Random forest achieved stronger predictive performance, while beta regression provided more interpretable relationships between variables and turnout.

## Visuals
### Beta Regression: Predicted vs Actual
Predicted versus actual turnout values for the beta regression model on the test dataset. Points closer to the red reference line indicate more accurate predictions.
<img width="711" height="516" alt="image" src="https://github.com/user-attachments/assets/0024c16e-9374-4af3-8947-3cda88d59a05" />

### Random Forest Variable Importance
The random forest model identified education level, political affiliation, unemployment rate, and regional indicators as important turnout predictors.
<img width="1270" height="887" alt="image" src="https://github.com/user-attachments/assets/915dd660-f027-4452-b2fd-047fc0d78ab6" />

## Future Improvements
- Explore interaction effects and nonlinear modeling approaches
- Evaluate additional ensemble methods
- Incorporate demographic and historical voting trend variables

## Tools
Analysis and modeling were completed entirely in R using statistical and machine learning libraries.
- R
- dplyr
- ggplot2
- caret
- randomForest
- betareg

## Files
- `voter_turnout_prediction.Rmd` — main analysis and modeling workflow
- `Data/` — datasets used in the analysis
