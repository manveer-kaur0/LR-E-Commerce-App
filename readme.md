
# 📊 E-Commerce Customer Spending Prediction

### *A Machine Learning Project using Linear Regression*

Welcome to my **E-Commerce Customer Spending Prediction Model**, a data-driven project built using a Kaggle dataset and implemented in Python.
This project explores how user behavior on an e-commerce platform influences annual spending — and uses Linear Regression to *predict* future customer revenue with impressive accuracy.

---

## 🚀 Project Overview

The goal of this project is to answer a business-critical question:

### **“How much will a customer spend annually based on their online behavior?”**

To do this, I used a **Kaggle E-commerce Customer Data** dataset that contains behavioral metrics like:

* 🕒 *Average Session Length*
* 📱 *Time on App*
* 🌐 *Time on Website*
* 📅 *Length of Membership*

These features help us understand **what drives customer expenditure** and how companies can use this to improve marketing strategies, personalize services, and optimize user experience.

---

## 📂 Dataset

The dataset includes:

| Column Name            | Description                                      |
| ---------------------- | ------------------------------------------------ |
| *Avg. Session Length*  | Avg minutes per session                          |
| *Time on App*          | Minutes spent on mobile app                      |
| *Time on Website*      | Minutes spent on website                         |
| *Length of Membership* | Number of years the customer has been associated |
| *Yearly Amount Spent*  | 💰 Annual customer expenditure                   |

This dataset is clean, structured, and excellent for regression experiments.

---

## 🧠 What This Model Does

This project applies **Linear Regression** to:

✔ Predict yearly customer spending
✔ Identify which features influence spending most
✔ Visualize correlations
✔ Train, test, and evaluate a machine learning model
✔ Achieve a strong R² score (model accuracy)

---

## 🛠 Tech Stack

* **Python 3**
* **Pandas** → Data manipulation
* **Matplotlib / Seaborn** → Visualizations
* **Scikit-Learn** → Machine Learning
* **Jupyter Notebook / VS Code** → Development

---

## 📈 Workflow

### **1️⃣ Importing Libraries**

Loaded essential ML and visualization libraries.

### **2️⃣ Loading the Dataset**

```python
df = pd.read_csv("data.csv")
```

### **3️⃣ Exploratory Data Analysis (EDA)**

* Pairplots
* Correlation heatmap
* Feature relationship study
* Outlier checking

### **4️⃣ Feature Selection**

Selected four key features:

```python
x = df[['Average Session Length','Time on App','Time on Website','Length of Membership']]
y = df['Yearly Amount Spent']
```

### **5️⃣ Train-Test Split**

Model trained on 70% data, tested on 30%.

### **6️⃣ Model Training**

```python
from sklearn.linear_model import LinearRegression
lm = LinearRegression()
lm.fit(x_train, y_train)
```

### **7️⃣ Model Evaluation**

* Predictions vs Actual comparison
* Residual analysis
* R² score
* Coefficients interpretation

---

## 📊 Results & Insights

💡 **Length of Membership** has the highest correlation with spending — loyal users spend more.
💡 **Time on App** influences spending more than website usage.
💡 The model effectively captures spending behavior trends.

✔ Achieved a strong predictive performance with good regression metrics.

---

## 🧪 How to Run This Project

### **1. Clone the Repository**

```
git clone https://github.com/your-username/ecommerce-linear-regression.git
```

### **2. Install Dependencies**

```
pip install -r requirements.txt
```

### **3. Run the Code**

Either open the `.ipynb` file in Jupyter Notebook
**OR** run the python script:

```
python model.py
```

### **4. View Results**

Graphs, metrics, and predictions will appear in the console/output window.

---

## 📌 Key Learnings

* How to apply Linear Regression to real-world business data
* Understanding of feature impact on revenue
* Data preprocessing and exploratory analysis
* Model evaluation and interpretation
* Building a deployable prediction pipeline

---

## ⭐ Future Improvements

🔹 Try advanced models (Random Forest, XGBoost)
🔹 Deploy the model using Flask / FastAPI
🔹 Add a UI interface
🔹 Hyperparameter tuning
🔹 Add cross-validation

---

## 🤝 Contributing

Pull requests are welcome!
Feel free to fork, modify, and expand the project.

---
