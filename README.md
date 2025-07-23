# 🏠 Home Credit Default Risk — Decision Tree Classifier

This project predicts the probability that a customer will **default on a loan**, using the **Home Credit Default Risk** dataset from Kaggle.  
It uses a **Decision Tree Classifier** for maximum interpretability so stakeholders can understand how predictions are made.

---

## 📌 Project Overview

**Goal:**  
Help Home Credit responsibly extend loans to more customers while minimizing risk.  
This project uses:
- The main application dataset (`application_train.csv`)
- Multiple external tables:
  - `bureau.csv`
  - `bureau_balance.csv`
  - `previous_application.csv`
  - `POS_CASH_balance.csv`
  - `credit_card_balance.csv`
  - `installments_payments.csv`

**Key steps:**  
- Loaded and merged raw data files.
- Aggregated external tables for richer features.
- Engineered new features (income ratios, worst credit status, rejection rates).
- Handled class imbalance with random under-sampling.
- Trained and evaluated a **Decision Tree Classifier**.
- Visualized the decision tree and evaluation metrics.
- Deployed a simple **Flask web demo** to make predictions interactively.

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/zain31197/home-credit-default-risk.git
cd home-credit-default-risk.git
## 📥 Download the Dataset

> ⚠️ **Note:** Raw Kaggle data files are **NOT included** in this repository because they exceed GitHub's size limits.  
> Please [accept the competition rules](https://www.kaggle.com/competitions/home-credit-default-risk/data) on Kaggle and download the following files:

- `application_train.csv`
- `bureau.csv`
- `bureau_balance.csv`
- `previous_application.csv`
- `POS_CASH_balance.csv`
- `credit_card_balance.csv`
- `installments_payments.csv`

Place all these files inside the `data/` folder at the project root.

---

## 🚀 How to Run the Project

### ✅ 1️⃣ Train the Model

To retrain the **Decision Tree** from scratch:

1. Open the Jupyter Notebooks in the `notebooks/` folder:

2. The final trained model will be saved as **`loan_default_model_DTC.pkl`**.

A **pre-trained model file** is already provided for convenience.

## 📌 Notes

- Please accept the competition rules on Kaggle **before using the data**.

---

## 👥 Project Team

**Group Members:**  
- Abdullah Ahmad — 25-0275-I  
- Muhammad Ali Reza — 25-0626-I  
- Zain Shahid — 25-0384-I
