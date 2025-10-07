# Feature Engineering and Selection on Heart Disease Dataset

This project focuses on **feature engineering and selection** techniques applied to a **Heart Disease dataset**.  
It demonstrates how to preprocess data, extract meaningful features, reduce dimensionality, and identify the most important predictors for efficient and accurate model training.

---

### 🔹 Key Objectives
- Create and encode new features using **One-Hot Encoding**
- Standardize numerical features for model training
- Apply **Principal Component Analysis (PCA)** to reduce dimensionality
- Evaluate **feature importance** using Random Forest
- Perform **Recursive Feature Elimination (RFE)** for optimal feature subset selection
- Fine-tune model hyperparameters using **Grid Search Cross-Validation**

---

### 🧰 Tools & Libraries Used
- **Pandas**, **NumPy** — Data manipulation and preprocessing  
- **Scikit-learn** — PCA, feature selection, and model optimization  
- **Matplotlib**, **Seaborn** — Visualization of PCA and tuning results  

---

### 📊 Techniques Applied
1. **Feature Encoding:** Converted categorical variables into dummy variables using `pd.get_dummies()`.  
2. **Scaling:** Standardized features before PCA to maintain uniform variance.  
3. **PCA:** Retained 95% variance with reduced components for computational efficiency.  
4. **Feature Importance:** Extracted from a trained `RandomForestRegressor`.  
5. **Recursive Feature Elimination (RFE):** Selected top 10 most influential features.  
6. **Hyperparameter Tuning:** Used `GridSearchCV` to optimize Random Forest parameters.  
7. **Visualization:** Generated heatmaps to analyze parameter performance.

---

### 🧠 Outcome
This project showcases how **systematic feature engineering and selection** can enhance model interpretability and performance, forming a solid foundation for predictive modeling in healthcare analytics.
