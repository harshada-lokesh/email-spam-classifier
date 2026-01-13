# 📧 Email Spam Classification

This repository contains a Machine Learning solution to identify and filter spam emails using **Logistic Regression**. The model is trained on the SMS/Email Spam Collection dataset to distinguish between legitimate messages ("NOT SPAM") and "SPAM."

## 🤖 Model Approach
The project implements a classic NLP pipeline to transform raw text into numerical data for classification.

* **Text Preprocessing:** Lowercasing, removal of stop words, and punctuation handling.
* **Vectorization:** Implemented **TF-IDF (Term Frequency-Inverse Document Frequency)** to convert text into a matrix of feature importance.
* **Algorithm:** **Logistic Regression** was chosen for its efficiency and high interpretability in high-dimensional binary classification tasks.

## 📊 Results
The model was evaluated using a standard 80/20 train-test split.

| Metric | Score |
| :--- | :--- |
| **Accuracy** | 95.65% |
| **Precision** | 88% |
| **Recall** | 98% |

### The Confusion Matrix:
<p align="left">
  <img src="results/confusion-matrix.png" width="300" alt="Centered image">
</p>

### The Model Prediction:
<p align="left">
  <img src="results/model-result.png" width="600" alt="Centered image">
</p>

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Scikit-Learn, Pandas, NumPy, NLTK, Seaborn, Mathplotlib
* **Workflow:** Jupyter Notebook in Kaggle

## 📁 Project Structure
```text
├── dataset.md            # Dataset from Kaggle
├── notebook/
│   └── email_spam_classification_model.ipynb    # Data cleaning, EDA, and Model
├── results/
│   └── confusion-matrix.png
│   └── model-result.png
│   └── metrics-result.png
├── .gitignore               # To ignore large data files
└── README.md
