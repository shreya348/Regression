**Car Resale Price Prediction**

**Overview**
This project focuses on predicting the resale price of cars using advanced machine learning techniques. Accurately predicting resale prices is crucial for both car buyers and sellers to make informed decisions. Our model leverages various car attributes such as mileage, engine capacity, owner history, and more, to predict the resale value. The primary goal is to create a reliable and accurate regression model for price prediction.

**Dataset**
The dataset, titled Car Resale Data – 2023, was sourced from Kaggle and contains 17,446 rows and 14 features.
Key features include:

**Descriptive Features:**
registered_year (Numeric)
engine_capacity (Numeric)
fuel_type (Categorical)
kms_driven (Numeric)
transmission_type (Categorical)
owner_type (Numeric)
mileage (Numeric)
And more...
Target Feature:
resale_price (Numeric)
The dataset underwent pre-processing, including handling missing values, encoding categorical variables, and normalization for numerical features.

**Project Goals**
-Understand how different car attributes influence resale price.
-Build machine learning models that accurately predict car resale prices.
-Evaluate and compare the performance of different regression models.
-Algorithms Used Linear regression, Random Forest, XGBoost and Sequential Neural Network

XGBoost followed closely, demonstrating robust predictive performance.
SNN and Linear Regression showed relatively lower performance due to the dataset size and linear assumptions.

**Conclusion**
The Random Forest Regressor proved to be the most reliable model for predicting car resale prices, effectively capturing non-linear relationships and providing robust predictions. This project highlights the importance of feature selection, data normalization, and model evaluation in building accurate machine learning models for regression tasks.
