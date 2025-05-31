# 📰 Detecting Fake News with Python and Machine Learning

This project is a machine learning-based fake news detector that uses Natural Language Processing (NLP) to classify news articles as **FAKE** or **REAL**. It uses a **Passive Aggressive Classifier** along with **TF-IDF Vectorization** for efficient text classification.

---

## 📂 Dataset

- **Source**: [Kaggle - Fake and Real News Dataset](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)
- **License**: CC-BY-NC-SA-4.0
- Contains two CSV files: `Fake.csv` and `True.csv`

---

## ✅ Features

- Preprocesses and combines real and fake news articles.
- Converts text data into numeric features using **TF-IDF**.
- Classifies using **Passive Aggressive Classifier**.
- Shows performance with **accuracy** and **confusion matrix**.

---

## 🛠️ Technologies Used

| Tool/Library             | Purpose                               |
|--------------------------|----------------------------------------|
| `Python`                 | Core programming language              |
| `pandas`                 | Data loading and manipulation          |
| `scikit-learn (sklearn)` | Machine learning pipeline              |
| `TfidfVectorizer`        | Text vectorization using TF-IDF        |
| `PassiveAggressiveClassifier` | Classification model           |
| `train_test_split`       | Splitting training and testing sets    |
| `accuracy_score`, `confusion_matrix` | Evaluation metrics         |

---

## 📊 Model Performance

- **Model**: Passive Aggressive Classifier
- **TF-IDF Vectorizer**: max_df=0.7, stop_words='english'
- **Train-Test Split**: 80% training, 20% testing

### 📈 Accuracy Achieved: `99.51%`

### 🧮 Confusion Matrix:
Actual FAKE 4679 21
Actual REAL 23 4257

