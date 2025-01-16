# Policyholder Call Times Prediction

### **Project Overview**
As part of the Travelers University Modeling Competition 2024, our team developed a machine learning model to forecast policyholder call counts. This project aimed to optimize call center resource allocation and reduce operational costs.

### **Key Contributions**
- **Data Preprocessing**: 
  - Addressed missing values using K-NN imputation for categorical features.
  - Balanced imbalanced datasets and engineered features to improve model performance.
- **Modeling Approach**:
  - Explored multiple machine learning models, including Random Forest, XGBoost, Neural Networks, and Lasso Regression.
  - Selected **LinearGAM** as the best-performing model for its flexibility, interpretability, and minimal overfitting.
  - Achieved the **lowest RMSE (36.9046)** among all models and a **Gini score of 0.24530**.
- **Model Evaluation**:
  - Compared training (RMSE: 35.6755) and test (RMSE: 36.9045) scores to validate model performance and prevent overfitting.
  - Leveraged SHAP values to interpret key drivers of call counts.

### **Tools & Technologies**
- **Python**: pandas, scikit-learn, pygam
- **SQL**: Data extraction and feature engineering
- **Tableau**: Visualization for exploratory analysis
- **Machine Learning Algorithms**: LinearGAM, Random Forest, XGBoost, Neural Networks, Lasso Regression

### **Data Source**
The dataset for this project is publicly available on Kaggle: [2024 Travelers University Modeling Competition](https://www.kaggle.com/competitions/2024-travelers-university-modeling-competition/data).

### **Results**
- Achieved actionable insights for customer segmentation and call center resource optimization.
- Delivered a business presentation summarizing the approach, results, and recommendations.

### **Performance Metrics**
- **Gini Score**: 0.24530
- **RMSE Comparison**:
  - LinearGAM: 36.9046 (Best Model)
  - Random Forest: 37.8815
  - XGBoost: 38.8416
  - Neural Networks: 37.8316
  - Lasso Regression: 37.3392
  - Quantile Regression: 41.8595
