# 🧠 Customer Churn Prediction using Machine Learning

This project aims to build a predictive model to identify whether a customer will churn (leave) based on their historical and behavioral data. The workflow includes data preprocessing, and applying machine learning models such as XGBoost and MLP.

## 📌 Project Structure
- `ModelingCustomerChurn_Masmur_Toloni_Harefa.ipynb`: Main Jupyter Notebook containing all analysis, modeling, and evaluation.
- `README.md`: Project documentation.

## 📊 Dataset
This project uses a customer churn dataset from kaggle : https://www.kaggle.com/datasets/muhammadshahidazeem/customer-churn-dataset?select=customer_churn_dataset-testing-master.csv. The dataset contains features such as:
- Customer demographic info
- Customer Spending
- Service usage
- Churn label (target: 0 = not churned, 1 = churned)

## 🧪 Techniques Used

### ✅ Preprocessing
- Missing value handling
- Feature scaling (StandardScaler)
- Train-test split with stratification


### ✅ Models Applied
- **XGBoost** ,**KNN**, **Decision Tree**, **Random Forest**
- **Multilayer Perceptron (MLP)** Neural Network with Keras
- Evaluation Metrics:
  - Accuracy
  - Precision, Recall, F1-score
  - Confusion Matrix
  - ROC AUC Score

## 📈 Results
The best model (XGBoost and RandomForest) achieved:
- High recall and F1-score 

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/masmur71/CustomerChurn.git
   
