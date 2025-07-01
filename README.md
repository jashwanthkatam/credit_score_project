# 💳 Credit Score Classification

> 🧠 A Machine Learning project to predict a person’s credit score bracket based on financial and behavioral data.

---

## 📘 Project Overview

You’re a data scientist at a global finance company that has collected years' worth of customer data.
The goal? To build an **intelligent credit scoring system** that classifies users into various **credit score categories** — automating what is currently a manual, time-consuming process.

This project applies **data preprocessing**, **feature engineering**, and multiple **machine learning models** to predict credit scores with increasing accuracy.

---

## 📊 Dataset Information

🔗 [Kaggle Dataset](https://www.kaggle.com/datasets/parisrohan/credit-score-classification)

* **Size:** 100,000+ records
* **Features:** 28 columns including user financial history, demographic info, and credit details
* **Target:** Credit score classification into meaningful risk brackets

🧾 **Dataset Columns Overview:**

* `ID`: Unique identifiers for users and movies
* `Rating`: User-generated ratings
* `Genre`: Category of movies (applicable in your Netflix project, but for this one should be credit-related fields like "Credit Utilization", "Outstanding Debt", etc.)

---

## 🧰 Project Workflow

### 🔹 1. Importing Libraries

Essential libraries like:

* `pandas`, `numpy` for data handling
* `matplotlib`, `seaborn` for visualization
* `sklearn` for model building

### 🔹 2. Handling Missing Values

* Replace special characters
* Convert string values to `int`/`float`
* Use **forward-fill** and **backward-fill** strategies to impute missing data

### 🔹 3. Data Cleaning

* Handled null values & invalid entries
* Categorical encoding (One-Hot Encoding)
* Removed outliers (especially from `Age`)

### 🔹 4. Feature Engineering

* **VIF (Variance Inflation Factor):** Checked for multicollinearity
* Selected all features with VIF < 5 ✅

---

## 🧠 Models and Evaluation

### 🔸 Logistic Regression

* 📈 Accuracy: **61.8%**

### 🔸 Decision Tree

* 📈 Accuracy: **69.7%**

### 🔸 Hyperparameter Tuning (GridSearchCV)

* 🌳 Tuned Decision Tree
* 📈 Accuracy: **70.93%**

### 🔸 Random Forest Classifier

* 🌲 Ensemble learning
* 📈 Accuracy: **79.7%** ✅

---

## 📌 Key Insights

* Data preprocessing significantly improved model performance
* Random Forest outperformed all other models in accuracy
* Proper handling of missing values and categorical encoding was critical to success

---

## 🎯 Future Improvements

* Test on live financial data
* Implement real-time credit risk scoring
* Integrate with APIs for automated finance approvals

---

## 🙌 Contributions

Feel free to fork the repo, submit pull requests, or suggest improvements! Let’s build smarter finance systems together. 💼📈

---

Let me know if you'd like a `README.md` file version ready to copy-paste or want to add sections like:

* 🧪 Jupyter Notebook preview link
* 💡 Business Use Case Summary
* 🐍 Python version & requirements
  
