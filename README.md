# Loan Default Prediction - Business Case

This repository contains a machine learning project. The objective is to build a supervised classification model to predict loan defaults for Lending Club, with a strong focus on minimizing financial risk and maximizing business impact.

Note: The dataset is too large to be hosted on GitHub.  
You can download it from the following link:  
[Download Dataset](https://urledu-my.sharepoint.com/:f:/g/personal/galla_garciacastany_esade_edu/ElZFxdbELP1Mg72ieUctQQcBZOhh_4Ku7536pocIEFsSAA?e=khAEfB)

---

## Project Overview

### Goals
- Predict loan defaults using supervised classification algorithms.
- Minimize the business impact of false predictions.
- Identify the most profitable and risk-balanced loan investment strategy.

### Contents
- `loan-business-case.ipynb`: Full analysis and modeling process, including:
  - Data preprocessing and cleaning
  - Feature selection and encoding
  - Handling class imbalance (SMOTE and undersampling)
  - Model training (Logistic Regression, Random Forest, SVM)
  - Model evaluation using metrics like AUC, precision, recall
  - Business impact analysis using different investment strategies

- `Business Case Presentation.pdf`: Slide deck summarizing the methodology, key results, and final business recommendations.

---

## Tools & Libraries
- Python 3.12
- scikit-learn
- pandas
- numpy
- imbalanced-learn
- matplotlib / seaborn

---

## Business Insight Summary

Three strategies were evaluated based on model predictions:
- Conservative (Grades A & B): Lowest risk and most stable returns — Recommended
- Balanced (Grades B to D): High loss due to excessive defaults
- Aggressive (Grades D to F): High ROI but very high risk

---

## How to Run

```bash
git clone https://github.com/nriccortesgit/loan-business-case.git
cd loan-business-case
jupyter notebook loan-business-case.ipynb
