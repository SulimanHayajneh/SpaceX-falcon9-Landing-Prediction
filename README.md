🚀 SpaceX Falcon 9 First Stage Landing Prediction
📌 Project Overview

This project analyzes historical launch data from SpaceX to predict whether the first stage of the Falcon 9 rocket will successfully land.

Reusable rockets significantly reduce launch costs. Accurately predicting landing success helps assess mission risk and cost efficiency.

This capstone project applies data science methodologies including data collection, data wrangling, exploratory data analysis (EDA), SQL analysis, interactive visualization, and machine learning classification models.

🎯 Business Problem

The cost of a Falcon 9 launch varies depending on whether the first stage booster is successfully recovered.

Objective:
Build a machine learning model that predicts the success of a Falcon 9 first-stage landing using historical launch data.

📊 Data Sources

The dataset was collected from:

SpaceX REST API

Wikipedia launch records

Publicly available SpaceX launch data

The dataset includes:

Launch Site

Orbit Type

Payload Mass

Booster Version

Flight Number

Launch Year

Landing Outcome (Target Variable)

🧹 Data Wrangling

The following preprocessing steps were performed:

API data extraction

Web scraping launch tables

Handling missing values

Feature engineering

Converting categorical variables using One-Hot Encoding

Casting numeric columns to float64

Creating the final feature matrix for modeling

📈 Exploratory Data Analysis (EDA)

EDA was conducted using:

Pandas

Matplotlib

SQL queries

Interactive visualization tools

Key analyses included:

Launch Site vs Landing Success

Orbit Type vs Success Rate

Payload Mass vs Success

Launch Year vs Success Trend

Key Insight:

Landing success improved significantly after 2015, indicating operational learning and system improvements.

🗺 Interactive Visualizations
📍 Folium Interactive Map

Launch sites were visualized using interactive maps to analyze geographical patterns in launch success.

Major launch locations include:

Cape Canaveral

Vandenberg Space Force Base

📊 Plotly Dash Dashboard

An interactive dashboard was developed using:

Plotly Dash

Features:

Launch site dropdown filter

Success rate pie chart

Payload mass vs outcome scatter plot

🤖 Predictive Modeling

Several classification models were implemented:

Logistic Regression

Decision Tree

Random Forest

Support Vector Machine (SVM)

Model Evaluation Techniques:

Train-Test Split

Cross Validation

GridSearchCV

Confusion Matrix

Accuracy Score

🏆 Best Performing Model

Random Forest achieved the highest accuracy and demonstrated strong performance in predicting landing success.

Most important features:

Orbit Type

Launch Site

Payload Mass

📂 Repository Structure
├── data/
├── notebooks/
│   ├── 1_data_collection.ipynb
│   ├── 2_data_wrangling.ipynb
│   ├── 3_eda_visualization.ipynb
│   ├── 4_sql_analysis.ipynb
│   ├── 5_interactive_dashboard.ipynb
│   └── 6_machine_learning.ipynb
├── dashboard/
├── presentation/
└── README.md

🛠 Technologies Used

Python

Pandas

NumPy

Matplotlib

SQL

Folium

Plotly Dash

Scikit-learn

Jupyter Notebook

📌 Conclusion

This project demonstrates how data science techniques can be applied to aerospace operations to:

Analyze historical launch patterns

Identify key success factors

Build predictive models

Support decision-making

Machine learning models successfully predicted Falcon 9 first-stage landing outcomes with strong accuracy, showing the effectiveness of classification techniques in real-world applications.

🔮 Future Improvements

Include weather data

Include booster reflight count

Apply advanced ensemble models (XGBoost)

Deploy model as a web application

👤 Author

Suliman Hayajneh
IBM Data Science Professional Certificate – Capstone Project
2026
