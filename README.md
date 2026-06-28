# Part 3 – Regression-Based Business Insights

## Business Problem

The objective of this project is to identify the business factors that influence monthly sales across retail stores using regression analysis.



## Dataset Description

The dataset contains monthly operational and sales information for multiple retail stores including:

- Marketing Spend
- Footfall
- Discount Percentage
- Staff Count
- Inventory Availability
- Competitor Distance
- Holiday Flag
- Customer Rating
- Store Type
- Region
- Monthly Sales
- Monthly Profit



## Dependent Variable

- Monthly Sales



## Independent Variables

- Marketing Spend
- Footfall
- Inventory Availability
- Customer Rating
- Discount Percentage
- Store Type
- Region



## Regression Approach

The analysis includes:

- Two Simple Linear Regression Models
- One Multiple Linear Regression Model
- Dummy Variable Creation
- Residual Analysis
- Model Comparison



## Dummy Variable Approach

Categorical variables were converted into dummy variables.

One category was omitted as the reference category to avoid multicollinearity.



## Model Comparison Summary

Three regression models were developed.

The Footfall model substantially outperformed the Marketing Spend model.

The Multiple Regression Model provided the most comprehensive explanation of monthly sales by combining several business drivers.



## Final Model Selected

Multiple Regression

Reasons:

- Multiple significant predictors
- Better business interpretation
- More useful for decision-making
- Stronger predictive capability



## Business Recommendation

Leadership should prioritise:

- Increasing customer footfall
- Improving inventory availability
- Optimising marketing expenditure
- Monitoring store-type differences



## Assumptions

- Linear relationships
- Independent observations
- Constant variance
- Normally distributed residuals



## Limitations

- Regression shows association rather than causation.
- External variables are not included.
- Future economic conditions may affect performance.



## Repository Contents

```
data/
analysis/
outputs/
screenshots/
README.md
```



## Screenshots Included

- simple_regression_output.png
- multiple_regression_output.png
- residuals_preview.png
- model_comparison_preview.png
