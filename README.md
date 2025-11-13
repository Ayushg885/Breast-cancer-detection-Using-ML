# 🩺 Breast Cancer Detection using Logistic Regression

This project uses the **Breast Cancer Wisconsin dataset** from Scikit-learn to build a simple but effective **logistic regression model** that predicts whether a tumor is **benign** or **malignant**.  
It includes data visualization, model training, probability curve plotting, and evaluation metrics.

---

## 🚀 Features

### 📊 Data Exploration & Visualization
- Conversion of dataset to Pandas DataFrame  
- 3D scatter plot of:
  - mean radius  
  - mean texture  
  - mean perimeter  
- 2D scatter plot of mean radius vs tumor class  
- Color-coded plotting (red = malignant, blue = benign)

### 🧠 Machine Learning Model
- Logistic Regression using Scikit-learn  
- Sigmoid probability curve visualization  
- Two training setups:
  1. Single feature: mean radius  
  2. Full feature set (30 features)

### 📈 Model Evaluation
- Confusion Matrix  
- Accuracy score  
- Precision, Recall, F1-score  
- Classification report  
- Confusion matrix heatmap using Seaborn

---

## 📁 Dataset

Dataset is loaded directly through:

```python
from sklearn.datasets import load_breast_cancer
