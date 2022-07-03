# King-County-House-Sales


## Home Regression Model

### Overview

This project entails using a multiple regression model to analyse home sales data in King County



### Business Problem

As a consultant, my client, Sunset Real Estate Company, is currently exploring the idea of purchasing properties to remodel either for the purpose selling or renting to prospective clients in King County.

I will analyse the current housing data from King's County to understand better the different factors affecting housing within the county and advice on the best investment strategy.

### Objective

To build a model that predicts the price of houses with an acceptably high accuracy.

To identify variables with the most weight when it comes to predicting the highest market price.

To advice on the best investment strategy

### Data

For my analysis I will use kc_house _data.csv. It has over 21000 records of home sales in the county.

#### Columns in the data set

id - unique identified for a house

date - house was sold

price - is prediction target

bedrooms- of Bedrooms/House

bathrooms- of bathrooms/bedrooms

sqft_living - footage of the home

sqft_lot - footage of the lot

floors - Total floors (levels) in house

waterfront - House which has a view to a waterfront

view - Has been viewed

condition - How good the condition is ( Overall )

grade - overall grade given to the housing unit, based on King County grading system

sqft_above - square footage of house apart from basement

sqft_basement - square footage of the basement

yr_built - Built Year

yr_renovated - Year when house was renovated

zipcode - zip

lat - Latitude coordinate

long - Longitude coordinate

sqft_living15 - The avg square footage of interior housing living space for the nearest 15 neighbors

sqft_lot15 - The avg square footage of the land lots of the nearest 15 neighbors

### Methods

I performed Inferential Analysis on the data by removing outliers in the data using z score.
I then used multiple regression analysis to build a pricing model to assess the strengh, relationship and importance of different factors and how they affect the pricing of a property.

### Results

The final model of best fit at a variance of 84% had the following outstanding features as the greatest price determinants:

Conditions

Location

Bedrooms

Views 

### Recommendations

Less is more when it comes to the number of bedrooms. An unit increase in the bedrooms leads to a 2.38% drop in the sale price. To generate higher sale prices, Sunset Real Estate should focus on houses with few bedrooms (1,2 &3).

Newer houses fetch a higher price in the market. The goal should be to get houses off as soon as they hit the market.

Increasing the sqft living of a house increases the market price.

You've probably heard it before from Allsopp and Spencer but it indeed is about Location, Location, Location! Location makes all the difference. SOme of the Zipcodes that fetch the highest prices in the market include:

zip_98004 - Beaux Arts Village

zip_98040 - Mercer Island

zip_98039 - Medina

zip_98102 - Seattle

zip_98105 - Seattle

zip_98109 - Seattle

zip_98112 - Seattle

zip_98119 - Seattle

The different parts of seattle seems to be a huge preference for most of the home buyers & renters

Houses in condition 5 will fetch the highest price in the market and View 2 fetches a higher market price compared to view 1.

A ideal house that would fetch the highest price in the market would be approximately 3 bedrooms, in Medina, WA (Zipcode 98039) with view 2 and in condition 5

A major opportunity would be to find home which falls into the low conditions category and possibly renovate them in order to change the condition to the middle to high categories in order to to increase the estimated sales price.

### For More Information

See the full analysis in the Jupyter Notebook or review this presentation






