# Fraud Detection Model

This repository contains a machine learning model for detecting fraudulent transactions using a dataset (`Fraud.csv`). The project demonstrates **data preprocessing, visualization, model training and evaluation** in Python with Jupyter Notebook.

---

## 📂 Project Structure:

```
Fraud Detection/
│-- fraud_detection.ipynb   # Jupyter notebook with full workflow
│-- Fraud.csv               # Dataset (NOT included in repo, too large)
│-- .gitignore              # Ignores large files like datasets
```

---

## ⚙️ Setup Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/ananya1605/fraud-detection.git
   cd fraud-detection
   ```

2. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

3. Download the dataset (`vFraud.cs`) from the provided link (see below) and place it in the project folder.
   
---

## 📊 Model Workflow

* Data preprocessing and cleaning
* Exploratory Data Analysis (EDA)
* Feature engineering
* Model training and evaluation
* Precision@K evaluation for imbalanced classification

---

## 📥 Dataset Access

The dataset (`Fraud.csv`) is **not uploaded to GitHub** because of size limitations (>100MB).
👉 You can download it from this link: (https://www.kaggle.com/datasets/amanindiamuz/financial-dataset-for-fraud-detection-in-a-comapny)

Place the file in the root project folder before running the notebook.

---

## 🚀 Results

* Precision@1%: `0.0725`
* Precision@0.5%: `0.12`
* Precision@0.1%: `0.15`

---

## ✨ Future Improvements

* Try advanced ML models (XGBoost, LightGBM, Neural Networks)
* Use SMOTE or undersampling for better class balance
* Deploy the model as a web API

---

## 📝 Author

Developed by Ananya Rana
