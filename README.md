#  Titanic Passenger Survival Prediction

# Project Overview

This project predicts whether a passenger would have survived the Titanic disaster using **Logistic Regression**. It demonstrates the complete machine learning workflow, from data preprocessing and exploratory data analysis to model training, evaluation, and building a predictive system.

---

# Dataset

* Dataset: Titanic - Machine Learning from Disaster
* Source: Kaggle
* Target Variable: Survived

  * 0 = Did Not Survive
  * 1 = Survived

---

# Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

# Project Workflow

# 1. Data Loading

* Loaded the Titanic dataset using Pandas.

# 2. Exploratory Data Analysis (EDA)

* Explored dataset structure.
* Checked data types.
* Identified missing values.
* Checked for duplicate records.
* Understood the meaning of each feature.

# 3. Data Preprocessing

* Filled missing values in the **Age** column using the median.
* Removed rows with missing **Embarked** values.
* Dropped unnecessary columns:

  * PassengerId
  * Name
  * Ticket
  * Cabin
* Encoded categorical features:

  * Sex
  * Embarked

# 4. Feature Selection

Selected relevant features based on data understanding and domain knowledge.

# 5. Train-Test Split

Split the dataset into training and testing sets.

# 6. Model Training

Trained a Logistic Regression classifier using Scikit-learn.

# 7. Model Evaluation

Training Accuracy: 81%

Testing Accuracy: 76%

# 8. Predictive System

Built a predictive system that accepts passenger details and predicts whether the passenger would have survived.

---

# Project Structure

text
titanic-passenger-survival-prediction/
│
├── Titanic_Passenger_Survival_Prediction.ipynb
├── train.csv
├── README.md
└── .gitignore


---

# Machine Learning Concepts Used

* Supervised Learning
* Binary Classification
* Logistic Regression
* Data Cleaning
* Missing Value Handling
* Feature Selection
* Categorical Encoding
* Train-Test Split
* Model Evaluation
* Predictive System

---

# Future Improvements

* Feature Engineering
* Feature Scaling
* One-Hot Encoding
* Decision Tree Classifier
* Random Forest Classifier
* Hyperparameter Tuning
* Cross Validation
* Confusion Matrix
* Classification Report
* Streamlit Web Application

---

# Learning Outcomes

Through this project, I learned how to work with a real-world dataset, perform data preprocessing, select relevant features, train a machine learning model, evaluate its performance, debug common machine learning issues, and build a predictive system using Logistic Regression.

---


