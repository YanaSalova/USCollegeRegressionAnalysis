# USCollegeRegressionAnalysis
**USCollegeRegressionR** is a comprehensive analysis of college and university data in the United States using R for regression analysis. This repository provides a detailed workflow for preparing data, performing linear regression, and addressing common issues in regression analysis.


### Features

- **Data Preparation**: Load and preprocess datasets, handle missing values, and prepare data for regression analysis.
- **Regression Analysis**: Define dependent and independent variables, perform linear regression using the `lm` function, and interpret regression results.
- **Model Diagnostics**: Construct confidence intervals, bivariate confidence regions, and check for multicollinearity.
- **Redundancy Analysis**: Identify and remove redundant predictors manually and using stepwise regression.
- **Residual Analysis**: Assess the normality of residuals, plot Predicted vs. Residuals, and check for model adequacy.
- **Outliers Detection**: Identify outliers using Cook's distance and Mahalanobis distance.
- **Visualization**: Create plots for regression diagnostics and results interpretation.




### Analysis

1. **Data Preparation**:
    - The dataset has been loaded and missing values have been handled.
    - Dependent and independent variables for the regression model have been defined.

2. **Regression Analysis**:
    - The summary of the regression model has been interpreted, focusing on coefficients, significance levels, and R-squared values.

3. **Model Diagnostics**:
    - Confidence intervals and bivariate confidence regions have been constructed.
    - Multicollinearity has been checked using variance inflation factors (VIF).
    - Redundant predictors have been identified and removed manually using redundancy tables.

4. **Stepwise Regression**:
    - Forward and backward stepwise regression based on AIC criteria has been performed.
    - Results have been compared and the optimal model has been selected.

5. **Residual Analysis**:
    - The normality of residuals has been assessed and Predicted vs. Residuals plots have been created to check model adequacy.
    - Outliers have been identified using Cook's distance and Mahalanobis distance.
