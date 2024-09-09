# Coffee Sales Analysis

## Overview
This project analyzes coffee sales data and builds a machine learning model to predict sales. The main focus is to preprocess the data, train a `RandomForestRegressor` model, and evaluate its performance. The project demonstrates how to handle both categorical and numerical data using pipelines and advanced scikit-learn techniques.

## Table of Contents
1. [Installation](#installation)
2. [Project Structure](#project-structure)
3. [Data Preprocessing](#data-preprocessing)
4. [Modeling](#modeling)
5. [Evaluation](#evaluation)
6. [Results](#results)
7. [Conclusion](#conclusion)

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your-repository.git
   ```

2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
   
## Project Structure
- Coffee_Sales_analysis.ipynb: Jupyter notebook containing all analysis, preprocessing steps, model training, and evaluation.
- data/: Folder containing the dataset (if available).
- README.md: Documentation of the project.


## Data Preprocessing
- The data is split into numerical and categorical features:
- Numerical Features: These features are scaled using StandardScaler.
- Categorical Features: These features are encoded using OneHotEncoder.
- A ColumnTransformer is used to apply the transformations in a streamlined manner.



## Modeling

The model used for prediction is RandomForestRegressor, a robust ensemble method in scikit-learn. It is trained on the preprocessed training dataset.



## Evaluation
- The model is evaluated using the following metrics:
- Mean Absolute Error (MAE): Measures the average magnitude of errors in a set of predictions.
- Mean Squared Error (MSE): Similar to MAE but gives more weight to large errors.
- R-Squared (R²): Indicates how well the model captures the variance in the data. A score close to 1 indicates an excellent fit.
- The results from the evaluation:


MAE: 2.33e-05
MSE: 9.97e-06
R²: 0.999999



## Results
The RandomForestRegressor model shows an outstanding performance with an R² score very close to 1, indicating that the model is nearly perfect in capturing the variance in the data.



## Conclusion
This project demonstrates how to preprocess a dataset containing both categorical and numerical data, build a robust machine learning model, and evaluate its performance. The RandomForestRegressor model is highly effective for predicting coffee sales with excellent results.



