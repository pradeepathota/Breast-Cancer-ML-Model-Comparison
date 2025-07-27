# Breast Cancer Tumor Classification Using Machine Learning

This project implements and compares multiple machine learning algorithms to classify breast cancer tumors as malignant or benign. Using the Breast Cancer Wisconsin Diagnostic Dataset, the workflow includes data preprocessing, model training, evaluation using accuracy and AUC, and visual performance comparison through bar plots and ROC curves.

---
## 👨‍💻 Author

**Venkata Pradeep Kumar Athota**  
📧 pradeepathota3@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/pradeepathota)

---

## 🎯 Objective

To develop and evaluate supervised machine learning models for breast cancer tumor classification and compare their predictive performance using ROC-AUC and accuracy metrics.

---

## 📊 Dataset

- **Source**: `sklearn.datasets.load_breast_cancer()`
- **Samples**: 569
- **Features**: 30 numeric features describing tumor characteristics
- **Target**: Binary classification — 0 (malignant), 1 (benign)

---

## 🧰 Tools & Libraries

- Python
- scikit-learn
- pandas, numpy
- matplotlib

---

## 🔄 Workflow Overview

1. **Data Loading & Preprocessing**
   - Loaded dataset using `load_breast_cancer()` from `scikit-learn`
   - Scaled features using `StandardScaler` for normalization

2. **Model Training**
   - Trained 5 models using default hyperparameters:
     - Logistic Regression
     - K-Nearest Neighbors (KNN)
     - Support Vector Machine (SVM)
     - Decision Tree
     - Gradient Boosting

3. **Model Evaluation**
   - Evaluated models using:
     - **Accuracy**
     - **AUC (Area Under ROC Curve)**

4. **Visualization**
   - Bar plots for accuracy and AUC scores
   - ROC curve comparison for all models

---

## 📈 Results Summary

All models performed well, with **Gradient Boosting** and **SVM** showing strong AUC and accuracy. ROC curves provided visual insight into each model's ability to distinguish between malignant and benign tumors.

---

## 📌 Project Highlights

- Clean and scalable ML pipeline using scikit-learn
- Side-by-side model comparison with ROC curves
- Emphasis on interpretability and reproducibility

---

## 📂 Files

- `main.py` or `notebook.ipynb` – Full code for data processing, modeling, and evaluation
- `README.md` – Project documentation

---

## 📝 License

This project is open-source and for educational purposes only.
