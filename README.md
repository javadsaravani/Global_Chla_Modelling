# Chl-a Modelling Tool

This repository contains a specialized tool developed for modeling chlorophyll-a (Chl-a) concentrations using total phosphorus (TP) and total nitrogen (TN) as input variables. The tool provides a user-friendly and efficient platform for predicting Chl-a levels based on these key nutrient drivers.

## Features

- **Dataset Selection**: Choose from four dataset types based on lake depth:
  - Shallow
  - Transitional
  - Deep
  - Combined dataset (aggregates records across all lake types regardless of depth)

- **Model Selection**: Select from seven advanced machine learning and deep learning models for Chl-a prediction:
  - Random Forest (RF)
  - XGBoost
  - Support Vector Regression (SVR)
  - Artificial Neural Networks (ANN)
  - Long Short-Term Memory networks (LSTM)
  - Bayesian Hierarchical Linear Regression (BHLR)
  - Kolmogorov-Arnold Network (KAN)

- **Visual and Quantitative Feedback**: After modeling, the tool provides:
  - A scatter plot of predicted vs. measured Chl-a values
  - Key performance metrics:
    - Pearson correlation coefficient (R)
    - Root mean squared error (RMSE)
    - Mean absolute error (MAE)

## User Interface and Workflow

1. **Main Page**: A brief description of the tool is presented upon opening.

   ![Main Page](images/main_page.png)  
   *Figure S1. The main page of the tool.*

2. **Dataset Selection**: Choose the desired dataset based on lake depth.

   ![Dataset Selection](images/dataset_selection.png)  
   *Figure S2. Dataset selection.*

3. **Model Selection**: Select the model you wish to use for Chl-a modeling.

   ![Model Selection](images/model_selection.png)  
   *Figure S3. Model selection.*

4. **Results Page**: View the scatter plot of predicted vs. measured Chl-a values and the performance metrics.

   ![Results Page](images/results_page.png)  
   *Figure S4. Modeling results page along with the performance metrics.*

## Installation

To run the tool, ensure you have the following libraries installed:

```bash
pip install tkinter Pillow pandas numpy matplotlib scikit-learn tensorflow KAN statsmodels torch pymc seaborn
