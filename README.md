# Project:2 Predict the price of homes at sale for the Aimes Iowa Housing
------------------------------------------------------------------------
## Contents:
  - Problem Statement
  - Executive Summary
  - Data Dictionary
  - Conclusions and Recommendations
------------------------------------------------------------------------

## Problem Statement

The project aims to advise Aimes residents that if they want to sell a house, what top 5 features of the house will help increase the selling price and also help people who want to buy a house in Aimes that which top 5 features they should 

------------------------------------------------------------------------
## Executive Summary

To explore which features of the house that affect the sale price, I used data from Kaggle which contain features of the house. This project aims to use features of house to predict sale price of the house by using linear regression and also use other regression like ridge regression, lasso regression and elasticnet regression if the model is overfitting.

------------------------------------------------------------------------
## Data Dictionary

| Feature           | Type         | Description                                |
| :---------------: | :----------: | -----------------------------------------: |
|Overall Qual       | object       | Overall material and finish quality        |
|Gr Liv Area        | int          | Above grade (ground) living area square feet |
|Total Bsmt SF      | float        | Total square feet of basement area  |
|Garage Area        | float        | Size of garage in square feet             |
|Garage Cars        | float        | Size of garage in car capacity             |
|1st Flr SF         | int          | First Floor square feet |
|Year Built         | int          | Original construction date |
|Garage Yr Blt      | int          | Year garage was built              |
|Year Remod/Add     | int          | Remodel date (same as construction date if no remodeling or additions)             |
|Full Bath          | int          | Full bathrooms above grade |
|Street             | object       | Type of road access to property |
|Mas Vnr Area       | float        | Masonry veneer area in square feet              |
|TotRms AbvGrd      | int          | Total rooms above grade (does not include bathrooms)             |
|Lot Shape          | object       | General shape of property                             |
|Land Contour       | object       | Flatness of the property                            |
|Lot Config         | object       | Lot configuration                            |
|Condition 1        | object       | Proximity to main road or railroad                            |
|House Style        | object       | Style of dwelling                            |
|Exter Qual         | object       | Exterior material quality |
|Exter Cond         | object       | Present condition of the material on the exterior|
|Foundation         | object       | Type of foundation|
|Bsmt Qual          | object       | Height of the basement              |
|Bsmt Exposure      | object       | Walkout or garden level basement walls              |
|BsmtFin Type 1     | object       | Quality of basement finished area                            |
|Central Air        | object       | Central air conditioning                         |
|Fireplace Qu       | object       | Fireplace quality                         |
|Garage Type        | object       | Garage location           |
|Garage Finish      | object       | Interior finish of the garage           |
|Garage Cond        | object       | Garage condition           |
|Paved Drive        | object       | Paved driveway          |


------------------------------------------------------------------------
## Conclusions and Recommendations

### Top 5 features

- The top feature affect sale price the most is ground living square feet with a coefficient at 25075, this means that if one unit increase in ground living square feet price of the house will increase 25,075 US dollar.

- The second feature affect sale price the most is overall material and finish quality with a coefficient at 14587, this means that if one unit increase in quality price of the house will increase 14,587 US dollar.

- The third feature affect sale price the most is total square feet of basement area with a coefficient at 12604, this means that if one unit increase in basement area price of the house will increase 12,604 US dollar.

- The fourth feature affect sale price the most is excellent height of the basement (100+ inches) with a coefficient at 8647, this means that if one unit increase in excellent height of the basement price of the house will increase 8,647 US dollar.

- The fifth feature affect sale price the most is garage area with a coefficient at 8039, this means that if one unit increase in garage area price of the house will increase 8,039 US dollar.

For Sellers
 - For people who want to sell their house in Aimes they can use this model to predict their house price.
 - For real estate agent they can use these top 5 features  to predict price of the house before buy or selling it, so they can gain the maximum profit.

For Buyers
 - For people who want to buy house in Aimes they can use this top 5 features to find the house that suitable for their budget such as if they got a limit budget but wnat to find house that bigger they can find house that has lower material quality for a lower price.
