# Phase 2 Project

## Project Overview

For this project, you will use regression modeling to analyze house sales in a northwestern county.

### The Data

This project uses the King County House Sales dataset, which can be found in  `kc_house_data.csv` in the data folder in this repo. The description of the column names can be found in `column_names.md` in the same folder. 

### Business Problem

A housing agency seeks to determine what features of house units determine the prices. Using this information the agency can advise home owners on what features will ensure better market price for their houses. 

## Deliverables

There are three deliverables for this project:

* A **GitHub repository**
* A **Jupyter Notebook**
* A **non-technical presentation**

# Conclusions:
* **R Squared and Adjusted R Squared:**<br>
Our model has a R squared and Adjusted R squared value of 0.641 which indicates that our predictor variables can explain 64.1% of the target variable price. <br>

* **P- Value for the F-Statistic:** <br>
Our p-value is 0.000 indicating that there is good linear relationship between our predictor variables and the target variable (price). <br>
* **P- Value for the features:** <br>
All the selected predictor features have a p-value of less than 0.05 indicating their significance in predicting the target variable. <br>
* **Parameter:** <br>
        **sqft_living (footage of the living space):** <br>
        With a coefficient of 0.4 from the model makes the feature positively correlated feature with price. A unit increase in the footage increases the house price by 0.4 units. <br>
        **grade (this is a grade given based on King County grading system):** <br>
        The feature has a coefficient of 0.58 showing a positive correlation with the price of the housing units. A unit increase in the grade given increase the price of the house unit by 0.5 unit. <br>
        **yr_built (built year):** <br>
        The feature has a coefficient of -0.153 showing a slight negative correlation with price. As the age of a house increases by one year, the price decreases by 0.15.
