# Insurance Data Analysis

This project provides an exploratory data analysis of an insurance dataset using Python. The analysis includes data manipulation, cleaning, and visualization to uncover insights and patterns in the data.

# Libraries Used
- **Pandas**: efficient data analysis and manipulation.
- **NumPy**: performing mathematical operations.
- **Matplotlib.pyplot & Seaborn**: data visualization through various charts, enhancing the understanding of data relationships.
- **Scikit-learn (sklearn)**: building predictive models, including preprocessing, model selection, and evaluation.
- **Plotly**: for interactive plotting and visualization
- **Xgboost**: for gradient boosting algorithms
- **Warnings**: for managing warning messages

## Dataset

Use the dataset 
- Dataset of charges and characteristics of insured persons (`insurance.csv`)

## Features

- Data Loading and Preprocessing: Cleansing the dataset by removing unnecessary columns and converting data types
- Data Visualization: Creation of graphs comparing the characteristics of insured persons with the value of insurance 
- Correlation Analysis: Identifying the strength of relationships between variables.
- Predictive Modeling: Developing models using GridSearchCV, XGBRegressor

## Predictive Models

The code implements a robust method to train, tune, and evaluate an XGBoost regression model. By using a pipeline, it ensures that preprocessing and modeling steps are applied consistently, and GridSearchCV automates the process of finding the best hyperparameters for the model. Finally, the model's performance is evaluated on unseen data using various error metrics to assess its accuracy.
