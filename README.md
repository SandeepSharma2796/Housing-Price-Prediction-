# Housing-Price-Prediction-
Housing price prediction is a significant area of study in the fields of data science and machine learning, 
given the complex factors that influence real estate markets. Accurate prediction of housing prices helps 
buyers, sellers, real estate agents, and policy makers make informed decisions. In this project, we will 
use a dataset of California housing prices, which contains key features such as location, population, 
median income, and housing characteristics, to develop a predictive model. By leveraging machine 
learning algorithms in Python, we aim to build a model that can forecast housing prices with high 
accuracy.

The dataset used in this project is the California Housing Dataset, which contains information from the 
1990 U.S. Census. It includes demographic and geographical data, which are crucial to predicting
housing prices in various regions of California. This dataset has been widely used in machine learning 
tutorials, making it a valuable resource for understanding real-world housing prediction tasks.

The goal of this project is to explore various machine learning techniques, preprocess the data, and 
evaluate the performance of different models to predict housing prices based on the available features.


**#Problem Statement**
In the real estate market, accurately predicting housing prices is a key challenge that influences various 
stakeholders, including homebuyers, real estate agents, investors, and policymakers. Predicting housing 
prices requires an understanding of the relationship between various factors such as income levels, 
geographical location, demographic characteristics, and housing features. This project focuses on 
building a predictive model to forecast the median house values in California based on a variety of 
attributes such as the median income, the age of the houses, the number of rooms, and the population 
of each district.

The dataset used for this project, known as the California Housing Dataset, contains information from 
the 1990 U.S. Census and includes demographic and geographical features for different districts in 
California. The challenge is to build a model that can predict the median house value for each district, 
given its various features. This problem is framed as a regression task, where the goal is to predict a 
continuous value—the median house value—based on input features

**#ABOUT DATASET**
This dataset is used in the second chapter of Aurélien Géron's recent book 'Hands-On Machine Learning 
with Scikit-Learn and TensorFlow'. It contains information from the 1990 California census and serves as 
an excellent introduction to implementing machine learning algorithms. The dataset includes various 
features related to housing and demographics within a block in California.
• Longitude: A measure of how far west a house is; a higher value is farther west
• Latitude: A measure of how far north a house is; a higher value is farther north
• Housing Median Age: Median age of a house within a block; a lower number is a newer building
• Total Rooms: Total number of rooms within a block
• Total Bedrooms: Total number of bedrooms within a block
• Population: Total number of people residing within a block
• Households: Total number of households, a group of people residing within a home unit, for a block
• Median Income: Median income for households within a block of houses (measured in tens of 
thousands of US Dollars)
• Median House Value: Median house value for households within a block (measured in US Dollars)
• Ocean Proximity: Location of the house w.r.t ocean/sea.

**#Technical Use**
➢ Programming Language: Python
➢ Data Manipulation and Analysis: Pandas, NumPy
➢ Python Visualization Library: Matplotlib, Seaborn (optional)
➢ Machine Learning Framework: Scikit-learn
➢ Modeling Algorithms: Linear Regression, Random Forest Regressor
➢ Model Evaluation: MSE, RMSE, R²

#Outcome of the Housing Price Prediction Project
The outcome of the project revolves around building an effective predictive model that can estimate the 
median house values in California based on various features such as median income, number of rooms,
population, and geographical location. Below are the key outcomes:
Linear Regression achieved better performance on the test set compared to Random Forest Regression
in terms of both R2 and error metrics (MSE and MAE).

**#R-Squared (Test):**
#**Linear Regression ** achieved an R2 of 0.494, indicating it explained around 
49.4% of the variance in housing prices in the test data.
• Train-Test Consistency: Linear Regression showed consistency between training and test scores, 
with a training R2 of 0.513, indicating minimal overfitting.



****#Random Forest Regression ****
showed signs of overfitting, with a significantly higher training R2 (0.910) 
compared to its test R2 (0.427).
• Error Metrics: Random Forest had a higher Mean Squared Error (MSE) and Mean Absolute Error (MAE) on the test set than Linear Regression, suggesting it had larger prediction errors.

**#Conclusion**
The Linear Regression model demonstrated a more reliable performance on the test set, 
providing a good balance between simplicity and predictive accuracy. With an R2R^2R2 of 
0.494, it explained nearly 49.4% of the variance in housing prices.
• Random Forest, despite its higher training score, appeared to be overfitting to the training data, 
as evidenced by its lower test score and higher error metrics. With further hyperparameter 
tuning or the use of regularization techniques, it could potentially improve.
• Overall, Linear Regression emerged as the better model in this context, offering a simpler and 
more consistent approach to predicting housing prices
