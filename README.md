# 🔄 Customer Churn Prediction using Machine Learning

This project aims to predict customer churn in a bank using various machine learning models. The dataset contains customer-level information like credit score, geography, age, tenure, balance, and activity status. The objective is to predict whether a customer will leave the bank or not.

---

## 📁 Dataset Overview

The dataset includes the following features:

- `CreditScore`: Customer credit score (higher score → less likely to churn)
- `Geography`: Customer's country of residence
- `Gender`: Male or Female
- `Age`: Age of the customer
- `Tenure`: Years of relationship with the bank
- `Balance`: Account balance
- `NumOfProducts`: Number of bank products used
- `HasCrCard`: Has credit card (1) or not (0)
- `IsActiveMember`: Active status of the customer
- `EstimatedSalary`: Estimated annual salary
- `Exited`: Target variable — whether the customer has exited the bank (1) or not (0)

---

## 🛠️ Preprocessing Steps

- Removed non-informative features: `RowNumber`, `CustomerId`, and `Surname`.
- Applied **OneHot Encoding** to categorical features (`Geography`, `Gender`).
- Performed feature scaling using `StandardScaler`.

---

## 🧠 Machine Learning Models Used

The following models were trained and evaluated on the dataset:

| Model                  | Accuracy Score |
|------------------------|----------------|
| Logistic Regression    | 0.8155         |
| K-Nearest Neighbors    | 0.8095         |
| Decision Tree (CART)   | 0.7750         |
| Random Forest          | 0.8470         |
| Support Vector Regressor (SVR) | 0.8335 |
| Gradient Boosting      | 0.8580 ✅      |

✅ **Best Model**: Gradient Boosting achieved the highest accuracy at **85.80%**.

---

## 📈 Evaluation Metrics

- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/BrijeshRakhasiya/CustomerChurn-Prediction.git
   cd churn-prediction-ml
  

# 📊 Future Enhancements
Apply hyperparameter tuning using GridSearchCV

Try deep learning models like ANN

Build a web app interface using Flask or Streamlit

# 📌 Project Status
✅ Model Trained
✅ Accuracy Compared
🔜 Deployment in Progress



 
## 📄 License

This project is licensed under the MIT License.

---
**Made ❤️ by Brijesh Rakhasiya**
