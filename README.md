# 💳 Credit Card Fraud Detection using Machine Learning

This project focuses on detecting fraudulent credit card transactions using machine learning classification models, SMOTE for handling class imbalance, and a neural network for performance comparison. The model is trained on an anonymized dataset containing real-world transactions.

---

## 🧠 Models Used

- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Support Vector Machine (SVM)  
- Decision Tree  
- Random Forest  
- Neural Network (MLPClassifier)  
- SMOTE for class balancing

---

## 📦 Dataset

- Source: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- Contains **284,807 transactions**  
- Features: 30 (anonymized via PCA) + `Amount` + `Time`  
- Target variable: `Class` (0 = Non-Fraud, 1 = Fraud)

---

## ⚙️ Workflow

1. Data loading and preprocessing  
2. Feature scaling with `StandardScaler`  
3. Train-test split with stratification  
4. Class balancing using **SMOTE**  
5. Training classification models  
6. Neural network training with `MLPClassifier`  
7. Model evaluation using:
   - Accuracy
   - Precision
   - Recall
   - F1 Score
   - Confusion Matrix
8. Visualization of model comparisons

---

## 📊 Evaluation Metrics

Each model is evaluated on:

- ✅ Accuracy  
- ✅ Precision  
- ✅ Recall  
- ✅ F1 Score  
- ✅ Confusion Matrix  

Bar plots visualize the performance across all models.

---

## 💡 How to Run

1. Clone the repository:
```bash
git clone https://github.com/Lipiika/credit-card-fraud-detection.git
