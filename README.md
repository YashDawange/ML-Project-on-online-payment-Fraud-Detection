# 💳 Online Payment Fraud Detection using Machine Learning

This project aims to detect fraudulent online payment transactions using machine learning techniques. By analyzing transaction data, the model classifies whether a transaction is genuine or fraudulent, helping mitigate financial losses and enhance security.

## 📁 Project Files

- `Online Payment fraud detection Project.ipynb` – Complete Jupyter Notebook with data preprocessing, model training, evaluation, and visualization.

## 📊 Dataset Overview

The dataset includes features related to online transactions such as:
- Step (time step)
- Amount
- Transaction type
- Old and new balances for origin and destination accounts
- isFraud (target label)

## ⚙️ Workflow

1. **Data Preprocessing**
   - Handled class imbalance using SMOTE (Synthetic Minority Over-sampling Technique)
   - Converted categorical variables using encoding techniques

2. **Exploratory Data Analysis (EDA)**
   - Visualized fraud vs. non-fraud patterns using Seaborn and Matplotlib

3. **Model Training**
   - Evaluated multiple classification algorithms including:
     - Logistic Regression
     - Decision Tree
     - Random Forest
   - Used metrics such as Accuracy, Precision, Recall, F1-score, and Confusion Matrix

4. **Fraud Detection Insight**
   - Focused on minimizing false negatives (frauds classified as non-frauds)
   - Final model demonstrated effective detection performance

## 📦 Technologies Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn

## 📈 Key Results

- Achieved high precision and recall in identifying fraudulent transactions
- Visual insights showed clear separability between fraud and non-fraud classes

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/YashDawange/online-payment-fraud-detection.git
   cd online-payment-fraud-detection
