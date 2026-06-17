# Restaurant-Rating-Prediction-ML
 Project Overview

This project aims to predict the aggregate rating of restaurants using machine learning techniques. The dataset was preprocessed by handling missing values, encoding categorical variables, and splitting the data into training and testing sets.

Two regression algorithms were implemented:

* Linear Regression
* Decision Tree Regression

The models were evaluated using Mean Squared Error (MSE) and R² Score.


 Dataset Features

The dataset contains restaurant-related information such as:

* Restaurant Name
* City
* Cuisines
* Average Cost for Two
* Price Range
* Votes
* Location Information
* Online Delivery Availability
* Table Booking Availability

Target Variable:

* Aggregate Rating


 Data Preprocessing

1. Loaded the dataset using Pandas.
2. Handled missing values in the Cuisines column.
3. Encoded categorical features using Label Encoding.
4. Split the dataset into training and testing sets (80:20 ratio).



 Models Used

 Linear Regression

Linear Regression was used as a baseline regression model.

Results:

* Mean Squared Error (MSE): 1.2187
* R² Score: 0.4646

 Decision Tree Regression

Decision Tree Regression was used to capture non-linear relationships between features.

Results:

* Mean Squared Error (MSE): 0.0572
* R² Score: 0.9749



 Feature Importance

The most influential features affecting restaurant ratings were:

1. Votes
2. Rating Color
3. Rating Text
4. Restaurant ID
5. Longitude

Votes had the highest impact on restaurant rating prediction.


 Conclusion

The Decision Tree Regression model significantly outperformed the Linear Regression model. It achieved an R² Score of 0.9749, indicating excellent predictive performance.

This project demonstrates the application of machine learning techniques for restaurant rating prediction and feature importance analysis.


 Technologies Used

 Python
 Pandas
 NumPy
 Scikit-Learn
 Google Colab


 Author

Velkur Joharika

