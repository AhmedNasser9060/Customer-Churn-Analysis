# 📊 Telco Customer Churn Analysis & Prediction

End-to-end data analysis and predictive modeling project focused on identifying key drivers of customer churn in the telecom industry and building a high-performance classification model.

---

## 📌 Project Overview

Customer churn is a critical business problem in subscription-based industries.  
This project demonstrates a complete data workflow:

- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Preprocessing
- Model Building & Comparison
- Hyperparameter Optimization
- Model Evaluation
- Dashboard Deployment

The objective is to extract actionable business insights and develop a reliable churn prediction system.

---

## 📂 Dataset

- Telco Customer Churn Dataset
- Contains customer demographics, subscription services, billing information, and churn status

---

## 🧠 Project Workflow

### 1️⃣ Exploratory Data Analysis (EDA)

- Analyzed churn distribution and class imbalance
- Investigated churn behavior across:
  - Contract types
  - Payment methods
  - Internet services
  - Tenure groups
- Built correlation heatmaps and statistical summaries
- Identified key churn drivers

---

### 2️⃣ Feature Engineering

Created business-driven features to improve predictive performance:

- `TenureGroup` (Customer lifetime segmentation)
- `ChargesPerMonth`
- `Contract_PaymentInteraction`
- `HasPhoneAndInternet`
- `NumServices` (Total subscribed services)

---

### 3️⃣ Data Preprocessing

- Converted categorical variables using Label Encoding
- Scaled numerical features using `StandardScaler`
- Implemented custom missing value imputation using Euclidean distance similarity
- Handled class imbalance

---

### 4️⃣ Model Building & Comparison

Trained and evaluated multiple classification models:

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

Applied:

- `GridSearchCV`
- `Optuna` hyperparameter tuning
- 5-fold cross-validation

---

## 📊 Model Performance

### 🏆 Best Model: XGBoost

- **Accuracy:** 80.0%
- **ROC-AUC:** 0.84
- **Precision (Churn class):** 0.66
- **Recall (Churn class):** 0.51

The model demonstrates strong predictive performance and generalization capability.

---

## 📈 Evaluation Metrics

- Accuracy
- Precision / Recall / F1-score
- ROC Curve & AUC
- Confusion Matrix
- Model comparison visualization

---

## 🚀 Deployment

An interactive dashboard was developed using Streamlit to:

- Visualize churn insights
- Allow user input for churn prediction
- Display real-time prediction results

🔗 Live Demo:  
https://telco-churn-dashboard.streamlit.app/

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Optuna
- Plotly
- Streamlit

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/your-repo-name.git](https://github.com/AhmedNasser9060/Customer-Churn-Analysis
cd Customer-Churn-Analysis

Install dependencies:

pip install -r requirements.txt

Run Streamlit app:

streamlit run app.py
🎯 Business Impact

This project demonstrates how data analysis and machine learning can:

Identify high-risk customers

Support retention strategies

Reduce revenue loss

Enable data-driven decision-making

📌 Key Takeaways

Complete end-to-end data workflow

Strong analytical and statistical reasoning

Model comparison and optimization

Deployment of ML solutions into interactive applications


