# ✈️ Flight Price Exploratory Data Analysis (EDA)
📌 Project Overview

This project focuses on Exploratory Data Analysis (EDA) of a flight price dataset to understand the key factors that influence airline ticket prices. The goal is to uncover patterns, trends, and insights that can help in price prediction and decision-making.

🎯 Objectives

Analyze flight ticket pricing behavior

Identify factors affecting flight prices

Understand relationships between price and features like airline, route, duration, and stops

Prepare data for future machine learning models

📂 Dataset Description

The dataset contains historical flight booking information with the following features:

Airline – Airline carrier name

Date_of_Journey – Travel date

Source – Departure city

Destination – Arrival city

Route – Flight route

Dep_Time – Departure time

Arrival_Time – Arrival time

Duration – Total travel time

Total_Stops – Number of stops

Price – Flight ticket price (Target Variable)

🧹 Data Cleaning & Preprocessing

The following preprocessing steps were applied:

Removed missing and inconsistent values

Converted date and time features into numerical format

Transformed duration into total minutes

Encoded categorical variables

Removed redundant and irrelevant columns

📊 Exploratory Data Analysis

EDA was performed using statistical analysis and visualizations.

🔹 Univariate Analysis

Price distribution shows right-skewness

Certain airlines consistently have higher prices

Non-stop flights tend to be more expensive

🔹 Bivariate & Multivariate Analysis

Airline vs Price: Premium airlines charge higher fares

Stops vs Price: More stops usually result in lower prices

Journey Month vs Price: Peak seasons have higher prices

Duration vs Price: Longer flights with stops are generally cheaper

Route Analysis: Popular routes show higher price variation

📈 Key Insights

Airline selection significantly impacts ticket price

Non-stop flights are costlier but preferred

Prices increase during holidays and peak seasons

Longer duration and multiple-stop flights are cheaper

Route popularity affects price volatility

🛠️ Tools & Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

🚀 Future Work

Build machine learning models for price prediction

Compare models like Linear Regression, Random Forest, XGBoost

Deploy the model using Flask or Streamlit

Create a user-friendly flight price prediction app

📌 Conclusion

This EDA provides a strong foundation for understanding flight pricing dynamics. The insights gained can be effectively used to develop accurate flight price prediction models and assist travelers in making informed booking decisions.

🤝 Author

Huzaifa Iqbal
Data Analyst | Aspiring Data Scientist
