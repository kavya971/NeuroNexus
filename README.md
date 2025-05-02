# NeuroNexus
# 💳 Credit Card Fraud Detection

This project uses machine learning techniques to predict fraudulent transactions in credit card datasets. The dataset contains real-world credit card transactions, where the goal is to predict whether a transaction is fraudulent or not.

## 📂 Source
**Dataset**: [Kaggle - Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)


- The `Class` column indicates whether a transaction is fraudulent (1) or not (0).

## 🔧 Technologies Used
- **Python**: 
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
- **Machine Learning**:
  - XGBoost
  - Scikit-learn
  - Imbalanced-learn (SMOTE for class balancing)
- **Environment**:
  - Google Colab

## 📊 Project Workflow

### 1. Data Preprocessing
- Checked for **null values** and handled missing data.
- Scaled the **Amount** feature using **StandardScaler**.
- Dropped irrelevant features.

### 2. Class Imbalance Handling
- Used **SMOTE (Synthetic Minority Oversampling Technique)** to balance the dataset.

### 3. Modeling
- Applied **XGBoost Classifier** for predicting fraud.
- Evaluated model performance using:
  - **Confusion Matrix**
  - **Classification Report**
  - **ROC Curve**

### 4. Evaluation
- Compared model performance **before and after SMOTE**:
  - **Accuracy** remained high due to class imbalance.
  - **Recall** and **F1-score** showed significant improvement after applying SMOTE.

## 📈 Results
- The **XGBoost model** performed well with a **high F1-score** and **recall** after SMOTE.
- Despite improvements, class imbalance remains a challenge, but the model is better at detecting fraud.


 ## 📌 How to Use

1. **Clone this repo**:
   ```bash
   git clone https://github.com/kavya971/NeuroNexus.git
