### HouseSalesKingCountUSA
Data Analysis IBM

### Notebook Information
Gemini
expand_less
Notebook
InvalidParameterError 
more_horiz
keyboard_arrow_down
House Sales in King Count USA
Table of Contents
Instructions
About the Dataset
Module 1: Importing Data
Module 2: Data Wrangling
Module 3: Exploratory Data Analysis
Module 4: Model Development
Module 5: Model Evaluation and Refinement
Estimated Time Needed: 75 min

keyboard_arrow_down
Instructions
In this assignment, you are a Data Analyst working at a Real Estate Investment Trust. The Trust would like to start investing in Residential real estate. You are tasked with determining the market price of a house given a set of features. You will analyze and predict housing prices using attributes or features such as square footage, number of bedrooms, number of floors, and so on. This is a template notebook; your job is to complete the ten questions. Some hints to the questions are given.

As you are completing this notebook, take and save the screenshots of the final outputs of your solutions (e.g., final charts, tables, calculation results etc.). They will need to be shared in the following Peer Review section of the Final Project module.

add
Kode
add
Teks
keyboard_arrow_down
About the Dataset
This dataset contains house sale prices for King County, which includes Seattle. It includes homes sold between May 2014 and May 2015. It was taken from here. It was also slightly modified for the purposes of this course.

### Variable	Description
id	A notation for a house
date	Date house was sold
price	Price is prediction target
bedrooms	Number of bedrooms
bathrooms	Number of bathrooms
sqft_living	Square footage of the home
sqft_lot	Square footage of the lot
floors	Total floors (levels) in house
waterfront	House which has a view to a waterfront
view	Has been viewed
condition	How good the condition is overall
grade	overall grade given to the housing unit, based on King County grading system
sqft_above	Square footage of house apart from basement
sqft_basement	Square footage of the basement
yr_built	Built Year
yr_renovated	Year when house was renovated
zipcode	Zip code
lat	Latitude coordinate
long	Longitude coordinate
sqft_living15	Living room area in 2015(implies-- some renovations) This might or might not have affected the lotsize area
sqft_lot15	LotSize area in 2015(implies-- some renovations)

### Results
R² (coefficient of determination) is a measure of how well your regression model explains the variability in the target data. The R² value ranges from 0 to 1:

R² = 1: The model explains 100% of the variability in the data. This means the model is very accurate, and all data points lie exactly on the regression line.
R² = 0: The model explains none of the variability in the data. This indicates that the model is no better than simply taking the average.
With an R² value of 0.9979, this indicates that your model explains about 99.79% of the variability in the target data. This means your model is very good at predicting target values based on the features used. However, it’s always wise to check for potential overfitting with the training data.
