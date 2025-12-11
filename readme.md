🛒 E-Commerce Customer Spending Prediction
⭐ Linear Regression Machine Learning Model · Kaggle Dataset · End-to-End Analysis
<p align="center"> <img src="https://img.shields.io/badge/Python-3.10+-blue?logo=python"/> <img src="https://img.shields.io/badge/Scikit--Learn-ML%20Model-orange?logo=scikitlearn"/> <img src="https://img.shields.io/badge/Status-Completed-brightgreen"/> <img src="https://img.shields.io/badge/License-MIT-yellow"/> <img src="https://img.shields.io/badge/Made%20with-Love-red"/> </p>
📌 Project Overview

This project builds a Linear Regression Machine Learning model that predicts Yearly Customer Spending using behavioral data from an e-commerce platform.

Using a Kaggle dataset, I performed:

📊 Extensive Data Exploration

⚙️ Feature Engineering

🤖 Model Training

🧪 Evaluation

📉 Insight Generation

The goal is to understand which user activities drive revenue and build a model capable of accurate predictions.

📂 Dataset Description
Feature	Description
Average Session Length	Avg time per session
Time on App	Total time spent on mobile app
Time on Website	Total time spent on website
Length of Membership	Years since the user joined
Yearly Amount Spent	Target variable (customer spending)

Dataset Source: Kaggle – E-Commerce Customer Behavior Dataset

🧠 ML Approach
✔ Algorithm Used: Linear Regression

Simple, explainable, and effective for continuous output prediction.

✔ Steps Performed

Data Cleaning & Formatting

Exploratory Data Analysis (EDA)

Heatmaps

Pair plots

Correlation analysis

Feature Selection

Train-Test Split

Model Training

Metrics Evaluation

Insights Extraction

📈 Key Insights

Length of Membership is the strongest predictor of spending

Time on App correlates more with spending than Time on Website

The model gives a high R² score, showing good predictive accuracy

Visualizations reveal clear linear trends in features

🛠 Tech Stack
Tool	Purpose
Python	Programming
Pandas	Data processing
NumPy	Numerical operations
Matplotlib / Seaborn	Visualizations
Scikit-Learn	Machine Learning
🚀 How to Run the Project
1️⃣ Clone Repository
git clone https://github.com/manveer-kaur0/LR-E-Commerce-App.git

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Run the Notebook / Script

Open code.ipynb in Jupyter
OR

python model.py

📂 Project Structure
📦 LR-E-Commerce-App
 ┣ 📜 code.ipynb
 ┣ 📜 data.csv
 ┣ 📜 readme.md
 ┣ 📜 requirements.txt (optional)
 ┣ 📜 model.py (optional)

🧪 Model Evaluation
Metric	Value
MAE	✔️ Good
MSE	✔️ Low
R² Score	⭐ High predictive accuracy

(Exact values depend on your latest training run.)

⭐ Future Enhancements

Add Random Forest / XGBoost models

Build a Flask / FastAPI API

Deploy model on Render / Vercel / Heroku

Add a Streamlit web app

Add Hyperparameter tuning

🤝 Contributing

Pull requests are welcome.
Feel free to fork the repo and submit improvements.
