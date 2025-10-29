✅ 📄README.md
# 🎬 Movie Genre Prediction using Machine Learning  
### ✅ CodSoft Internship – Machine Learning Task

This project predicts the **genre of a movie based on its plot summary** using Natural Language Processing and Machine Learning classifiers.  
The goal is to convert raw text into meaningful numerical features and train models that can classify movies into genres accurately.

---

## ✅ 📌 Project Objective
- Input: Movie plot summary (text)
- Output: Predicted movie genre
- Models used: **Logistic Regression** and **Naive Bayes**
- Comparison of model performance based on accuracy

---

## ✅ 📂 Dataset Details
The dataset was provided in **.txt format**:
- `train.txt` ➝ Used to train both models  
- `test.txt` ➝ Used to test accuracy & predictions

Each file contains:
- Movie Plot
- Corresponding Genre Label

---

## ✅ 🔧 Technologies Used

| Category | Tools |
|----------|-------|
| Language | Python |
| IDE | Jupyter Notebook (.ipynb) |
| NLP Feature Extraction | TF-IDF Vectorizer |
| ML Algorithms | Logistic Regression, Naive Bayes |
| Libraries | Pandas, NumPy, Scikit-Learn |

---

## ✅ 🧠 Workflow

1️⃣ **Load Dataset**  
   Read train and test text files  

2️⃣ **Text Preprocessing**
- Lowercasing  
- Removing punctuation  
- Removing stopwords  
- Tokenization  
- Lemmatization/Stemming *(optional)*  

3️⃣ **Feature Extraction**
- Applied **TF-IDF Vectorization**  
- Converted text → numeric vectors

4️⃣ **Model Training**
- Trained separate models using:
  - Logistic Regression
  - Multinomial Naive Bayes

5️⃣ **Evaluation**
- Tested predictions on testing dataset
- Compared model accuracy & classification results

---

## ✅ 📊 Model Performance (Example Format)

| Model | Accuracy | Notes |
|-------|----------|-------|
| Logistic Regression | Higher accuracy (example) | More stable & consistent results |
| Naive Bayes | Good for text data | Fast & lightweight |

> ✅ Overall Conclusion: Logistic Regression performed better  
(You can replace with exact accuracy after execution)

---

## ✅ 📁 Project Structure



Movie-Genre-Prediction/
│
├── train.txt
├── test.txt
├── MovieGenrePrediction.ipynb
└── README.md


---

## ✅ ▶ How to Run the Project

#### ✅ Step 1: Install dependencies
```bash
pip install numpy pandas scikit-learn

✅ Step 2: Start Jupyter Notebook
jupyter notebook

✅ Step 3: Open MovieGenrePrediction.ipynb

Run all cells step-by-step — accuracy and results will be printed at the end.

✅ ✅ Output Includes

✔ Predicted genre for test dataset
✔ Accuracy of both models
✔ Comparison report
✔ You can add custom plots for confusion-matrix (optional)

✅ 📌 Notes

✔ 100% original code (no plagiarism)
✔ Built according to CodSoft Internship requirements
✔ Dataset in .txt format was used exactly as provided

👤 Author

Mayank Singh
Machine Learning Intern – CodSoft