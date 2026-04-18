# Assignment 14: Ethical AI Analysis and Explainability

## 📌 Overview

This project focuses on building a machine learning model while ensuring **fairness, transparency, and ethical decision-making**.

The goal is to:

* Train a classification model
* Evaluate its performance
* Analyze fairness across different groups
* Interpret model decisions using explainability tools

---

## 📊 Dataset

A sample loan dataset was used for this project.

**Features include:**

* Gender (Sensitive Attribute)
* Income
* Loan Amount
* Credit History

**Target Variable:**

* Loan_Status (Approved = 1, Not Approved = 0)

---

## ⚙️ Technologies Used

* Python
* Pandas & NumPy
* Scikit-learn
* Fairlearn
* SHAP
* LIME
* Matplotlib

---

## 🚀 Project Workflow

### 1. Data Preprocessing

* Loaded dataset into Pandas DataFrame
* Encoded categorical variables
* Selected features (X) and target (y)
* Identified **Gender** as the sensitive feature

---

### 2. Model Training

* Split data into training and testing sets
* Trained a **Logistic Regression** model

---

### 3. Model Evaluation

* Accuracy Score
* Confusion Matrix
* Classification Report

---

### 4. Fairness Analysis

Fairness metrics were calculated using **Fairlearn**:

* Selection Rate
* False Positive Rate
* True Positive Rate

A **MetricFrame** was used to compare performance across gender groups.
Bar charts were used for visualization.

---

### 5. Explainability

#### 🔹 SHAP (Global + Local)

* Summary plot for feature importance
* Waterfall plot for individual predictions

#### 🔹 LIME (Local Explanation)

* Explained individual predictions
* Highlighted feature contributions

---

## 📈 Key Insights

* The model achieved good accuracy but showed slight differences across gender groups
* This indicates potential bias in predictions
* Explainability tools revealed which features influenced decisions the most

---

## ⚖️ Ethical Considerations

* Use of sensitive attributes (e.g., Gender) may introduce bias
* Models should be monitored to prevent unfair outcomes
* Techniques like fairness constraints and feature selection can improve fairness

---

## 🧠 Conclusion

This project demonstrates that:

* High accuracy does not guarantee fairness
* Fairness analysis is essential in real-world ML systems
* Explainability tools improve trust and transparency

---

## 📂 How to Run

1. Open the notebook in Google Colab
2. Install required libraries:

   ```bash
   pip install fairlearn lime shap
   ```
3. Run all cells step-by-step

---

## 👤 Author

**Henry Falaiye**
Email: [henry.falaiye@students.williscollege.com](mailto:henry.falaiye@students.williscollege.com)
GitHub: https://github.com/HenryFalaiye
