# Industrial_copper_modeling

## Problem statement 
- Sales and pricing data in the copper industry often exhibit skewness and noise.
Manual handling of these challenges can be time-consuming and less accurate for predicting optimal pricing decisions.
Machine Learning Regression Solutions:

- Utilizing regression models addresses data issues through techniques like normalization and outlier detection.
Advanced algorithms in regression models prove robust, offering a more efficient way to handle complex data challenges.
Lead Classification for Improved Sales:

- A lead classification model is introduced to evaluate and classify leads.
Focusing on the STATUS variable (WON as Success and LOST as Failure) streamlines lead analysis, improving efficiency in capturing potential customers

## Approach Summary:

### Data Understanding:
- Identify variable types and distributions.
- Clean 'Material_Reference' values starting with '00000' to null.
- Treat reference columns as categorical; consider excluding INDEX.
### Data Preprocessing:
-Handle missing values.
-Address outliers.
-Apply transformations for skewness in continuous variables.
-Encode categorical variables.
### Exploratory Data Analysis (EDA):
- Visualize outliers and skewness.
- Utilize feature engineering.
- Identify and drop highly correlated columns.
### Model Building and Evaluation:
- Split dataset into training and testing sets.
- Train and evaluate classification models with appropriate metrics.
- Optimize hyperparameters.
- Interpret results and assess model performance.
### Model GUI with Streamlit:
- Use Streamlit module to create an interactive page.
- Include task input (Regression or Classification).
- Add input fields for each column (excluding 'Selling_Price' for regression and 'Status' for classification).
- Apply feature engineering, scaling, and transformations used in training to predict and display output.

