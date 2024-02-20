# prediction_of_fuel_consumption
Prediction_of_Fuel_Consumption

<img alt="BC" src="https://i.pinimg.com/originals/51/13/e4/5113e4472a82a2c4e8e0805703830a3d.jpg" width='500'  align='center'/>

<!-- ABOUT THE PROJECT -->
## About The Project

This code project involves data analysis of automobile performance and building regression models. The main objective of the project is to understand the impact of various automobile features (such as cylinders, horsepower, weight, etc.) on fuel efficiency and to create regression models to predict fuel efficiency based on these features.

The steps of the project are as follows:

- 1)Loading the dataset: Data related to automobile performance is retrieved from the "auto-mpg.data" file and loaded into a DataFrame.

- 2)Data preprocessing: The dataset is examined, missing values are checked and appropriately filled, and outliers are detected and, if necessary, removed.

- 3)Exploratory Data Analysis (EDA): Various visualizations are used to analyze the dataset. Correlations are examined, distributions of features are displayed, and outliers are confirmed.

- 4)Feature engineering: Some categorical features are transformed using one-hot encoding, and the dataset is prepared for regression models.

- 5)Data splitting and standardization: The dataset is split into training and test sets. Numerical features are standardized.

- 6)Building Regression Models: Different regression models such as linear regression, ridge regression, lasso regression, ElasticNet, and XGBoost are experimented with, and the performance of these models is evaluated.

- 7)Evaluation of Model Performance: The prediction performance of each model is evaluated using mean squared error (MSE).

- 8)Averaging Models: In some cases, better performance can be achieved by averaging predictions from multiple models. This approach is also evaluated.

At the end of the project, the fuel efficiency prediction capabilities of different regression models and their combinations are compared, and the best-performing model or models are identified.

### Built With

* ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
* ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
* ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
* ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
* ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
* ![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white)
