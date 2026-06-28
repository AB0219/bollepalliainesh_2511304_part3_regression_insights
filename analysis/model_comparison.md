# Model Comparison

## Objective

The objective of this analysis was to identify the factors that are most strongly associated with monthly sales across retail stores.



## Model Summary

| Model | Dependent Variable | Independent Variable(s) | R² | Significant Variables | Business Usefulness |
|-------|--------------------|-------------------------|------|----------------------|--------------------|
| Simple Regression 1 | Monthly Sales | Marketing Spend | 0.167 | Marketing Spend (p < 0.001) | Moderate |
| Simple Regression 2 | Monthly Sales | Footfall | 0.736 | Footfall (p < 0.001) | High |
| Multiple Regression | Monthly Sales | Marketing Spend, Footfall, Inventory Availability, Store Type Dummy | Higher overall explanatory power | Marketing Spend, Footfall, Inventory Availability, Store Type | Very High |



## Comparison

### Simple Regression Model 1

Marketing spend has a positive relationship with monthly sales. Although statistically significant, the model explains only about 16.7% of the variation in sales.

### Simple Regression Model 2

Footfall is a much stronger predictor of monthly sales. The model explains approximately 73.6% of the variation in sales and provides substantially better predictive performance.

### Multiple Regression Model

The multiple regression model combines several business variables simultaneously. Marketing spend, footfall, and inventory availability remain statistically significant after controlling for other variables. The inclusion of dummy variables allows differences between store types to be measured.



## Business Usefulness

The multiple regression model provides the best understanding of sales performance because it evaluates multiple operational drivers simultaneously.



## Limitations

- Regression identifies association rather than causation.
- External factors such as economic conditions, competitor promotions, and seasonality are not included.
- The model assumes linear relationships among variables.
- Some unexplained variation remains due to omitted variables.



## Final Selected Model

The Multiple Regression Model was selected because it incorporates multiple business drivers and provides the strongest basis for business decision-making.
