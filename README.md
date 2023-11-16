Profit Prediction for Startups using Regression Algorithms
================
## Introduction:
The scope of this project was to analyze data for 50 startup companies located in different 
States. The aim was to use Regression Machine Learning algorithms to predict Profit 
based on several features. These features consisted of R&D Spend, Administration Spend, 
Marketing Spend, and State.

* **Data Source:** 50 Startups dataset on [Kaggle](https://www.kaggle.com/datasets/farhanmd29/50-startups)

<br>

## Data Analysis:

![A correlation matrix](/images/1.png)

* Profit had a very high positive correlation with R&D Spend.
* Profit had a high positive correlation with Marketing Spend.

<br><br>

![A bar chart of the Total Profit of the startups by State](/images/2.png)

As a group, the startup companies in New York had the highest Total Profit.

<br><br>

![A bar chart of column sums grouped by State](/images/3.png)

In each State, the highest expense for the startup companies was Marketing Spend.

<br><br>

![A bar chart of the average Marketing Spend of the startups by State](/images/4.png)

As a group, the startup companies in Florida had the highest Average Marketing Spend.

<br>

## Regression Machine Learning Models:

Several algorithms were used including linear regression, gradient boosting, and bagging. Metrics were compared for each model to determine which model was to be selected for providing predictions. The metrics used for evaluation were the R-squared value and the Root Mean Square Error (RMSE) value. The criteria for selection was that the model needed to have a high R-squared value and a low testing set Root Mean Square Error (RMSE) value.

<br>

### Machine Learning Models Sorted by Highest R2 Score:

![Machine Learning Models Sorted by highest R2 Score](/images/5.png)

<br>

If the R-squared metric is the focus, then the XGBoost Regressor needed to be selected as the model to use for predictions. It had the highest R-squared value.

<br>

### Machine Learning Models Sorted by Lowest Root Mean Squared Error:

![Machine Learning Models Sorted by lowest Root Mean Squared Error](/images/6.png)

<br>

If the RMSE metric is the focus, then the XGBoost Regressor needed to be selected as the model to use for predictions. It had the lowest RMSE value.
 
<br>

The XGBoost model was then used to make a prediction. For a startup company located in California having a R&D Spend of $132,455.87, an Administration Spend of $1,235,674.98, and a Marketing Spend of $678,343.00, the predicted Profit was $154,958.64

<br>

## Findings:
* Profit had a very high positive correlation with R&D Spend.<br><br>
* Profit had a high positive correlation with Marketing Spend.<br><br>
* As a group, the startup companies in New York had the highest Total Profit.<br><br>
* In each State, the highest expense for the startup companies was Marketing Spend.<br><br>
* As a group, the startup companies in Florida had the highest Average Marketing Spend.<br><br>
* Several Machine Learning Regression algorithms were used. The XGBoost Regression model was selected to predict Profit, because the XGBoost Regression model had the highest R-squared value and the lowest RMSE value.<br><br>

**Please click [here](https://github.com/eric5412/Profit-Prediction-for-Startups-using-Regression/blob/main/Profit%20Prediction%20for%20Startups%20using%20Regression%20Algorithms.ipynb) for the entire project.**

<br><br>
<br><br>
