# Spam Mail Prediction using Machine Learning

## 📌 Overview

This project builds a machine learning model to classify messages as **Spam** or **Ham (Not Spam)**.

It uses **Natural Language Processing (NLP)** techniques such as **TF-IDF vectorization** along with a **Logistic Regression model** to perform text classification.

---

## 🎯 Objective

The goal of this project is to automatically detect whether a given message is spam or not based on its text content.

---

## 📂 Dataset

The dataset contains two columns:

* **Category** → Label (`spam` or `ham`)
* **Message** → Text content of the message

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

---

## ⚙️ Machine Learning Workflow

1. Data Cleaning and Preprocessing
2. Label Encoding (spam → 0, ham → 1)
3. Train-Test Split
4. Feature Extraction using TF-IDF
5. Model Training (Logistic Regression)
6. Model Evaluation

---

## 📊 Evaluation Metrics

* Accuracy
* Confusion Matrix
* Precision, Recall, F1-score

---

## 📈 Results

The model performs well in distinguishing spam and non-spam messages, showing high accuracy on both training and test data.

---

## 🔍 Example Prediction

Input message:

```text
Congratulations! You have won a free prize. Call now!
```

Output:

```text
Spam
```


Your Name
