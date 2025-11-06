# Customer Churn Prediction

This project focuses on building a machine learning model to predict whether a customer will churn (i.e., discontinue a service) based on various features like contract type, monthly charges, and services used. Early prediction of churn helps businesses retain customers by taking proactive steps.

---

## 📌 Problem Statement

Customer churn is a major concern for telecom and subscription-based businesses. This project aims to predict churn using historical customer data to improve retention strategies.

---

## 🧰 Tools & Technologies Used

- **Programming Language**: Python  
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Models Used**: Decision Tree, Random Forest, XGBoost  
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1 Score, Confusion Matrix  
- **IDE**: Jupyter Notebook

---

## 🧹 Data Preprocessing

- Loaded and explored the Telco Customer Churn dataset
- Handled missing values (notably in `TotalCharges`)
- Applied Label Encoding and One-Hot Encoding to categorical variables
- Scaled numerical features using StandardScaler
- Split data into training and testing sets (80/20)

---

## 📊 Exploratory Data Analysis (EDA)

- Churn was more common among customers with:
  - Month-to-month contracts
  - Higher monthly charges
  - Electronic check as payment method
- Senior citizens also showed a slightly higher churn rate

---

## 🤖 Model Building

Trained and compared the following models:

| Model         | Accuracy |
|---------------|----------|
| Decision Tree | ~75%     |
| XGBoost       | ~77%     |
| Random Forest | **~78%** |

- Random Forest performed the best in terms of overall accuracy and balance

---

## 🧪 Evaluation Metrics

Used the following metrics to evaluate model performance:
- Accuracy
- Precision
- F1 Score
- Confusion Matrix

---

## ✅ Results

- Final model: **Random Forest**
- Achieved: **78% Accuracy**
- Delivered interpretable churn predictions using tree-based models


---

## 📎 Resources

- Dataset: [Telco Customer Churn - Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

---

## 🧑‍💻 Author

Aditya Amodkar
