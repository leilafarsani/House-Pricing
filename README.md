# Housing Sale Price Prediction

This project utilizes a dataset of home sales in Ames, Iowa, spanning the years 2006 to 2010. The primary objective is to develop a predictive model for house prices. The dataset consists of more than 1400 records, each representing a house sale, and it includes 79 features describing various attributes, such as:

- Square footage
- Number of bedrooms
- Neighborhood
- Construction materials
- Quality ratings
- Condition

## Here are some key details about the dataset:

- It contains information on 1460 individual residential homes sold between 2006 - 2010 in Ames, Iowa.
- The data has 79 explanatory variables describing various attributes of each home like square footage, number of bedrooms, neighborhood, roof type, basement condition etc.
- The target variable to predict is the sale price of each home.
- Predictors include both numerical and categorical variables. Some feature engineering will be required for modeling.
- 23 nomimal variables like RoofStyle, Condition1, BldgType will need encoding into numeric variables.
- There are some missing values in the dataset that will need to be handled.
- A few key numeric predictors are OverallQual (quality rating), GrLivArea (square footage), LotArea, YearBuilt, TotalBsmtSF (basement size).
- Goal is to build a model to accurately predict the SalePrice based on the predictors. Regression algorithms like linear regression, random forest can be used.
- Useful evaluation metrics are RMSE, R-squared, MAE to assess model prediction accuracy.



## Here's a brief version of what you'll find in the data description file.

- SalePrice - the property's sale price in dollars. This is the target variable that you're trying to predict.
- MSSubClass: The building class
- MSZoning: The general zoning classification
- LotFrontage: Linear feet of street connected to property
- LotArea: Lot size in square feet
- Street: Type of road access
- Alley: Type of alley access
- LotShape: General shape of property
- LandContour: Flatness of the property
- Utilities: Type of utilities available
- LotConfig: Lot configuration
- LandSlope: Slope of property
- Neighborhood: Physical locations within Ames city limits
- Condition1: Proximity to main road or railroad
- Condition2: Proximity to main road or railroad (if a second is present)
- BldgType: Type of dwelling
- HouseStyle: Style of dwelling
- OverallQual: Overall material and finish quality
- OverallCond: Overall condition rating
- YearBuilt: Original construction date
- YearRemodAdd: Remodel date
- RoofStyle: Type of roof
- RoofMatl: Roof material
- Exterior1st: Exterior covering on house
- Exterior2nd: Exterior covering on house (if more than one material)
- MasVnrType: Masonry veneer type
- MasVnrArea: Masonry veneer area in square feet
- ExterQual: Exterior material quality
- ExterCond: Present condition of the material on the exterior
- Foundation: Type of foundation
- BsmtQual: Height of the basement
- BsmtCond: General condition of the basement
- BsmtExposure: Walkout or garden level basement walls
- BsmtFinType1: Quality of basement finished area
- BsmtFinSF1: Type 1 finished square feet
- BsmtFinType2: Quality of second finished area (if present)
- BsmtFinSF2: Type 2 finished square feet
- BsmtUnfSF: Unfinished square feet of basement area
- TotalBsmtSF: Total square feet of basement area
- Heating: Type of heating
- HeatingQC: Heating quality and condition
- CentralAir: Central air conditioning
- Electrical: Electrical system
- 1stFlrSF: First Floor square feet
- 2ndFlrSF: Second floor square feet
- LowQualFinSF: Low quality finished square feet (all floors)
- GrLivArea: Above grade (ground) living area square feet
- BsmtFullBath: Basement full bathrooms
- BsmtHalfBath: Basement half bathrooms
- FullBath: Full bathrooms above grade
- HalfBath: Half baths above grade
- Bedroom: Number of bedrooms above basement level
- Kitchen: Number of kitchens
- KitchenQual: Kitchen quality
- TotRmsAbvGrd: Total rooms above grade (does not include bathrooms)
- Functional: Home functionality rating
- Fireplaces: Number of fireplaces
- FireplaceQu: Fireplace quality
- GarageType: Garage location
- GarageYrBlt: Year garage was built
- GarageFinish: Interior finish of the garage
- GarageCars: Size of garage in car capacity
- GarageArea: Size of garage in square feet
- GarageQual: Garage quality
- GarageCond: Garage condition
- PavedDrive: Paved driveway
- WoodDeckSF: Wood deck area in square feet
- OpenPorchSF: Open porch area in square feet
- EnclosedPorch: Enclosed porch area in square feet
- 3SsnPorch: Three season porch area in square feet
- ScreenPorch: Screen porch area in square feet
- PoolArea: Pool area in square feet
- PoolQC: Pool quality
- Fence: Fence quality
- MiscFeature: Miscellaneous feature not covered in other categories
- MiscVal: $Value of miscellaneous feature
- MoSold: Month Sold
- YrSold: Year Sold
- SaleType: Type of sale
- SaleCondition: Condition of sale
- We are going to convert train ad test data. And We are going to drop SalePrice column for predict.

### What else is the data trying to say to us ?
We need to analyse the data. Analysing data is the most important thing to understand what the data is telling us.

## Goal

The overarching goal of this project is to employ machine learning regression techniques to uncover relationships between these housing attributes and the eventual sale price. An accurate model would empower us to estimate a home's value based on its characteristics. This has significant applications in various domains, including:

- Real estate pricing
- Market analysis
- Property investments

## Summary

In summary, this project aims to harness the wealth of detailed housing data to construct a regression model capable of predicting Ames home prices with a high degree of accuracy. The insights derived from this model will prove valuable to various stakeholders, including home buyers, sellers, developers, and real estate professionals.

### Let's embark on this data science journey to uncover valuable insights about housing prices in Ames, Iowa!

