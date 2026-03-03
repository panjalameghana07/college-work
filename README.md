#  Machine Learning Analysis of NYC Taxi Dataset

# Project Overview
This project presents a full Big Data and Machine Learning pipeline designed to estimate taxi fare amounts using the NYC Yellow Taxi dataset.

The objective is to demonstrate the application of distributed computing and scalable machine learning techniques on large-scale real-world transportation data.

Using Apache Spark and PySpark MLlib, the system efficiently processes millions of taxi trip records to build predictive models for fare estimation.


# Problem Statement
Traditional data processing solutions struggle to handle large-scale transportation datasets.

This project addresses this challenge by implementing a scalable analytics workflow that:
- Cleans and preprocesses taxi trip data
- Performs feature engineering
- Trains distributed machine learning models
- Evaluates performance for accurate fare prediction

The solution supports:
- Pricing strategy optimization
- Demand forecasting
- Urban mobility operational improvements


#  Methodology

# Data Processing
- Input Format: Parquet files
- Data cleaning and preprocessing
- Feature engineering

# Key Features Engineered
- Pickup hour
- Day of week
- Month
- Passenger count
- Trip distance
- Payment type
- Pickup & drop-off location IDs


#  Machine Learning Models Used

The following regression models were implemented using PySpark MLlib:

1. Linear Regression
2. Decision Tree Regression
3. Random Forest Regression
4. Gradient Boosted Trees

# Evaluation Metric
- Root Mean Square Error (RMSE)


# Key Findings

- Ensemble models performed better than Linear Regression.
- Random Forest and Gradient Boosted Trees achieved lower RMSE.
- Non-linear models are more suitable for taxi fare prediction.


#  Technologies Used

- Apache Spark (PySpark)
- PySpark MLlib
- Python
- Google Colab
- Tableau
- Parquet Data Format


#  Conclusion

This project successfully demonstrates an end-to-end scalable Big Data machine learning workflow.

It highlights:
- The importance of distributed analytics
- The effectiveness of ensemble learning models
- Practical application of machine learning in urban transportation systems
