<img src="images/housing_market.jpg_fit=scale" width=400 height=400 />

# King County, WA Housing Sales Analysis
---


# Overview
---

Our team was hired by a hot-shot real estate agency to create a model which predicts the prices of houses in the King County area based on differnt features. These features include: city/town/neighborhood location, square footage, number of bedrooms, whether it's on the water, how good of a view it has, ...

To acheive our goal, we will use multiple linear regression models to analyse housing sales in King County, WA  using housing data gathered within the county from 2014 and 2015. 

For this analysis, we have used regression models such as, Ordinary Least Squared, Train-Test Split, and K-Fold Cross Validation models to create an efficient predictive model. 

Our analysis shows that based on the R^2 scores, our regression model's accuracy is ...


# Business Understanding
---
Our stakeholder wants to be able to predict the price of a house based on certain features provided by their customers. 

Our project will answer the following questions:
* With what accuracy could we predict the prices of houses based on these features?
* What specific housing features will provide us with the most accurate model? 


# Data Understanding
---
The data used for this project was sourced from a dataset called ‘King County House Sales’ and contains information regarding housing sales statistics in King County, WA.

##### The dataset contains the following columns:

* ```id```: A unique sale id relating to a house sale
* ```date```: Date of house sale
* ```price```: The price which the house sold for
* ```bedrooms```: How many bedrooms the house has
* ```bathrooms```: How many bathrooms the house has
* ```sqft_living```: How much square footage the house has
* ```sqft_lot```: How much square footage the lot has
* ```floors```: How many floors the house has
* ```waterfront```: Whether the house is on the waterfront. Originally contained ‘YES’ or ‘NO’, converted to 0 or 1 for comparative purposes
* ```view```: Whether the house has a view and whether it’s fair, average, good, or excellent. Converted to numberical (0-4) for comparative purposes
* ```condition```: overall condition of the house: Poor, Fair, Average, Good, Very Good
* ```grade```: Numerical grading for house
* ```sqft_above```: How much of the houses square footage is above ground
* ```sqft_basement```: How much of the square footage is in the basement
* ```yr_built```: Year the house was built
* ```yr_renovated```: Year the house was renovated, if applicable
* ```zipcode```: House zipcode
* ```lat```: House’s latitude coordinate
* ```long```: House’s longitude coordinate
* ```sqft_living15```: Average size of living space for the closest 15 houses
* ```sqft_lot15```: Average size of lot for the closest 15 houses


# Modeling
---
This project uses linear regression models, such as Ordinary Least Squared, Train-Test Split, and K-Fold Cross Validation to provide predictive modeling for our real estate stakeholder

We began by splitting our data frame into three section by feature type: 
1) House features such as square footage and room numbers
2) House quality and age
3) House location within King County (City/Town/Suburb). This process was done through geo locating the latitude and longitude columns

We then created linear regression models for each section and narrowed down our features through assessing coorrelation and finding potential multicollinearity issues

Finally, we combined the updated selection of column features and created a final regression model and a corresponding visualization for our overal prediction


# Regression Results
---



# Conclusion
---


# Next Steps
---


# Further Questions
---
See the full analysis in the Jupyter Notebook or review this presentation

For any additional questions, please contact ....


# Repository Structure
---
├── data
├── images
├── README.md
├── housing_sales_modeling.ipynb
└── Housing_Sales_Modeling_Presentation.pdf

