# Logistic Regression Binary Classification

This project implements a **Logistic Regression** model for binary classification using the **Heart Disease UCI Dataset** from Kaggle.

The notebook includes:
- Data upload and preprocessing
- Train-test split and feature standardization
- Logistic Regression model training
- Evaluation using **Confusion Matrix**, **Classification Report**, **ROC-AUC Score**, and **ROC Curve**

---

## 📂 Dataset

We use the **Heart Disease UCI Dataset**:
- **Source**: [Kaggle - Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)
- **Target column**: `target`  
  - `0` → No heart disease  
  - `1` → Heart disease present

The dataset is already included in this repository as `heart.csv`.

---

## 🚀 How to Run the Code

You can run this project on **Google Colab** without installing anything locally.

### 1️⃣ Open Google Colab
Go to [Google Colab](https://colab.research.google.com/).

### 2️⃣ Upload the Code
1. Upload the Python notebook (`logistic_regression.ipynb`) or paste the code from `logistic_regression.py` into a Colab cell.
2. Also upload the dataset file `heart.csv` from this repository.

### 3️⃣ Run the Code
The code will:
- Load the dataset
- Train a Logistic Regression model
- Output evaluation metrics
- Plot the ROC curve
