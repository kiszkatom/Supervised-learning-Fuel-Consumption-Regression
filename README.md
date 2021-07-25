# Supervised-learning-Fuel-Consumption-Regression
The goal is to find out good regression model for fuel consumption prediction.
# Data
Data came from https://www.fueleconomy.gov/feg/ws/index.shtml#fuelType1.
# Data manipulations
I want to focus on prediction of combine consuption (comb08 variable). I decide to use varaiables: cylinders, displ, year, guzzler, tCharger, sCharger, startStop and dummy variables on columns drive, eng_dscr, fuelType, make, trany, VClass. After dropping outliers i define linear, ridge, lasso and elstaic net regression models.
# Results
![image](https://user-images.githubusercontent.com/62485500/126897591-3801ac51-dbeb-4710-9e13-c147156104c7.png)

As we can see on this image the best result gives ridge model. Also only ridge model gives accepatble scores.
