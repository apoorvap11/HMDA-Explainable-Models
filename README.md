# HMDA-Explainable-Models


# HMDA Explainable Machine Learning Models  
### Responsible & Interpretable ML • Model Explainability • Bias Detection

This project demonstrates my ability to build **explainable, responsible machine learning models** using the Home Mortgage Disclosure Act (HMDA) dataset. The focus is on creating **transparent, interpretable models** that can be validated, monitored, and audited — skills that are increasingly required for data science, analytics, and ML roles.

This repository was originally part of a graduate-level project at The George Washington University, and has been refined and published to my GitHub portfolio to showcase my work.

---

##  Key Skills Demonstrated

- **Explainable Machine Learning (XAI)**
- **Responsible & Fair ML Practices**
- **Model validation, early stopping & reproducibility**
- **Hyperparameter tuning & cross-validation**
- **XGBoost (monotonic constraints)**
- **Explainable Boosting Machines (EBM)**
- **Elastic Net Logistic Regression (h2o)**
- **Feature understanding & exploration**
- **Probability scoring for production ML workflows**
- **End-to-end ML pipeline: data → model → evaluation → scoring**

---

##  Project Overview

Mortgage pricing decisions in the U.S. have long been tied to fairness and regulatory scrutiny.  
In this project, I:

1. **Trained multiple explainable ML models**  
2. **Compared model performance & interpretability**
3. **Generated probability scores (`phat`) for unseen test data**
4. Focused on transparency over black-box performance

The target variable is **whether a mortgage is considered high-priced**, a key financial and fairness outcome for borrowers.

---

##  Tools & Technologies

- **Python**
- **h2o**
- **XGBoost**
- **InterpretML (EBM)**
- **Pandas, NumPy**
- **Jupyter Notebook**

---

##  Repository Structure

---

##  Models Trained

### **1. Elastic Net Logistic Regression (h2o)**
- Fully interpretable coefficients  
- Strong baseline model  

### **2. Explainable Boosting Machine (EBM)**
- Highly transparent additive model  
- Handles nonlinearities while staying interpretable  

### **3. Monotonic Gradient Boosting (XGBoost)**
- Ensures monotonicity on key features  
- More flexible while still constrained for explainability  

All models produce a `phat` score — the predicted probability that a loan is high-priced.

---

## How to Run

1. Install dependencies:

```bash
jupyter notebook hmda_explainable_models.ipynb

pip install -r requirements.txt





