# UsedCarPricePredictor

## Used car price predictor for car dealerships

The goal is to understand what factors make a car more or less expensive. As a result of the analysis, the model should provide clear recommendations to the client—a used car dealership—as to what consumers value in a used car.

The selected model should be able to predict the price of a used car.

For this task the provided dataset contains information on 426K cars. 


### Methodology

The notebook follows these steps:

Define the business problem as a regression and interpretation task.

Inspect missingness, outliers, distribution, and categorical cardinality.

Clean invalid prices, unrealistic years, odometer outliers, and messy categorical values.

Feature Engineering

Compare models using MAE as the primary metric, with RMSE and R² as supporting metrics.

Interpret price drivers using Ridge coefficients, permutation importance, EDA, and business judgment.


### Models Used

Ridge Regression

Ridge Regression with polynomial degree=2

Ridge Regression with polynomial degree=3


### HyperParameter tuning with

GridSearchCV with k-fold validation


### Recommendations for the dealerships

