# 🚢 Titanic Survival Prediction using K-Nearest Neighbors (KNN)

This project aims to predict passenger survival on the Titanic using the **K-Nearest Neighbors (KNN)** classification algorithm. It involves loading and cleaning the dataset, performing exploratory data analysis, data preprocessing, scaling features, and evaluating the model's performance using accuracy metrics and visualizations.

## 📌 Dataset Used
The dataset used is the tested.csv

---

## 🔧 Tools and Libraries
- Python 
- Pandas & NumPy
- Matplotlib & Seaborn (for visualizations)
- Scikit-learn (for machine learning models and preprocessing)

---

## 📊 Workflow

### 1. Data Preprocessing
- Handled missing values in `Age` and `Fare`
- Dropped the `Cabin` column
- Converted categorical variables (`Sex`, `Embarked`) to numeric

### 2. Exploratory Data Analysis (EDA)
- Survival counts and their relation to gender and passenger class
- Visualizations using count plots

### 3. Feature Scaling
- Used `StandardScaler` to normalize features before applying KNN

### 4. Model Building
- Used `KNeighborsClassifier` from scikit-learn
- Evaluated using accuracy score on both training and testing sets

---

## ✅ Results

| Dataset        | Accuracy |
|----------------|----------|
| Training Data  | ~99%   |
| Test Data      | ~98%     |






