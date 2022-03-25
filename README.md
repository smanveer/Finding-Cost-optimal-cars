# Finding Cost-optimal cars
Built five machine learning models based on regression algorithms to monitor the contributing factors for price and performance of top 15 most-used cars in the market

- Wrangled data to only keep the useful columns for further analysis
-  Dealt with null values, missing values, out of bound values.
-  Used IQR rule and boxplot to extract outliers
-  Build lots of pivot tables and box plots to get a deeper insight.

EXPLORATION-
PRICE Vs. make/ color/ age/ odometer/ condition/ drive
->  Ford has highest average price
->  Found top 3 colors.
--> Found top3 highest sold color

MODELLING
PRE
->  Chose most relevant variables for target,
->  converted categorical into numerical using Label Encoding
->  split data into test and training datasets size 0.5
-> Dummy Regressor
-> Linear Regressor
-> Random Forest
-> Gradient boosting
-> KNN regressor

TUNED THE MODELS, COMPARED THEM AND OBTAINED THE BEST.
