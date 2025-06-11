📈 Linear Regression Project: Predicting Apartment Prices
📝 Project Overview
This project applies linear regression to predict the price of apartments based on features such as size, number of bedrooms, and location. It serves as an educational exercise to demonstrate how linear regression works in practice, including data exploration, feature engineering, and model evaluation.

🎯 Objective
To develop a simple yet effective linear regression model that can estimate the price of an apartment given a set of explanatory variables. The goal is to interpret model coefficients and assess performance using appropriate statistical metrics.

📊 Dataset Description
The dataset includes apartment-related variables:

size: Square footage of the apartment

bedrooms: Number of bedrooms

price: Target variable – apartment price

Other features may include floor number, building type, and location indicators, depending on preprocessing steps.

🔍 Steps Followed
Data Cleaning and Preprocessing

Checked for missing values and outliers

Converted categorical variables into dummy/indicator variables

Exploratory Data Analysis (EDA)

Visualized feature relationships with matplotlib and seaborn

Identified multicollinearity and non-linear patterns

Model Building

Built a linear regression model using sklearn

Split the data into training and test sets

Trained the model and generated predictions

Model Evaluation

Used evaluation metrics such as:

R² Score

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Analyzed residual plots to verify model assumptions

Model Interpretation

Interpreted the coefficients to understand the impact of each feature on apartment price

Validated linearity, homoscedasticity, and independence assumptions

🛠️ Tools & Libraries
Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

Statsmodels

📌 Conclusion
The linear regression model offered reasonable predictions with interpretable coefficients. It is well-suited for basic prediction tasks, but may benefit from regularization or feature transformation if overfitting or non-linearity is observed.

