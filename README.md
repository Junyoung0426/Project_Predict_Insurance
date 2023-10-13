# Insurance Premium Prediction Project


This project aims to predict insurance premiums using machine learning techniques in a Jupyter Notebook. The dataset contains features such as age, sex, BMI, number of children, smoking status, region, and insurance charges.

## Table of Contents
1. [Dataset](#dataset)
2. [Data Preprocessing](#data-preprocessing)
3. [Exploratory Data Analysis (EDA)](#eda)
4. [Model Selection](#model-selection)
5. [Model Performance](#model-performance)
6. [Usage](#usage)
7. [License](#license)
8. [Contact](#contact)

## Dataset - https://www.kaggle.com/datasets/simranjain17/insurance/code
- **age**: Age of the insured (int)   
- **sex**: Gender of the insured (object)
- **bmi**: Body Mass Index (BMI) of the insured (float)
- **children**: Number of children/dependents covered by the insurance (int)
- **smoker**: Smoking status (1 for smokers, 0 for non-smokers) (object)
- **region**: Region of residence (object)
- **charges**: Insurance charges (float)

## Data Preprocessing
- Remove dupliacted data
- Handled missing data (if any).
- Encoded categorical variables using one-hot encoding and label encoding.
- Scaled numerical features.

## Exploratory Data Analysis (EDA)
- Explored the dataset through various visualizations and summary statistics.
- Identified correlations and patterns in the data.
- Show the plot showing the relationshipg among columns.

## Model Selection
- Trained multiple regression models:
  - Linear Regression
  - Polynomial Regression
  - Support Vector Regression
  - Random Forest
  - Decision Tree
  - XGBoost
  - LightGBM
  - Gradient Boosting Regression
- Evaluated models based on performance metrics.

## Model Performance
- Calculated R-squared (coefficient of determination) and Mean Squared Error (MSE) for each model.
- Selected the model with the best performance after hyper parameter

## Usage
1. Clone this repository:
git clone https:/ https://github.com/Junyoung0426/Predict_Insurance.git
2. Open the Jupyter Notebook:
jupyter notebook insurance_prediction.ipynb
3. Run the notebook to preprocess data, perform EDA, train models, and make predictions.
