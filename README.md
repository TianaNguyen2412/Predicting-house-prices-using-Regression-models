# Predicting house prices in Ames, Iowa
<p>The project aims to employ different regression models in machine learning to predict house prices in Ames, Iowa, given numerous house attributes. </p>
<p>The jupyter notebook includes:<br>
<ul>
<li>	<strong>Exploratory data analysis</strong> (data visualization included) to determine problems with the data and uncover patterns among house features, between house features and prices.</li>
<li>	<strong>Data preprocessing</strong> (imputing, scaling, encoding, and creating new features) to manipulate data to be ready for machine learning.</li>
<li>	<strong>Building regression models</strong>: Linear regression, Ridge regression, Lasso regression, ElasticNet regression, Decision Tree regression, Random Forest regression, Gradient Boosting Tree, XGBoost, KNeighbors.</li>
<li>	<strong>Hyperparameter tuning</strong> based on GridSearchCV</li>
<li>	<strong>Model evaluation</strong> based on Root Mean Squared Error (RMSE)</li>
<li>	<strong>Prediction</strong> based on model stacking to take advantage of base models to generate final predictions with higher accuracy.</li>
</ul>
</p>

<h3>Datasets:</h3>
Datasets are taken from Kaggle, one for training, and the other for testing.<br>
Datasets contain 80 columns (excluded identifier column) with 79 predictor variables and one target variable (SalePrice). <br>
Predictor variables mainly fall into these categories: Type of house, location, age, lot, roof, floor, basement, rooms, utilities (central air, heating…), garage, external features (pool, porch…), and type of sale.

<h3> Dependencies:</h3>
<ul>
<li>numpy</li>
<li>pandas</li>
<li>matplotlib</li>
<li>seaborn</li>
<li>sklearn</li>
<li>xgboost</li>
