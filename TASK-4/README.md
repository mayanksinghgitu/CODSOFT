# Task 4 --- Spam SMS Detection – CODSOFT Internship

This project builds an AI/ML model that classifies SMS messages as **Spam** or **Legitimate (Ham)**.  
The main objective is to protect users from fraudulent or unwanted messages using Natural Language Processing (NLP) and Machine Learning.

---

## ✅ Project Overview
SMS spam filtering is widely used in messaging apps, email services, and telecom systems.  
This project uses machine learning on text data to automatically detect spam messages with high accuracy.

---

## ✅ Dataset Details
- **Dataset provided by:** CodSoft
- **Shape:** `(5169 rows × 2 columns)`
- **Final Columns Used:**
  - `label` → spam / ham classification
  - `message` → SMS text

The original dataset contained unused columns:
`v1, v2, Unnamed:2, Unnamed:3, Unnamed:4`  
These were cleaned and removed during preprocessing.

---

## ✅ Technologies Used

| Category | Tools |
|----------|-------|
| Language | Python |
| Notebook / IDE | Jupyter Notebook |
| Libraries | Pandas, NumPy, Scikit-Learn, Matplotlib |

---

## ✅ Data Preprocessing Steps
- Dropped unnecessary columns
- Renamed final two useful columns:  
  ✅ `label`  
  ✅ `message`
- Converted labels to numeric (`spam` / `ham`)
- Text cleaning: lowercasing, removing punctuation & special characters
- Split dataset into training & testing sets
- Text converted into numerical vectors using TF-IDF

---

## ✅ Machine Learning Model

✅ **Model Used:** `LinearSVC (Support Vector Classifier)`  
Reason: SVM performs very well on text classification because of high-dimensional sparse features from TF-IDF.

---

## ✅ Model Performance

| Metric | Score |
|--------|-------|
| ✅ Training Accuracy | **99.97%** |
| ✅ Testing Accuracy  | **98.25%** |

Confusion Matrix was generated and analyzed to check true positives, false positives, etc.  
The model achieved strong generalization and very low misclassification error.

---

## ✅ Output
- Input: SMS text
- Output:
  - `1` → Spam
  - `0` → Not Spam (Ham)

Example:
```
Message: "Congratulations! You won a prize!"
Prediction: Spam ✅
```

---

## ✅ Files in Repository
| File | Description |
|------|-------------|
| `spam_sms_detection.ipynb` | Full Jupyter Notebook code |
| `README.md` | Project documentation |
| Dataset (Not uploaded) | Provided by CodSoft |

---

## ✅ Conclusion
The Linear SVC model provides **high accuracy** for spam detection and can be used in real-time SMS filtering applications.  
With proper deployment, it can work inside messaging apps to block spam automatically.

---

## ✅ Future Improvements
- Try Naive Bayes or Logistic Regression for comparison
- Add word embeddings (Word2Vec / GloVe)
- Deploy via Flask or Streamlit web app
- Build real-time API for mobile integration

---

## ✅ Author
**Mayank Singh**  
CODSOFT Internship – Machine Learning Tasks
