# 🏠 House Price Prediction & Market Segmentation in Kuala Lumpur

This machine learning project explores residential property data in Kuala Lumpur, Malaysia. It aims to deliver both **accurate house price predictions** and **market segmentation insights** to support smarter decision-making for real estate stakeholders.

---

## 🎯 Project Objectives

- Predict housing prices using supervised learning models.
- Segment the housing market into meaningful groups using unsupervised learning.
- Analyze the most influential features affecting property value.
- Provide actionable recommendations for real estate agencies, buyers, and developers.

---

## 📊 Key Techniques Used

### 🔹 Data Preprocessing
- Handling missing values with statistical imputation and assumptions.
- Log transformation to reduce skewness in `Price` and `Size`.
- Robust scaling to manage outliers.
- One-hot encoding and target encoding for categorical variables.

### 🔹 Unsupervised Learning (Market Segmentation)
- **Model:** K-Means Clustering
- **Optimal K:** 2 (determined via Elbow Method)
- **Clusters Identified:**
  - **Luxury Properties**: Larger size (~2,150 sq ft), higher prices (~RM1.8M+), more rooms and bathrooms.
  - **Mid-Range Properties**: Moderate size (~1,015 sq ft), average pricing (~RM600K).
- **Evaluation:** Silhouette Score = 0.363
- **Visualization:** PCA for 2D cluster separation

### 🔹 Supervised Learning (Price Prediction)
- **Models Trained:**
  - Linear Regression
  - Random Forest Regressor
  - Gradient Boosting Regressor
  - XGBoost Regressor
- **Best Model:** Random Forest Regressor
  - R² Score (Test): 0.9372
  - MAE: 0.1393
  - RMSE: 0.1729

---

 

