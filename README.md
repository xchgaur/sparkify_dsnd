# sparkify_dsnd
BLOG LINK: https://medium.com/@gchauhan.blr/how-can-i-hold-on-to-my-customers-4704b74679fd

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

# Data
input data file provided by udacity:
'mini_sparkify_event_data.json'

# Files

1) Jupyter Notebook called Sparkify.ipynb
2) html file Sparkify.html

# Packages
pyspark
seaborn
matplotlib
numpy
pandas

# Conclusion
# Summary
We developed a model which can predict customer churn. We performed EDA, Feature engineering and created featureset to be used for ML model trainig and validation. We used cross validation and grid search to fine tune our model. However we achieved about 87% accuracy, and 0.84 F1 score with base Random Forest model.

# Reflection
This project gives exposure to spark environment to analyze a large volume of data.
One of the interesting things was to identify the derived features from the page column. This will be a key takeaway from this project.Exposure to spark to handle big data is another big plus
# Improvement
There is still lot of scope for improvement here. We have not taken into account some features like user_agent and location which can play a part here. Also I was not able to run this on cloud spark cluster due to time constraints and few platform config issues.
Next step will be to develop the model on large data on aws cluster.
