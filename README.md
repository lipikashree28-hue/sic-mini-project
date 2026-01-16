🏥 Medical Cost Prediction using Machine Learning
📌 Project Overview

This project focuses on predicting medical expenses based on patient-related features such as age, Body Mass Index (BMI), and number of medical procedures.
The aim is to demonstrate how machine learning regression techniques can be used to estimate healthcare costs efficiently.

🎯 Problem Statement

To build a machine learning model that predicts the medical cost of a patient using the following features:

Age

BMI

Number of medical procedures

This is a supervised regression problem where the target variable is continuous.

📂 Dataset Description

The dataset is provided in CSV format and contains:

age – Age of the patient

bmi – Body Mass Index

num_procedures – Number of medical procedures undergone

medical_cost – Total medical cost (target variable)

The dataset was raw and unclean, containing missing values that required preprocessing.

🔧 Technologies & Libraries Used

Python

Google Colab

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn

🔄 Project Workflow

Data Loading

Data Cleaning & Preprocessing

Exploratory Data Analysis (EDA)

Feature Selection

Train–Test Split

Model Training

Model Evaluation

Live Prediction Demo

📊 Exploratory Data Analysis (EDA)

EDA was performed to understand the relationship between features and medical cost.

Scatter plots were used to analyze trends

Correlation between features and target variable was studied

Outliers were inspected using boxplots

🤖 Model Used

Linear Regression

The model was trained on 80% of the data and tested on the remaining 20%.

📈 Model Evaluation Metrics

The performance of the model was evaluated using:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

R² Score

These metrics help measure prediction accuracy and model reliability.

🔍 Sample Prediction

The model can predict medical cost for custom input values.

Example Input:

Age: 45

BMI: 28.5

Number of Procedures: 3

Predicted Output:

Estimated Medical Cost (in currency units)

🚀 How to Run the Project

Open the project notebook in Google Colab

Upload the dataset CSV file

Run all cells sequentially

Modify input values in the prediction cell to test new cases

🔮 Future Enhancements

Add more features like smoking habits, region, and gender

Use advanced models such as Random Forest or XGBoost

Perform hyperparameter tuning

Deploy the model using Streamlit or Flask

👩‍💻 Author

Lipika Shree
B.Tech – AI & ML
Mini Machine Learning Project

📜 License

This project is for academic and educational purposes only.
