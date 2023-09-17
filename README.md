# Predicting house prices
The project aims to employ different regression models in machine learning to predict house prices in Ames, Iowa, given numerous house attributes. 
The jupyter notebook includes:
•	Exploratory data analysis (data visualization included) to determine problems with the data and uncover patterns among house features, between house features and prices.
•	Data preprocessing (imputing, scaling, encoding, and creating new features) to manipulate data to be ready for machine learning.
•	Building regression models: Linear regression, Ridge regression, Lasso regression, ElasticNet regression, Decision Tree regression, Random Forest regression, Gradient Boosting Tree, XGBoost, KNeighbors.
•	Hyperparameter tuning based on GridSearchCV
•	Model evaluation based on Root Mean Squared Error (RMSE)
•	Prediction based on model stacking to take advantage of base models to generate final predictions with higher accuracy.

### Datasets:
Datasets are taken from Kaggle, one for training, and the other for testing.
Datasets contain 80 columns (excluded identifier column) with 79 predictor variables and one target variable (SalePrice). Predictor variables mainly fall into these categories: Type of house, location, age, lot, roof, floor, basement, rooms, utilities (central air, heating…), garage, external features (pool, porch…), and type of sale.

### Dependencies:
•	numpy
•	pandas
•	matplotlib
•	seaborn
•	sklearn
•	xgboost
