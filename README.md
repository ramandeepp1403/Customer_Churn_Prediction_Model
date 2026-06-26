# 👥 Customer Churn Prediction using Machine Learning

An end-to-end **Machine Learning** project that predicts whether a telecom customer is likely to churn based on demographic information, account details, and service usage. The project includes **Exploratory Data Analysis (EDA)**, data preprocessing, feature engineering, model comparison, evaluation, and business insights.

---

# 📌 Project Overview

Customer churn is one of the biggest challenges faced by subscription-based businesses. Retaining existing customers is often more cost-effective than acquiring new ones.

In this project, I built and compared multiple machine learning models to predict customer churn and identify the factors that contribute most to customer retention.

---

# 🎯 Objectives

- Understand customer demographics and service usage
- Perform Exploratory Data Analysis (EDA)
- Clean and preprocess the dataset
- Train multiple classification models
- Compare model performance using evaluation metrics
- Identify the most important features influencing customer churn
- Generate actionable business insights

---

# 📂 Dataset

**Dataset:** IBM Telco Customer Churn Dataset

### Dataset Summary

- 👥 **7,043 customers**
- 📊 **21 features**
- 🎯 Target Variable: **Churn**
- Binary Classification Problem

### Dataset Features

| Feature | Description |
|----------|-------------|
| customerID | Unique customer identifier |
| gender | Customer gender |
| SeniorCitizen | Senior citizen indicator |
| Partner | Whether customer has a partner |
| Dependents | Whether customer has dependents |
| tenure | Number of months with the company |
| PhoneService | Phone service subscription |
| MultipleLines | Multiple phone lines |
| InternetService | Internet service type |
| OnlineSecurity | Online security service |
| OnlineBackup | Online backup service |
| DeviceProtection | Device protection plan |
| TechSupport | Technical support subscription |
| StreamingTV | Streaming TV subscription |
| StreamingMovies | Streaming Movies subscription |
| Contract | Contract type |
| PaperlessBilling | Paperless billing status |
| PaymentMethod | Payment method |
| MonthlyCharges | Monthly bill amount |
| TotalCharges | Total charges paid |
| Churn | Target variable (Yes/No) |

---

# 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Google Colab
- Jupyter Notebook

---

# 🔍 Exploratory Data Analysis

The project includes:

- Dataset overview
- Missing value analysis
- Data cleaning
- Summary statistics
- Customer segmentation
- Distribution analysis
- Histograms
- Scatter plots
- Box plots
- Correlation analysis

---

# ⚙️ Data Preprocessing

- Removed unnecessary features
- Converted target variable into numerical format
- Encoded categorical variables
- Feature scaling using StandardScaler
- Train-Test Split (80:20)

---

# 🤖 Machine Learning Models

The following classification algorithms were trained and evaluated:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

Random Forest was further optimized using **GridSearchCV** for hyperparameter tuning.

---

# 📊 Model Performance

| Model | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
|--------|---------:|----------:|--------:|----------:|---------:|
| Logistic Regression | **0.742** | 0.509 | **0.789** | **0.618** | **0.838** |
| Decision Tree | 0.734 | 0.499 | 0.535 | 0.516 | 0.673 |
| Random Forest (Tuned) | **0.789** | **0.631** | 0.495 | 0.555 | 0.823 |

---

# 📈 Model Evaluation

The following evaluation techniques were used:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Classification Report
- Confusion Matrix
- ROC Curve Comparison
- Feature Importance

---

# 📊 Key Insights

- Logistic Regression achieved the **highest Recall (0.789)**, making it better at identifying customers likely to churn.
- Random Forest achieved the **highest Accuracy (0.789)** and **highest Precision (0.631)**, reducing false positive predictions.
- Customer **tenure**, **Monthly Charges**, **Total Charges**, and **Contract Type** were among the most influential features.
- Different evaluation metrics highlight different strengths, emphasizing that model selection should align with business objectives.

---

# 💼 Business Value

This project can help telecom companies:

- Identify customers at risk of leaving
- Improve customer retention strategies
- Design targeted promotional campaigns
- Reduce customer acquisition costs
- Increase long-term customer lifetime value

---

# 📁 Project Structure

```text
Customer_Churn/
│
├── Customer_Churn.ipynb
├── customer_churn_model.pkl
├── scaler.pkl
├── requirements.txt
├── README.md
└── screenshots/
```

---

# ▶️ Getting Started

Clone the repository

```bash
git clone https://github.com/ramandeepp1403/Customer_Churn_Prediction_Model.git
```

Navigate to the project

```bash
cd Customer_Churn_Prediction_Model
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the notebook

```bash
jupyter notebook
```

---

# 📸 Project Preview
<img width="793" height="176" alt="Screenshot 2026-06-27 023735" src="https://github.com/user-attachments/assets/33246016-1969-4c74-92dd-07beca539c0e" />
<img width="603" height="641" alt="Screenshot 2026-06-27 023858" src="https://github.com/user-attachments/assets/c6639134-e88d-498f-96d0-0d07fe33c657" />
<img width="942" height="745" alt="Screenshot 2026-06-27 023927" src="https://github.com/user-attachments/assets/ac47cd19-7afe-4d74-bb6b-8ae5cd8c9e67" />
<img width="1349" height="786" alt="Screenshot 2026-06-27 023958" src="https://github.com/user-attachments/assets/4469ab16-8e31-4f56-8304-668dc34b9ea1" />


---

# 🚀 Future Improvements

- Deploy using Streamlit
- Hyperparameter tuning for additional models
- Explain predictions using SHAP values
- Perform cross-validation
- Experiment with XGBoost and LightGBM

---

# 👨‍💻 Author

**Ramandeep Singh**

- GitHub: https://github.com/ramandeepp1403
- LinkedIn: https://www.linkedin.com/in/ramandeep-pandi/

---

# ⭐ Support

If you found this project helpful, consider giving it a **⭐ Star**.
