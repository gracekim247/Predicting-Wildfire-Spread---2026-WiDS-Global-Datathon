# Predicting Wildfire Spread - 2026 WiDS Global Datathon

## Overview
This repository contains the machine learning pipeline developed for the 2026 Women in Data Science (WiDS) Global Datathon. As an AI Fellow in the Break Through Tech program at Cornell Tech, I collaborated with a team to build a predictive classification model forecasting the spread of wildfires. 

Our model predicts the probability of a wildfire hitting specific spatial perimeters within 12, 24, 48, and 72-hour windows.

## Results
* **Final AUC Score:** 0.90823

## Tools & Technologies
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-Learn, Seaborn, Matplotlib, XGBoost
* **Environment:** Jupyter Notebook / Google Colab

## Methodology
Our approach involved a full end-to-end machine learning pipeline:
1. **Exploratory Data Analysis (EDA):** Analyzed 37 distinct spatial and temporal features. Utilized Seaborn correlation heatmaps to identify key variables impacting fire growth, such as cross-track components and alignment.
2. **Data Preprocessing:** Cleaned raw geospatial data, handled missing values through imputation, and applied one-hot encoding to categorical variables to prepare the dataset for training.
3. **Modeling:** Trained a gradient-boosted decision tree using XGBoost. Optimized model performance by fine-tuning hyperparameters (including learning rate, tree depth, and subsampling) to maximize the Area Under the Curve (AUC) evaluation metric while managing class imbalances and preventing overfitting.

## Repository Structure
* `final.ipynb`: The main Jupyter Notebook containing the data exploration, preprocessing, and model training code.
* `requirements.txt`: The list of required Python packages needed to run the notebook.
