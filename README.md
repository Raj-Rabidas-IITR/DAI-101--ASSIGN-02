# DAI-101 - Assignment 02: Predictive Model for Restaurant Tips

### **Submitted by:** Raj Rabidas  
- **Enrollment Number:** 23118064  
- **Branch:** Metallurgical and Materials Engineering, 2nd Year BTech  
- **Course:** DAI-101  
- **Submission Date:** *[10/11/2024]*

---

## Project Overview
This project aims to enhance restaurants' understanding of tipping behavior by developing a predictive model to estimate tip amounts. Using various regression techniques, this model will help identify factors influencing tips, improve customer service strategies, and assist in revenue management.

### Problem Statement
1. **Regression Techniques**: 
   - Apply regression techniques, including:
     - **Linear Regression**
     - **Ridge and Lasso Regularization**
     - **Decision Tree Regression**
     - **Ensemble Methods** (Random Forest)
     - **Support Vector Regression (SVR)**
     - **K-Nearest Neighbors (KNN)**
   
   - **Goals**:
     1. Identify significant factors impacting tip amounts.
     2. Build and evaluate models to predict tips effectively.
     3. Provide insights to enhance customer service strategies and optimize revenue management.

2. **Data Analysis for Linearity**:
   - Check if the data follows a linear trend using:
     - **Scatter Plot**
     - **Pair Plot for Multiple Features**
     - **Correlation Matrix (Heatmap)**
     - **Statistical Tests for Linearity (Rainbow Test)**
     - **Residuals Plot**
     - **Line Plot** (for time-series data, if applicable)
   - Based on data trends, apply appropriate regression methods and evaluate model accuracy.

## Libraries Used
```python
import pandas as pd
import numpy as np
from sklearn.model_selection import train_test_split, cross_val_score
from sklearn.linear_model import LinearRegression, Ridge, Lasso
from sklearn.ensemble import RandomForestRegressor
from sklearn.tree import DecisionTreeRegressor
from sklearn.svm import SVR
from sklearn.neighbors import KNeighborsRegressor
from sklearn.preprocessing import LabelEncoder
from sklearn.metrics import r2_score, mean_squared_error, accuracy_score
from sklearn.model_selection import GridSearchCV
import matplotlib.pyplot as plt
import seaborn as sns
