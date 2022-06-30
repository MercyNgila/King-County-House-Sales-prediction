# King-County-House-Sales


## Home Regression Model

### Overview
This project entails using a multiple regression model to analyse home sales data in King County

### Business Problem
The company is currently exploring the idea of purchasing properties ro remodel either for the purpose selling or renting to prospective clients in King County.
I will analyse the current housing data from King's County to understand the different factors and areas affecting housing within the county and advice on the best investment strategy. 

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
