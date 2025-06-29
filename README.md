# 🎓 College Acceptance Predictor 

A Linear Regression ML Project

This is a beginner-friendly machine learning project I built to predict a student’s **chance of acceptance** into a U.S. university for master's or higher studies. The idea came from how difficult it can be to manually explore university options, especially when students might miss better opportunities that they actually qualify for.

Using a dataset of past admissions, I trained a **linear regression model** that takes in basic profile inputs like GRE score, TOEFL score, CGPA, etc., and predicts the likelihood of admission. Based on this, it even gives a rough suggestion of colleges you can target.

---

## 📌 What This Project Does

- Predicts **Chance of Acceptance** using Linear Regression
- Takes inputs like GRE score, TOEFL score, CGPA, Research, etc.
- Evaluates model using MSE and R² score
- Provides **college recommendation tiers** based on your predicted score
- Shows a scatter plot of actual vs predicted values
- Uses techniques I learned in the Supervised Machine Learning: Regression and Classification (https://www.coursera.org/learn/machine-learning) course by DeepLearning.AI

---

## 📁 Dataset

Source: Graduate Admissions Dataset – Kaggle (https://www.kaggle.com/datasets/mohansacharya/graduate-admissions)

Features used:
- GRE Score
- TOEFL Score
- University Rating
- CGPA
- Research Experience  

Target variable: 
- **Chance of Admit**

---

## 🧠 Libraries Used

- `pandas` – data handling  
- `seaborn`, `matplotlib.pyplot` – visualization  
- `sklearn` – model training and evaluation  

---

## 📊 Model Performance

| Metric        		| Value    |
|-------------------------------|----------|
| Mean Squared Error (MSE) 	| `0.0050` |
| R² Score               	| `0.8046` |

The model performs well and explains over 80% of the variation in admissions based on the input features.

---

## 🔎 Sample Prediction

### Input:
[300, 100, 3, 8.0, 1]  # GRE, TOEFL, Univ Rating, CGPA, Research

### Output:
Predicted chance of admit: 65.42%
Suggested college tier: SUNY Buffalo, UIC, ASU

