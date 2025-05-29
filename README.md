This project demonstrates the use of simple and multiple linear regression models to predict housing prices based on various features from a housing dataset.

# Overview :

# The dataset is loaded from a CSV file and preprocessed by encoding categorical variables.

* A simple linear regression model is trained using only the area feature to predict house prices.
* Model performance is evaluated using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² score.
* Results are visualized through scatter plots showing actual vs. predicted prices.
* A multiple linear regression model is then trained using multiple features (area, bedrooms, bathrooms, stories, and parking).
* The multiple regression model’s performance is also evaluated and visualized.
* The coefficients of the multiple regression model are displayed to interpret the influence of each feature on the price.

# Key Points :

* Uses pandas for data manipulation.
* Employs scikit-learn for model training, prediction, and evaluation.
* Visualizes results using matplotlib.
* Provides insights into the relationship between housing features and prices.

# Required Libraries :

Make sure to install the following Python libraries before running the code:

* pandas
* matplotlib
* scikit-learn
