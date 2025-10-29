✅ TASK–2: Fraudulent Credit Card Transaction Detection

README.md (Final Version)

# ✅ Task 2 — Credit Card Fraud Detection

This project builds a Machine Learning model to detect **fraudulent credit card transactions** using transaction-level data.  
The goal is to classify each transaction as **Legitimate (0)** or **Fraud (1)** with high accuracy.

---

## 📌 Dataset Information
- **Files Provided**  
  ✅ `fraudTrain.csv`  
  ✅ `fraudTest.csv`

- **Dataset size**  
  | File | Rows | Columns |
  |------|------|---------|
  | fraudTrain.csv | 1,296,675 | 23 |
  | fraudTest.csv | 555,719 | 22 |

- **Preprocessing Steps**
  ✅ Removed irrelevant/unwanted columns  
  ✅ Final selected **12 important features** for training  
  ✅ Checked for missing values  
  ✅ Encoded categorical data  
  ✅ Train-test split done properly  

---

## 🧠 Machine Learning Model Used
- ✅ **Random Forest Classifier**
- Reason:
  - Works well with large datasets
  - Handles imbalance
  - High accuracy & stability

---

## ✅ Final Accuracy Results

| Metric | Score |
|--------|-------|
| **Training Accuracy** | ✅ `99.74357532474836%` |
| **Testing Accuracy** | ✅ `99.74627510256964%` |

The model performs extremely well and generalizes successfully on unseen test data.

---

## 📊 Confusion Matrix
We calculated and analyzed the confusion matrix to understand:

- ✅ True Positives (Fraud correctly detected)  
- ✅ True Negatives (Legitimate correctly detected)  
- ✅ False Positives  
- ✅ False Negatives  

This helped verify that the model **detects fraud with high precision and recall**.

---

## 🛠️ Technologies Used
- Python
- Jupyter Notebook (`.ipynb`)
- Libraries:
  - Pandas
  - NumPy
  - Scikit-Learn
  - Matplotlib / Seaborn (for visualization)

---

## 📁 Project Files in This Task Folder


Task-2/
│── fraudTrain.csv
│── fraudTest.csv
│── credit_fraud_detection.ipynb (Jupyter notebook)
│── README.md


---

## ✅ Final Conclusion
✔ The Random Forest model successfully detects fraudulent credit card transactions  
✔ Highest accuracy above **99%**  
✔ Confusion matrix analysis confirms strong performance  
✔ Model can be deployed in real banking/transaction security systems

---

## 📌 Author
🧑‍💻 *Mayank Singh*  
Machine Learning & Python
