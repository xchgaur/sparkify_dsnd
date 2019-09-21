# sparkify_dsnd

# Project Overview
Sparkify is a music streaming app, and this dataset contains two months of sparkify user behavior log. Each user uses either the Free-tier with advertisement between the songs or the premium Subscription Plan.Users can upgrade, downgrade or cancel their service at any time. All this data contains key insights that can help the business thrive. The goal of this project is to analyze this data and predict which users are expected to churn.
Another key aspect of this project is to use spark and leverage it to handle big data problems.
The notebook for detailed implementation can be found below here

# Approach
We will follow below steps to build a model which will be able to classify users as churn vs non-churn users.
Data Exploration: learn about the data and define Churn and label data based on churn definition.
Feature Engineering: Create features for each user:this data will be used as input to the model
Data transformation, data splitting and model training:
- Transform feature engineered data. 
- Split data into training, validation and test data.
- Build a machine learning model to train using training data

