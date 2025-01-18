# Used Vehicle Price Prediction using Craigslist data
 This project aims to address challenges in the used car market by developing a machine learning model to estimate the market value of used vehicles based on online listing information.
## Test Set Performance

| Model                       | RMSE               | R²               |
|-----------------------------|--------------------|------------------|
| Baseline                   | 12,423.36          | -0.000000044     |
| Multivariate Linear Regression | 6,171.44          | 0.7532           |
| Random Forest Regressor    | 3,619.28           | 0.9151           |
### Interpretation

Since the price of cars is typically in the tens of thousands, the performance of our final model (Random Forest Regressor) is acceptable. The model achieves an RMSE of $3,619, meaning its predictions are, on average, off by only $3,619. With an R² of 0.9151, the model can explain 91.51% of the variance in car prices, making it a effective tool for estimating used car values.

## Insights  
Variables like year, odometer, and manufacturer significantly impact pricing.  
## Strengths  
Random Forest effectively captures non-linear relationships and interactions between variables compared to baseline models.  
## Challenges 
Handling high-cardinality features and filtering noisy data from online marketplaces.  
## Improvements
Test out more powerful or novel models, tune hyperparameters for better performance, handle missing data more effectively.

[link to dataset](https://www.kaggle.com/datasets/austinreese/craigslist-carstrucks-data)
