# 🚨 Credit Card Fraud Detection

## 📌 Project Overview
This project is a Machine Learning model built to detect fraudulent credit card transactions. Financial fraud data is highly imbalanced, so this project specifically focuses on handling class imbalance using data sampling techniques to improve fraud detection rates.

## 🛠️ Tech Stack & Tools
* **Language:** Python
* **Environment:** Jupyter Notebook
* **Libraries:** Pandas, Matplotlib, Seaborn, Scikit-Learn, Imbalanced-Learn (SMOTE)

## 💡 Key Highlights & Concepts Covered
1. **Data Preprocessing:** Handled missing values and anonymized data (V1-V28 features).
2. **Handling Class Imbalance:** Used **SMOTE** (Synthetic Minority Over-sampling Technique) to balance the dataset (originally ~284k normal vs 492 fraud transactions).
3. **Model Training:** Built a classification model using **Logistic Regression**.
4. **Model Evaluation:** Evaluated using Confusion Matrix, Precision, and a significantly improved **Recall** score for fraud detection.
5. **Live Alert System:** Created a custom Python function to simulate a real-time transaction scan (Red Alert for fraud, Green for safe).

## 🚀 How to Run
1. Clone this repository.
2. Ensure you have the `creditcard.csv` dataset in the same directory.
3. Open `Financial_Fraud_Detection.ipynb` in Jupyter Notebook.
4. Run all cells to see the data visualizations and model results.
