# 💳 Credit Card Fraud Detection using Machine Learning

An end-to-end Machine Learning project designed to detect fraudulent credit card transactions using Python and Random Forest Classifier.

---

## 📊 Dataset Information
* **Total Transactions:** 284,807 records[cite: 4]
* **Features:** 31 numerical features (including Time, Amount, V1-V28 PCA transformed variables, and the target Class)[cite: 4].
* **Class Distribution:** 
  * Legitimate Transactions (Class 0): ~99.83%[cite: 4]
  * Fraudulent Transactions (Class 1): ~0.17% (Highly Imbalanced Dataset)[cite: 4]

---

## 🛠️ Tech & Skills
* **Programming & Core:** Python, Pandas, NumPy[cite: 4]
* **Data Visualization:** Matplotlib, Seaborn[cite: 4]
* **Machine Learning:** Scikit-learn (RandomForestClassifier, Train-Test Split, Metrics)[cite: 4]

---

## 🚀 Project Workflow
1. **Data Loading & Exploration:** Inspected dataset dimensions, data types, and checked for missing values.
2. **Exploratory Data Analysis (EDA):** Visualized the class imbalance using count plots to understand the distribution of fraud vs. non-fraud transactions.
3. **Model Training:** Split the dataset (80% train, 20% test) and trained a **Random Forest Classifier** (`n_estimators=100`)[cite: 4].
4. **Evaluation:** Evaluated model performance using Accuracy, Classification Report (Precision, Recall, F1-Score), and Confusion Matrix.
5. **Feature Importance:** Extracted and visualized the top features contributing to the model's predictive decisions (such as V17, V12, V14).

---

## 📈 Results & Performance
* **Accuracy:** ~99.95%[cite: 4]
* **Classification Report:** Achieved high precision and a strong balance in detecting rare fraudulent patterns despite extreme class imbalance.

---

## ⚙️ How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/amrfayad/credit-card-fraud-detection.git](https://github.com/amrfayad/credit-card-fraud-detection.git)
