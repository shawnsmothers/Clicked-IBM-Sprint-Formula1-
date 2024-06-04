# Clicked-IBM-Sprint-Formula1-
EDA, Feature Engineering focused on grid and result position  

Here is the detailed description formatted for a README file:

# Formula 1 Data Analysis Project

## Overview
This project analyzes the Formula 1 World Championship dataset to predict driver positions based on various features. The main goal is to understand the influence of the starting grid position on the final race position.

## Data Preprocessing
1. **Handling Missing and Duplicate Data:**
   - Checked for and handled null values and duplicates in the dataset.

2. **Feature Engineering:**
   - Transformed data to fit into a regression model.
   - Converted relevant columns (`points`, `milliseconds`, `position`) into float type.
   - Removed newline characters (`\n`) and used the mean of valid entries to fill in null values.

## Hypothesis
- Investigated whether the starting grid position influences the final race position.
- Aimed to determine if a better grid position results in a more favorable finish (e.g., positions 1-3).

## Modeling
- **Target Variable:** `position`
- **Features:** `grid`, `finished_lap`, `points`
- Applied two machine learning models:
  - Regression analysis
  - Random forest

## Results
- The models performed moderately well.
- Accurately predicted lower positions (closer to the front of the grid).
- Struggled to accurately predict higher positions (farther back on the grid).

## Conclusion
While the models demonstrated some predictive power, especially for drivers starting in lower positions, there is room for improvement in predicting outcomes for those 
starting farther back. Further refinement of features and modeling techniques could enhance prediction accuracy.


