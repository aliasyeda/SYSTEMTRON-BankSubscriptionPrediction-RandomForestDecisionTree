# SYSTEMTRON-BankSubscriptionPrediction-RandomForestDecisionTree

# Customer Subscription Prediction using Decision Tree & Random Forest

This project uses the **Bank Marketing dataset** from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/bank+marketing) to predict whether a customer will subscribe to a term deposit based on their demographic and behavioral data.

---

## 🧠 Project Goal

> **Build a Decision Tree classifier** to predict if a customer will purchase a service, based on historical data.

Additionally, we trained a **Random Forest model** to improve performance and compare results.

---

## 📁 Dataset Used

- **Source**: UCI Bank Marketing Dataset  
- **Features**: Age, Job, Marital Status, Education, Loan, Contact Type, etc.  
- **Target**: `y` → Whether the customer subscribed to a term deposit (`yes` or `no`)

---

## ⚙️ Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn (DecisionTreeClassifier, RandomForestClassifier)
- Matplotlib & Seaborn (for visualization)
- Joblib (for saving models)

---

## ✅ Workflow Summary

- Loaded the dataset and preprocessed missing & categorical data
- Converted the target column `y` to binary (1 = yes, 0 = no)
- Split data into training and testing sets (80/20)
- Trained a **Decision Tree model** and saved it
- Trained a **Random Forest model** for comparison
- Evaluated both models using:
  - Accuracy
  - Classification Report (Precision, Recall, F1)
  - Confusion Matrix

---

## 📊 Decision Tree Accuracy

- **Accuracy**: `88.94%`
- **F1-Score (Class 1 - Subscribed)**: `0.51`


Confusion Matrix:
[[6846  457]
 [ 454  481]]
 

## How to Use

Clone the repo and run the notebook or script.

Pass a customer's information into the predict_subscription() function.

Get the prediction: 1 = subscribed, 0 = not subscribed.



## 📌 Note
This project started with Random Forest to enhance prediction accuracy  then  later included  Decision Tree model as per task instructions.

## 👨‍💻 Author

Developed by
**Syeda Alia Samia**  
GitHub:[Syeda Alia Samia](https://github.com/your-github-username)


