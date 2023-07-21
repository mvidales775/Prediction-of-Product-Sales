# Preditction of Product Sales
## Analyzing Diffrent factors that effect sales

**Michael Vidales** 

### Business problem:

### Data:
[Big Mart Sales Prediction](https://datahack.analyticsvidhya.com/contest/practice-problem-big-mart-sales-iii/)

From this dataset, there were 8523 rows and 11 columns 

## Data Dictionary:
![DataDictionary.png](DataDictionary.png)

## Methods
- During the exploratory data analysis, a boxplot and histogram was visualized for each numeric datatype column. 
- Also, a barplot was visualized for each categorical column. 
- This gave a good baseline for all of the numeric and categorical columns for univariate EDA.

## Results


#### Visual 1 Title
![ITEMTYPE_COUNT.png](ITEMTYPE_COUNT.png)

> Sentence about visualization.

#### Visual 2 Title
![ITEMSALES_BY_TYPE.png](ITEMSALES_BY_TYPE.png)

>


## Model

- Linear Regression Model
- Random Forest Regressor Model
- Tuned Random Forest Regressor Model

------------------------------------------------------------
Linear Regression Test Data
------------------------------------------------------------
- MAE = 804.12
- MSE = 1,194,351.19
- RMSE = 1,092.86
- R^2 = 0.57

------------------------------------------------------------
Random Forest Test Data
------------------------------------------------------------
- MAE = 766.73
- MSE = 1,216,006.15
- RMSE = 1,102.73
- R^2 = 0.56

------------------------------------------------------------
Tuned Random Forest Test Data
------------------------------------------------------------
- MAE = 734.69
- MSE = 1,119,162.23
- RMSE = 1,057.90
- R^2 = 0.59


The Final Model Chosen was a Random Forest Regressor Model with the n_estimators tuned to 100.

For the testing set on the model, 59% of the variance in y was explained by x.

The Mean Absolute Error was off by about $734.69.

The Mean Squared Error was $1,119,162.23.

The Root Mean Squared Error had a calculation of $1,057.90.


## Recommendations:

More of your own text here


## Limitations & Next Steps

More of your own text here


### For further information


For any additional questions, please contact 

Michael Vidale
**mvidales775@gmail.com**
