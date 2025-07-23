# Ozone Level Prediction Project

## Project Overview
This project aims to predict ozone concentration levels (maxO3) based on various meteorological and environmental variables. The dataset contains 13 features including temperature readings at different times, cloud cover, wind components, and precipitation indicators.

## Key Features
- **Target Variable**: maxO3 (maximum ozone concentration observed during the day)
- **Predictor Variables**:
  - Temperature at 9h, 12h, 15h (T9, T12, T15)
  - Cloud cover at 9h, 12h, 15h (Ne9, Ne12, Ne15)
  - Wind components at 9h, 12h, 15h (Vx9, Vx12, Vx15)
  - Previous day's ozone level (maxO3v)
  - Wind direction at 12h (vent)
  - Precipitation occurrence (pluie)

## Project Steps
1. **Data Loading and Initial Visualization**
   - Imported and examined the dataset structure
   - Performed initial statistical analysis

2. **Exploratory Data Analysis (EDA)**
   - Cleaned and preprocessed data (handling decimal formats, dropping unnecessary columns)
   - Analyzed distributions, outliers, and correlations
   - Visualized relationships between variables

3. **Data Preprocessing**
   - Handled numerical conversions
   - Analyzed variable distributions and transformations
   - Examined correlations between variables

4. **Modeling**
   - Implemented various regression models:
     - Linear Regression
     - Ridge Regression (L2 regularization)
     - Lasso Regression
     - KNN
     - Random Forest
   - Evaluated models using MSE and R² metrics

5. **Model Optimization**
   - Used cross-validation and grid search for hyperparameter tuning
   - Selected best performing model

## Key Findings
- The target variable (maxO3) shows right-skewed distribution
- Temperature variables show strong correlation with ozone levels
- Random Forest demonstrated best performance among tested models

## Requirements
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Usage
1. Clone the repository
2. Install required packages
3. Run the Jupyter notebook `Ozone level predection.ipynb`

