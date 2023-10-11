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

## Dataset
- **age**: Age of the insured
- **sex**: Gender of the insured
- **bmi**: Body Mass Index (BMI) of the insured
- **children**: Number of children/dependents covered by the insurance
- **smoker**: Smoking status (1 for smokers, 0 for non-smokers)
- **region**: Region of residence
- **charges**: Insurance charges

## Data Preprocessing
- Handled missing data (if any).
- Encoded categorical variables using one-hot encoding.
- Scaled numerical features.

## Exploratory Data Analysis (EDA)
- Explored the dataset through various visualizations and summary statistics.
- Identified correlations and patterns in the data.

## Model Selection
- Trained multiple regression models:
  - Linear Regression
  - Polynomial Regression
  - Random Forest
  - Decision Tree
  - XGBoost
  - LightGBM
  - Gradient Boosting Regression
- Evaluated models based on performance metrics.

## Model Performance
- Calculated R-squared (coefficient of determination) and Mean Squared Error (MSE) for each model.
- Selected the model with the best performance.

## Usage
1. Clone this repository:
