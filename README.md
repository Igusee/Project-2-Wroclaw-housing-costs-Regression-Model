# Real Estate Price Regression Project in R

## About my data:
* Dataset included key details about apartments in Wrocław.
* Data variables consisted of:
  * **Building Age**: Time since construction in years.
  * **Distance from City Center**: Distance in kilometers from the main square.
  * **Apartment Size**: Area of the apartment in square meters.
* Dataset source: **Otodom**.
* Initial preprocessing involved removing incomplete records (e.g., missing construction dates or location details).

## Data Preparation in R:
* Imported data from an Excel file using the `readxl` package.
* Cleaned and formatted variables to ensure consistency:
  * Removed records with missing or incorrect data.
  * Transformed data types where necessary.
* Performed initial exploratory analysis to understand relationships between variables.

## Regression Modeling:
* Created linear regression models to analyze relationships between price and key variables:
  * Observed:
    * Negative correlation between price and building age.
    * Negative correlation between price and distance from the city center.
    * Positive correlation between price and apartment size.
* Compared multiple regression models with varying combinations of variables.
* Evaluated models using statistical measures like **p-value**, **R²**, and **adjusted R²**:
  * Selected the best-fit model based on these metrics.
  * Identified and excluded outliers to enhance model accuracy.

## Visualization and Diagnostics:
* Generated key plots using R:
  * Scatter plots with regression lines to illustrate variable relationships.
  * Residual plots to assess model assumptions.
  * Quantile-quantile plots to check normality of residuals.
* Evaluated multicollinearity and verified the independence of residuals using statistical tests.

## Key Outputs:
* Predicted apartment prices for hypothetical scenarios using the final model.
* Analyzed and visualized residuals to ensure robustness of the model.

## Files:
* **R Code**: Provided in this repo for reproducibility.
* **Visualizations**: Included as outputs in the repository.

## This project provided valuable insights into factors influencing apartment prices in Wrocław and demonstrated the application of linear regression in R for real estate analysis. Feel free to explore the code and datasets in the repository!
