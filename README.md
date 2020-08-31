# Shek-s-House-Prices-Advanced-Regression-Techniques-Guide
This is a guide for you to draw inspiration to kick-start your data science competition journey. This is the House Prices: Advanced Regression Techniques hosted by Kaggle.

This is a very basic walkthrough(if you want to call it that) of the competition. I wanted to provide the framework for elementary analysis, preprocessing and modeling. Use this as a bicycle with training wheels. Doing well in competitions is all aboout trying things others havent to get the score you need, so, please use this notebook as a starting point and expand it in anyway you see fit. Here's the description of the compition:

Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.

# Overview:

The Ames Housing dataset was compiled by Dean De Cock for use in data science education. It's an incredible alternative for data scientists looking for a modernized and expanded version of the often cited Boston Housing dataset. 

Goal
It is your job to predict the sales price for each house. For each Id in the test set, you must predict the value of the SalePrice variable. 

# Skills you'll practice:

- Creative feature engineering 
- Advanced regression techniques like random forest and gradient boosting

# Metric

Submissions are evaluated on Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted value and the logarithm of the observed sales price. (Taking logs means that errors in predicting expensive houses and cheap houses will affect the result equally.) So, be sure to optimize to this metric
