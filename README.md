# Task 2: Credit Card Fraud Detection 💳

This repository contains the solution for **Task 2: Credit Card Fraud Detection** completed as part of the Machine Learning Virtual Internship at **CodSoft**[cite: 7, 12].

---

## 📌 Project Overview
The goal of this project is to build a Machine Learning model to identify fraudulent credit card transactions and distinguish them from legitimate ones[cite: 12].

Algorithms explored and evaluated:
- **Logistic Regression**[cite: 12]
- **Decision Tree Classifier**[cite: 12]
- **Random Forest Classifier**[cite: 12]

---

## ⚙️ Workflow & Steps
1. **Data Loading & Preprocessing:** Handling missing/duplicate entries, feature scaling (`StandardScaler`), and stratified train-test splitting (`test_size=0.2`, `random_state=42`).
2. **Handling Class Imbalance:** Fraudulent transactions represent a tiny fraction of total transactions, so imbalance-aware training and evaluation metrics are emphasized.
3. **Model Training & Comparison:** Training and evaluating classifiers on transaction features.
4. **Evaluation Metrics:** Tracking **Accuracy**, **Precision**, **Recall**, **F1-Score**, **ROC-AUC Score**, and **Confusion Matrix**.
5. **Visualizations Generated:**
   - Class imbalance chart (Legitimate vs. Fraudulent transactions).
   - Confusion matrix heatmaps.
   - Model metrics comparison chart.
   - ROC / Precision-Recall curve and feature importance chart.
6. **Custom Transaction Prediction:** Helper function to predict whether a transaction is legitimate or fraudulent along with confidence/probability.

---

## 💡 Key Takeaways & Conclusion
1. **Beyond Accuracy:** Because fraudulent cases are rare, high accuracy alone can be misleading; **Precision**, **Recall**, **F1-Score**, and **ROC-AUC** give a much clearer picture of fraud detection performance.
2. **Model Trade-offs:** Ensemble and tree-based models (such as Random Forest) capture non-linear patterns effectively, while tuning decision thresholds or class weights helps balance catching fraud (Recall) against false alarms (Precision).
3. **Future Improvements:** Exploring anomaly detection, cost-sensitive thresholds, or cross-validation can further improve reliability on real-world transaction streams.

---

## 🚀 How to Run (Google Colab)
1. Open the Task 2 `.ipynb` notebook in Google Colab.
2. Upload `creditcard.csv` (or set its Google Drive path).
3. Run all cells sequentially to view metrics, charts, and the conclusion.

---
*Created for CodSoft Machine Learning Internship (#codsoft)*[cite: 7, 8]
