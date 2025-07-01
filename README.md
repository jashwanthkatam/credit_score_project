💳 Credit Score Classification Project:


📊 Overview

Welcome! This project demonstrates how to build an intelligent credit score classification system for a global finance company.

Imagine you’re a data scientist at a large financial institution — 
you’ve got access to extensive customer bank details and credit-related data. The goal? 
➡️ Reduce manual work by automatically classifying customers into credit score brackets, enabling faster decisions and better risk management.


🗂️ Dataset

📌 Source: Kaggle Credit Score Dataset

Records: 100,000 entries across 28 features.

Features Include:

Unique IDs for customers and transactions

Credit scores

Bank details

Demographic information

![image](https://github.com/user-attachments/assets/d24ad6c9-3a61-4d93-98f5-557ec1d6c438)


⚙️ Steps & Methodology


1️⃣ Import Libraries
Essential libraries like pandas, numpy, matplotlib, and seaborn were imported to handle data and visualization tasks.


2️⃣ Data Cleaning 🧹
Removed special characters and replaced them with NaN values where appropriate.

Converted string fields to numeric types (int or float).

Filled missing values using forward-fill and backward-fill methods.

Removed outliers (e.g., for age) to maintain data integrity.

Applied One Hot Encoding to categorical variables.

![image](https://github.com/user-attachments/assets/301398bd-c8f9-42b2-995d-95363b886da5)


3️⃣ Feature Selection 🔍
✅ Used Variance Inflation Factor (VIF) to check for multicollinearity — ensuring VIF < 5 for selected features.
✅ Retained all relevant features based on these checks.

![image](https://github.com/user-attachments/assets/15faf05d-0d20-4310-8d9e-87ac8992b73d)


4️⃣ Model Building & Evaluation 🤖

Model	Accuracy
Logistic Regression	61.8%
Decision Tree	69.7%
Decision Tree (Hyperparameter Tuned)	70.9%
Random Forest	79.7%

![image](https://github.com/user-attachments/assets/ec7134bb-3298-4e87-83c5-2ca51e33e055)


Techniques Used:

Logistic Regression: Baseline model for binary classification.

Decision Tree: Improved interpretability with decent performance.

GridSearchCV: Hyperparameter tuning for optimal Decision Tree performance.

Random Forest: Achieved the highest accuracy, leveraging ensemble learning.



📈 Key Learnings


✅ Data cleaning and proper handling of missing values greatly improved model performance.
✅ Feature selection using VIF helped avoid multicollinearity.
✅ Ensemble methods like Random Forest provided significant accuracy improvements compared to single classifiers.

🚀 Future Improvements
✨ Test other advanced ensemble techniques like XGBoost or LightGBM.
✨ Deploy the model as an API for real-time credit score classification.
✨ Implement feature importance analysis to explain predictions to stakeholders.

🙌 Credits
Dataset by link: (https://www.kaggle.com/datasets/parisrohan/credit-score-classification)
Developed by Jashwanth Katam

Feel free to ⭐ this repo if you found it helpful!
Pull requests and suggestions are always welcome. 🤝
