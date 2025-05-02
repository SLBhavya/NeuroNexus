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


# 🛡️ Credit Card Fraud Detection Using SMOTE and Logistic Regression

This project focuses on detecting fraudulent credit card transactions using **Logistic Regression**. It handles the **imbalanced dataset** problem by using **SMOTE (Synthetic Minority Oversampling Technique)** to create synthetic examples of fraud cases for better model performance.

---

## 📂 Dataset

- The dataset used is [Kaggle's Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud).
- It contains transactions made by European cardholders in September 2013.
- Out of 284,807 transactions, only 492 are fraudulent (Class = 1), making it a highly imbalanced dataset.

---

## 🔍 Key Libraries

- `pandas`, `numpy` for data manipulation  
- `sklearn` for ML models and preprocessing  
- `imblearn` for handling class imbalance with SMOTE

---

## 🧠 Workflow Steps

### Step 1: Import Libraries  
- Essential libraries like `pandas`, `sklearn`, `imblearn`, etc.

### Step 2: Load Dataset  
- Read and explore the dataset  
- View class distribution

### Step 3: Preprocess  
- Split data into training and test sets  
- Scale features using `StandardScaler`  
- Apply `SMOTE` to the training data

### Step 4: Train Model  
- Train a `LogisticRegression` model with `class_weight='balanced'`

### Step 5: Evaluate Model  
- Generate confusion matrix and classification report  
- Evaluate accuracy, precision, recall, F1-score

---

## 🧪 Results

- The model performs well in identifying fraudulent transactions after applying SMOTE.
- Balanced precision and recall values due to oversampling.

---

## 🚀 Future Work

- Compare with other models like `RandomForestClassifier`, `XGBoost`, or `Neural Networks`
- Implement a real-time fraud detection system
- Tune hyperparameters for improved performance

---









