# ML Pipeline Practice

## 📌 Overview

This repository demonstrates the difference between a traditional machine learning workflow and using a Pipeline approach in sklearn.

The goal is to understand how pipelines simplify preprocessing and model building while making the workflow more reliable and production-ready.

---

## 📂 Files Included

### 1. Predict_Without_pipeline.ipynb

* Manual machine learning workflow
* Separate steps for:

  * Handling missing values
  * Encoding categorical data
  * Feature scaling
* More complex and error-prone process

---

### 2. Predict_With_Pipeline.ipynb

* Uses sklearn Pipeline
* Combines preprocessing and model into a single flow
* Cleaner, more efficient, and reusable code
* Helps prevent data leakage

---

## ⚖️ Key Comparison

| Feature          | Without Pipeline | With Pipeline |
| ---------------- | ---------------- | ------------- |
| Code Structure   | Scattered        | Organized     |
| Preprocessing    | Manual           | Automated     |
| Reusability      | Low              | High          |
| Risk of Error    | High             | Low           |
| Production Ready | ❌                | ✅             |

---

## 🧠 What I Learned

* Pipelines simplify machine learning workflows
* They ensure consistent preprocessing during training and testing
* Reduce chances of data leakage
* Improve code readability and maintainability

---

## 🎯 Purpose

This is a practice project created to strengthen my understanding of machine learning pipelines and their importance in real-world applications.

---

## 🚀 Future Improvements

* Add more models inside pipeline
* Hyperparameter tuning with GridSearchCV
* Deploy model using Flask / Streamlit
* Convert notebook into production-ready code

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Google Colab Notebook

---

## 📌 Note

This is a learning-based repository, not a full production project.
