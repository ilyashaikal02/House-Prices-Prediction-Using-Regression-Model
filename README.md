# House-Prices-Prediction-Using-Regression-Model
Link Rpubs : https://rpubs.com/Ilyashaikall/HousePricesPrediction

1. Background
Recently, there have been wide swings in the growth rate of housing prices across many countries. Housing prices tend to rise over time; however, accurately predicting them might be a difficult task. There are various factors that may influence the demand for a property. Additionally, it is extremely difficult to figure out which set of factors might explain buyers’ behavior, since every buyer tends to have their own preferences such as house size, location, etc. In this document, I am going to predict housing prices in King County using a linear regression model, as well as find out which attribute plays the key role in determining the housing price. The dataset used was obtained from Kaggle (https://www.kaggle.com/datasets/harlfoxem/housesalesprediction) and consists of 21,613 observations.

Here are some informations about the features:

id: Unique ID for each home sold
date: Date of the home sale
price: Price of each home sold
bedrooms: Number of bedrooms
bathrooms: Number of bathrooms, where .5 accounts for a room with a toilet but no shower
sqft_living: Square footage of the house interior living space
sqft_lot: Square footage of the land space
floors: Number of floors
waterfront: Whether the house was overlooking the waterfront or not
view: An index of how good the view of the property was (0-4)
condition: An index on the condition of the apartment (1-5)
grade: An index on the quality of building construction and design (1-13),
sqft_above: The square footage of the interior housing space that is above ground level
sqft_basement: The square footage of the interior housing space that is below ground level
yr_built: The year the house was initially built
yr_renovated: The year of the house’s last renovation
zipcode: Zipcode area the house is in
lat: Latitude
long: Longitude
sqft_living15: The square footage of interior housing living space for the nearest 15 neighbors
sqft_lot15: The square footage of the land lots of the nearest 15 neighbors
