![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange)

# 📊 TikTok Virality Project
Master IASD – M1 IDD – Machine Learning Project
Mayy Miled & Giuliano Aldarwish – May 2025
Supervisor: Pierre Wolinski

---

## 🧠 Objective

This project aims to predict the virality of TikTok videos using machine learning methods.  
The challenge is to design a consolidated dataset from two complementary sources, perform rigorous preprocessing and feature engineering, and compare a variety of classifiers, from simple models (LDA, Logistic Regression) to ensemble methods (Random Forest, XGBoost, Stacking).

---

## 🗂️ Folder Structure

```
TikTok_Virality_Project/
├── README.md                 ← You are here
├── MLProject.pdf             ← Main report (10+ pages)
│
├── data/
│   ├── meta_data.csv         ← Source dataset #1 (quantitative focus)
│   └── trending_converted.csv ← Source dataset #2 (qualitative + text)
│
├── notebooks/
│   ├── 1_preprocessing.ipynb ← Data preparation, feature engineering
│   └── 2_modeling.ipynb      ← Classification models and evaluation
```

---

## 🚀 How to Run the Code

Open and execute the notebooks in the following order:

1. `notebooks/1_preprocessing.ipynb`  
   - Loads and merges the two datasets
   - Constructs the final feature matrix
   - Defines the target variable `is_viral`

2. `notebooks/2_modeling.ipynb`  
   - Trains and evaluates multiple classification models
   - Displays cross-validation scores, confusion matrices, and ROC curves

All paths to the data files are relative to the `/data/` directory. Make sure this folder is present at the same level as the notebooks.
⚠️ Don’t forget to set the correct file paths at the beginning of the notebooks (to load the CSV files),
and at the end (if you save figures or results).
---

## 🛠️ Dependencies

This project uses the following Python libraries:

- `numpy`, `pandas`, `polars`
- `matplotlib`, `seaborn`
- `scikit-learn`, `xgboost`
- `warnings`, `copy`, `os`

You can install them via:

```bash
pip install -r requirements.txt
```

---

## 📄 Report

The report `MLProject.pdf` contains:

- A detailed description of the task and datasets
- Exploratory and preprocessing steps
- Feature engineering (TF-IDF, time variables, one-hot encoding...)
- Model comparisons (Logistic Regression, LDA/QDA, Trees, SVM, Stacking)
- Interpretation of results (ROC, confusion matrices, coefficients)
- A conclusion with insights and open questions

---

> *For any question or reuse, please contact mayy.miled@dauphine.eu or giuliano.aldarwish@dauphine.eu*
