# Heart Disease Analysis Project

## Overview
This project analyzes a heart disease dataset to identify patterns and prepare the data for predictive modeling. The analysis includes exploratory data analysis (EDA) and feature engineering to enhance the dataset for machine learning applications.

## Dataset
The dataset contains medical information about patients, including:
- Demographic data (age, sex)
- Clinical measurements (blood pressure, cholesterol, etc.)
- Test results (ECG, thalassemia, etc.)
- Target variable indicating presence of heart disease

## Key Findings from EDA
1. The dataset contains information about patients with and without heart disease
2. No missing values were found in the dataset
3. Several features show strong correlation with the target variable
4. Chest pain type (cp) shows clear patterns with respect to heart disease diagnosis
5. Heart disease prevalence varies across different age groups

## Feature Engineering Process
The following steps were taken to prepare the data for modeling:

1. **Outlier Handling**: Identified and capped outliers in numerical features
2. **Feature Transformation**: Applied log transformation to skewed features
3. **Feature Scaling**: Standardized numerical features
4. **Feature Creation**: Created new features based on domain knowledge:
   - Age groups
   - Blood pressure categories
   - Cholesterol categories
   - Heart rate reserve
   - Combined chest pain and angina feature
5. **One-Hot Encoding**: Encoded categorical features
6. **Feature Selection**: Selected the most important features using statistical tests

## Files
- `heart.csv`: Original dataset
- `heart_analysis.ipynb`: Jupyter notebook containing the analysis
- `heart_processed.csv`: Processed dataset ready for modeling

## Usage
1. Review the analysis in `heart_analysis.ipynb`
2. Use the processed dataset `heart_processed.csv` for model development
3. Apply insights from the EDA to inform model selection and feature importance

## Requirements
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Future Work
- Develop predictive models using the processed dataset
- Evaluate different algorithms for heart disease prediction
- Perform hyperparameter tuning to optimize model performance
- Create visualizations for model interpretation
