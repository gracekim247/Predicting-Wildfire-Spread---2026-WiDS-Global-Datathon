# Predicting Wildfire Spread - 2026 WiDS Global Datathon

## Overview
This repository contains the machine learning pipeline developed by my team for the 2026 Women in Data Science (WiDS) Datathon. We built a predictive model to forecast the spread of wildfires, predicting the probability of a fire hitting a specific perimeter within 12, 24, 48, and 72-hour windows.

## Results
- Achieved a final AUC score of **0.90823**.

## Tools & Technologies
- **Language**: Python
- **Libraries**: Pandas, NumPy, Scikit-Learn, Seaborn, XGBoost

## Methodology

1. **Exploratory Data Analysis**: Analyzed 37 spatial and temporal features using Seaborn to identify correlations and key variables impacting fire growth.

2. **Data Preprocessing**: Handled missing values, encoded categorical variables, and prepared geospatial data for modeling.

3. **Modeling**: Trained and optimized an XGBoost classification model, tuning hyperparameters (tree depth, learning rate) to maximize AUC and handle class imbalances.

## Acknowledgments
This project was completed collaboratively with my team as part of the Break Through Tech AI Fellowship.
