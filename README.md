# A Novel Machine Learning Program for Prediction and Analysis of Public Library Material Purchase Cost

<p align="center">
  <b>Jin-Woong Kim<sup>1</sup> · Seoung-Ho Choi<sup>2*</sup></b><br>
  <sup>1</sup>Department of Convergence IT Engineering, Hansung University, Seoul, Republic of Korea<br>
  <sup>2</sup>College of Liberal Arts, Faculty of Basic Liberal Arts, Hansung University, Seoul, Republic of Korea
</p>

****

<img width="1200" alt="Architecture" src="https://github.com/user-attachments/assets/61558051-d0a6-4095-b7d8-377a9d29bea2" />
<p align="center"><em>Figure 1. Overview of the proposed machine-learning program for predicting public library material purchase cost using statistical data and SHAP analysis.</em></p>

<br>

## Abstract

The material purchase cost in public libraries plays a vital role in ensuring equitable access to information and maintaining the quality of library services. However, budget forecasting is often complicated by fluctuations in demand, price, and policy constraints. To address this challenge, we propose a novel machine-learning program that predicts the next year’s material purchase cost using statistical data from the National Library Statistics System. The dataset includes 36 usage-related features from 12,672 library records collected between 2007 and 2021. We employed five tree-based machine-learning models and two deep-learning models to estimate next-year material purchase costs. Furthermore, we conducted SHAP analysis to interpret how each factor contributes to cost predictions and applied PCA to handle multicollinearity. Experimental results show that XGBoost achieved the best predictive performance (R² = 0.699), demonstrating the model’s potential for improving public library budget allocation.

<br>

## Motivation

- Accurate budget prediction is essential for sustainable library management and fair allocation of resources.  
- Existing regression or correlation-based approaches are limited in scalability and interpretability.  
- Applying modern machine-learning models can improve prediction accuracy and reveal which operational factors drive cost changes.  
- Interpretability through SHAP analysis allows policymakers to understand the quantitative impact of each variable.

<br>

## Contribution

- Built a **machine-learning framework** to forecast public library material purchase costs using national statistics data.  
- Collected and refined **36 annual usage indicators (2007–2021)** including number of staff, users, loans, and budgets.  
- Compared multiple models (Random Forest, Extra Trees, CatBoost, LightGBM, XGBoost, LSTM, Transformer).  
- Applied **PCA** to resolve multicollinearity and ensure model robustness.  
- Utilized **SHAP** to interpret the contribution of key predictors such as *current-year cost, user count, and collection size*.  
- Achieved the best performance using **XGBoost**, validating its potential for data-driven budget planning.
