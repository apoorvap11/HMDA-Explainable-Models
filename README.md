# HMDA-Explainable-Models

HMDA Explainable Models – Responsible Machine Learning (GWU)

This repository contains my implementation of Assignment 1 for the GWU Responsible Machine Learning course.  
The project trains and evaluates multiple **explainable machine learning models** on the HMDA mortgage dataset.

---

## 📂 Project Structure

---

## 📊 Models Trained
The assignment requires at least two explainable models. I included:

- **Elastic Net Logistic Regression (h2o)**
- **Explainable Boosting Machine (EBM, interpret)**
- **Monotonic Gradient Boosting Machine (XGBoost)**

Each model outputs a CSV with **one column named `phat`**, representing the predicted probability that a mortgage is *high-priced*.

---

## ▶️ How to Run the Notebook

1. Download the provided HMDA data:
   - `hmda_train_preprocessed.zip`
   - `hmda_test_preprocessed.zip`

2. Place them in the `data/` folder.

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
