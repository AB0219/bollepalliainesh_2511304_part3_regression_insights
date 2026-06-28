# Regression Model Equations

## Simple Regression Model 1

Dependent Variable:

Monthly Sales

Independent Variable:

Marketing Spend

Equation:

Monthly Sales = 560777.35 + (2.13 × Marketing Spend)

### Interpretation

- Intercept: Expected sales when marketing spend is zero.
- Marketing coefficient: Every additional unit of marketing spend is associated with an increase of approximately 2.13 units in monthly sales.



## Simple Regression Model 2

Dependent Variable:

Monthly Sales

Independent Variable:

Footfall

Equation:

Monthly Sales = 446410.58 + (35.68 × Footfall)

### Interpretation

Each additional customer entering the store is associated with an average increase of approximately 35.68 units in monthly sales.



## Multiple Regression Model

Dependent Variable:

Monthly Sales

Independent Variables

- Marketing Spend
- Footfall
- Inventory Availability
- Store Type Dummy Variables

Equation

Monthly Sales =
146249.80
+ 1.18(Marketing Spend)
+ 33.68(Footfall)
+ 3062.93(Inventory Availability)
− 22957.90(StoreType_High Street)
+ ...



## Dummy Variable Explanation

Store Type was converted into dummy variables.

Dummy variables created:

- StoreType_High Street
- StoreType_Mall
- StoreType_Residential

Reference Category:

The omitted category is used as the reference category to avoid the dummy variable trap.



## Final Model Selected

Multiple Regression Model

Reason:

- Uses multiple operational factors simultaneously.
- Produces stronger business insights.
- Controls for differences across store types.
- More suitable for forecasting than individual simple regression models.
