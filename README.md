# Alzheimer's Disease Prediction - Machine Learning Analysis

## Overview
This project explores the **Alzheimer's Disease Dataset** using **exploratory data analysis (EDA)** and **machine learning models** to predict Alzheimer's diagnosis. It compares multiple classification models to identify the most effective one for predicting Alzheimer's disease based on various clinical, demographic, and lifestyle factors.

- **Author:** Deniz Lal Ersoy  
- **Date:** 02.12.2024  

## **Dataset**
- **Source:** [Kaggle - Alzheimer's Disease Dataset](https://www.kaggle.com/dsv/8668279)
- **Citation:** Rabie El Kharoua (2024). *Alzheimer's Disease Dataset.* Kaggle. DOI: [10.34740/KAGGLE/DSV/8668279](https://www.kaggle.com/dsv/8668279)

## **Machine Learning Models & Results**
Five classification models were trained and evaluated:

| Model                 | Accuracy  | Precision (1) | Recall (1) | F1-Score (1) |
|----------------------|-----------|--------------|-----------|-------------|
| **Logistic Regression** | 0.798 | 0.68 | 0.82 | 0.74 |
| **Random Forest**      | 0.926 | 0.93 | 0.86 | 0.89 |
| **SVM**               | 0.823 | 0.73 | 0.64 | 0.68 |
| **XGBoost**           | **0.942** | **0.94** | **0.86** | **0.90** |
| **KNN**               | 0.674 | 0.54 | 0.52 | 0.53 |

## **Takeaways**
- **XGBoost achieved the highest accuracy (94.2%)**, making it the best-performing model.
- **Random Forest also performed well (92.6%)** but had slightly lower recall for Alzheimer's cases.
- **Logistic Regression & SVM performed moderately well**, with decent accuracy but lower recall for the minority class.
- **KNN had the lowest accuracy (67.4%)**, indicating that it struggles with this dataset.

## **Handling Class Imbalance**
- The dataset was moderately imbalanced (1.8:1 ratio).
- **SMOTE (Synthetic Minority Over-sampling Technique)** was applied to balance the training data.
- The test set was left **imbalanced** to reflect real-world distributions.

## **Contact**
If you have any questions or suggestions, feel free to reach out!

 **Email:** [ersoydenizlal@gmail.com]  
 **GitHub:** [github.com/lalersoy]

