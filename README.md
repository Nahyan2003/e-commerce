🛋️ E-commerce Furniture Dataset Project

This project analyzes and models sales data from the E-commerce Furniture Dataset 2024, which contains 2,000 entries scraped from AliExpress. The dataset provides insights into online furniture sales, discounts, and market trends.

📂 Project Files

ecommerce_furniture_dataset.csv → Dataset used for analysis

ecommerce_furniture_project.ipynb → Jupyter Notebook with step-by-step analysis

ecommerce_furniture_project_report.pdf → Detailed project report with methodology and results

project.py → Original Python script version of the project

README.md → Documentation of the project

📊 Dataset Overview

The dataset contains the following columns:

productTitle: Name of the furniture item

originalPrice: Original price before discount

price: Final selling price after discount

sold: Number of units sold

tagText: Shipping/offer tags (e.g., "Free shipping")

Dataset size: 2,000 rows × 5 columns

🎯 Objective

The main goal is to predict the number of items sold (sold) based on product attributes like price, discounts, and shipping tags.

🛠️ Tech Stack

Programming Language: Python

Libraries: pandas, seaborn, matplotlib, scikit-learn

Tools: Jupyter Notebook, VS Code

🚀 Project Workflow

Data Collection – Load dataset from CSV

Data Preprocessing – Handle missing values, clean price fields, encode categorical values

Exploratory Data Analysis (EDA) – Visualize distributions, scatterplots, and relationships

Feature Engineering – Create discount percentage and encoded features

Model Training – Train Linear Regression & Random Forest models

Model Evaluation – Compare using Mean Squared Error (MSE) and R² Score

Conclusion – Identify key insights and best model

📈 Exploratory Data Analysis

Distribution of product prices and items sold

Effect of discount percentage on sales

Analysis of shipping/offer tags (e.g., Free shipping vs. Paid shipping)

🤖 Machine Learning Models

Linear Regression: Baseline predictive model

Random Forest Regressor: Robust non-linear model

🔍 Model Results

Linear Regression: Suitable for linear relationships, baseline performance

Random Forest: Better performance, handles complex interactions in features

📝 Conclusion

Discounts and free shipping play a significant role in boosting sales

Random Forest performed better than Linear Regression in predicting sales

The project shows how data preprocessing, feature engineering, and ML models can help businesses optimize e-commerce strategies

🙌 Acknowledgements

Dataset sourced from AliExpress via Apify

Project inspired by the E-commerce Furniture Dataset 2024 guide
