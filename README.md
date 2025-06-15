Real Estate Valuation (Taiwan Housing Dataset)
This project develops a regression model to predict property prices per unit area based on various features such as age, location, and convenience metrics, utilizing the Taiwan Housing Dataset. The goal is to provide accurate property valuations to aid in real estate analysis and decision-making.

Project Overview
The Real Estate Valuation project focuses on building a robust regression model to estimate the price per unit area of properties in Taiwan. By analyzing key factors that influence property value, this model can serve as a valuable tool for real estate agents, investors, and individuals interested in the housing market.

Features and Data
The model utilizes the Taiwan Housing Dataset, which includes the following features to predict 

Age of the house: The older the house, the generally lower the price.
Location: Proximity to MRT (Mass Rapid Transit) stations.
Convenience metrics: Number of convenience stores nearby.
Transaction date: Used to extract temporal features like year and month.
Methodology
Data Preprocessing: The initial data undergoes cleaning and preparation. This includes extracting temporal features such as the year and month from the transaction date.
Model Training: A regression model is trained using Scikit-learn's LinearRegression algorithm.
Prediction: The trained model is used to predict new property values. [cite_start]The output is then converted to USD for better interpretation.
Model Evaluation

Mean Squared Error (MSE): Measures the average squared difference between the estimated values and the actual value.
R² Score: Represents the proportion of the variance in the dependent variable that is predictable from the independent variables. The model was evaluated using MSE and R² metrics.
