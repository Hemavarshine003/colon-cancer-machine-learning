# Colon Cancer Classification using Machine Learning

## Project Overview
This project applies machine learning techniques to classify colon cancer samples using high-dimensional gene expression data.

Dataset characteristics:
- Samples: 208
- Features: 19,297 genes
- Classes: Colon Cancer vs Control

The objective is to evaluate machine learning algorithms and identify important gene biomarkers contributing to cancer prediction.

## Machine Learning Models
The following algorithms were evaluated:

- Support Vector Machine (SVM)
- Random Forest
- XGBoost
- Decision Tree
- Logistic Regression

## Dimensionality Reduction
Principal Component Analysis (PCA) was applied to reduce high-dimensional gene expression features and analyze variance structure.

## Key Biomarkers Identified
Important genes identified through SHAP feature importance analysis:

- KRAS
- PIK3CA
- TP53
- APC

These genes are well known drivers of colorectal cancer pathways.

## Tools Used
- Python
- Scikit-learn
- XGBoost
- SHAP
- Pandas
- NumPy
- Matplotlib

## Repository Structure

data → gene expression dataset  
notebooks → analysis notebook  
scripts → machine learning pipeline  
results → evaluation plots and figures
