# 📊 Customer Churn Analysis and Prediction

## 📌 Overview

This project focuses on **analyzing telecom customer churn** and building predictive models to determine whether a customer is likely to leave the company.
It combines **exploratory data analysis (EDA)**, **visualizations**, and **machine learning models** to derive actionable business insights.

---

## 📂 Project Structure

```
├── Customer Churn Analysis and Prediction - Project Source Code.ipynb  # Main Jupyter Notebook
├── data/
│   └── Telco_Customer_Churn_Dataset.csv                               # Dataset (not included in repo)
├── README.md                                                          # Project documentation
```

---

## 🎯 Objectives

* Perform **EDA** to identify patterns and correlations affecting churn.
* Visualize customer demographics, services, and churn distribution.
* Build and evaluate predictive models to **classify churn vs. non-churn customers**.
* Compare performance across different metrics: **accuracy, precision, recall, F1, MCC, ROC-AUC**.
* Provide **business insights** to reduce churn.

---

## 🔑 Key Features

* 📊 **EDA & Visualization**: Heatmaps, histograms, churn distribution plots.
* ⚙️ **Preprocessing**: Handling missing values, encoding categorical variables, feature scaling.
* 🤖 **Machine Learning Models**:

  * Logistic Regression
  * Random Forest
  * XGBoost
  * Hybrid Ensemble Model
* 📈 **Evaluation Metrics**: Accuracy, Precision, Recall, F1, MCC, Confusion Matrix, ROC Curve.
* ✅ **Final Insights & Recommendations**.

---

## 📊 Example Visualizations

* **Churn Distribution by Gender & Contract Type**
* **Correlation Heatmap**
* **ROC & PR Curves**
* **Feature Importance Plots**

---

## ⚡ Tech Stack

* **Python**
* **Pandas, NumPy** – Data manipulation
* **Matplotlib, Seaborn** – Visualization
* **Scikit-learn** – ML models & evaluation
* **XGBoost** – Gradient boosting model
* **Jupyter Notebook** – Development environment

---

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/customer-churn-prediction.git
   cd customer-churn-prediction
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Open Jupyter Notebook:

   ```bash
   jupyter notebook
   ```
4. Run the notebook:

   ```
   Customer Churn Analysis and Prediction - Project Source Code.ipynb
   ```

---

## 📌 Results

* Best performing model: **Ensemble Hybrid (Stacked XGBoost + Random Forest)**
* Achieved:

  * Accuracy: **XX%**
  * F1 Score: **XX%**
  * ROC-AUC: **XX%**

---

## 📢 Future Work

* Hyperparameter optimization with GridSearchCV / Optuna
* Deploy model as a **Flask/Django web app**
* Automate churn alerts for business use cases
