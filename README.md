# SMS-spam-filtering-based-on-character-n-gram-models
SMS spam classifier using character n-gram features and machine learning models.
# 📱 SMS Spam Filtering using Character n-Gram Models

This project implements a spam classifier for SMS messages using **character-level n-gram features** and traditional machine learning models. It achieves **91.13% accuracy**, with a precision of **96.70%** and an F1-score of **91.09%**.

---

## 📌 Overview

- Dataset: SMS Spam Collection Dataset (UCI)
- Feature extraction: Character-level n-grams
- Model: Naive Bayes / Logistic Regression
- Vectorizer: TfidfVectorizer (with char n-grams)
- Evaluation: Precision, Recall, F1-score, Confusion Matrix

---

## 🧰 Technologies Used

- Python
- scikit-learn
- pandas
- NumPy
- matplotlib, seaborn

---

## 📂 Folder Structure

| Folder       | Contents                                 |
|--------------|------------------------------------------|
| `src/`       | Preprocessing, training, evaluation code |
| `models/`    | Saved model `.pkl` file                  |
| `data/`      | Dataset (or source link)                 |
| `results/`   | Output visuals: confusion matrix, charts |
| `notebooks/` | EDA + training demo notebook             |

---

## 🧪 Model Performance

| Metric     | Value     |
|------------|-----------|
| Accuracy   | 91.13%    |
| Precision  | 96.71%    |
| Recall     | 85.15%    |
| F1-Score   | 91.09%    |
