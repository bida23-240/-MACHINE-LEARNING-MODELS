# MACHINE LEARNING MODELS
Predicting Depression Using Machine Learning (Logistic Regression, SVM, Random Forest)
The repository contains Python scripts for predicting depression using three different machine learning models:
- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest Classifier

These models were trained and evaluated using a cleaned Excel dataset with features such as sleep hours, diet, family history, and suicidal thoughts.

---

## 📂 Files

| File Name              | Description                                 |
|------------------------|---------------------------------------------|
| `logistic_regression.py` | Trains and evaluates a Logistic Regression model |
| `svm.py`                 | Trains and evaluates a Support Vector Machine model |
| `random_forest.py`       | Trains and evaluates a Random Forest model       |
| `Cleaned Depression Professional Dataset.xlsx` | Dataset used for training and evaluation |

---

## ⚙️ Requirements

- Python 3.8 or above
- Required Python libraries:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`
  - `openpyxl`
    

# 🧠 Predicting Depression Using Machine Learning

## 📘 Project Overview
This project applies three machine learning models to predict depression using a cleaned Excel dataset. It includes:

- **Support Vector Machine (SVM)**
- **Logistic Regression**
- **Random Forest**

## 📁 Dataset
Make sure the Excel file `Cleaned Depression Professional Dataset.xlsx` is available in your working directory. Update the path inside each script if needed.

---

## 📦 Installation

Use the command below to install all required libraries:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn openpyxl
```

---

## 🛠️ Operating Instructions

### A. Setup

1. Place all Python scripts (`svm.py`, `logistic_regression.py`, `random_forest.py`) in the same folder.
2. Ensure the dataset file path in each script is correct.

> Example path format (Windows):
```python
r"C:\Users\YourName\Documents\Cleaned Depression Professional Dataset.xlsx"
```

### B. Run the Code

Open a terminal/command prompt in the script folder and run the desired model:

```bash
python logistic_regression.py
```

Replace with `svm.py` or `random_forest.py` to run other models.

---

## 📊 Output Description

### Logistic Regression
- Accuracy score
- Confusion matrix
- ROC and precision-recall curves
- Feature importance

### SVM
- Classification report
- Confusion matrix
- Feature coefficients

### Random Forest
- Classification report
- Confusion matrix (heatmap)
- Class distribution pie chart
- Feature importance (graph + table)

---

## 📝 Notes

- All models use label encoding and feature scaling.
- Data is split into 80% training and 20% testing.
- If any error occurs, double-check the dataset file path and sheet name.

---

## 👨‍💻 Author
This project was created by BIDA23-7 Group D for a Research & Innovation assignment on predicting depression using machine learning.



