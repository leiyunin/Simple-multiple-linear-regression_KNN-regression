# Simple-multiple-linear-regression_KNN-regression

# Overview
This project analyzes the Combined Cycle Power Plant dataset, capturing the relationship between ambient variables and the net hourly electrical energy output over six years, focusing on predictive modeling and statistical analysis:

- **Data Acquisition**:
  - Downloads data from the UCI Machine Learning Repository, featuring variables like Temperature (T), Ambient Pressure (AP), Relative Humidity (RH), and Exhaust Vacuum (V).

- **Data Exploration**:
  - Investigates dataset dimensions, representations, and distributions.
  - Generates pairwise scatterplots to examine relationships between all variables.
  - Calculates descriptive statistics including mean, median, range, quartiles, and interquartile ranges, summarizing findings in a table.

- **Predictive Modeling**:
  - **Simple Linear Regression**: Applies models for each predictor to assess the relationship with the electrical output, identifying statistically significant associations and potential outliers.
  - **Multiple Regression Analysis**: Constructs a model using all predictors, evaluates significance of associations, and compares simple versus multiple regression outcomes through visual and statistical analysis.
  - **Nonlinear Associations and Interactions**:
    - Explores nonlinear relationships by fitting models with polynomial terms for each predictor.
    - Investigates predictor interactions and their impact on the response, incorporating pairwise interaction terms in a full linear regression model.
    - Enhances model performance by including interaction terms and quadratic nonlinearities, selecting significant predictors based on p-values.

- **KNN Regression**:
  - Implements k-nearest neighbor regression with both normalized and raw features, identifying optimal k values through error analysis and plotting train/test errors against 1/k.

- **Comparative Analysis and Model Improvement**:
  - Compares KNN Regression results with the most accurate linear regression model, discussing test errors and model efficacy.
  - Aims to improve predictive accuracy through model refinement, including potential interaction terms or nonlinear associations, and validates models using a train-test split approach.

This comprehensive exploration from simple to complex models provides insights into the predictive dynamics of power plant operations, leveraging statistical and machine learning techniques to enhance understanding and prediction accuracy of energy output.