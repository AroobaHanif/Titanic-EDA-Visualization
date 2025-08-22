# Machine Learning Internship Tasks – Titanic Dataset & Regression Models

This repository contains my submissions for multiple internship tasks, covering Exploratory Data Analysis (EDA), feature scaling, regression modeling, classification, and hyperparameter optimization.

---

## Task 1 – Titanic Dataset: Data Analysis & Visualization
- Loaded Titanic dataset using **Pandas**
- Performed EDA:
  - Data types, summary statistics
  - Missing values check
- Visualized:
  - Bar plots for categorical variables
  - Histograms for numerical variables
  - Correlation heatmap  

📂 File: `titanic.ipynb`

---

## Task 2 – Feature Scaling & Distribution Comparison
- Applied **StandardScaler** on numeric features
- Compared original vs scaled distributions using histograms  

📂 File: `Feature_Scaling_and_Distribution_Comparison.ipynb`

---

## Task 3 – Linear & Polynomial Regression (House Price Prediction)
- Trained **Simple Linear Regression** and **Polynomial Regression** models
- Compared predictions with actual values using scatter plots
- Evaluated models using:
  - R² Score
  - Mean Absolute Error (MAE)
  - Root Mean Squared Error (RMSE)  

📂 File: `LinearRegression.ipynb`

---

## Task 4 – Logistic Regression (Titanic Survival Prediction)
- Trained **Logistic Regression** model on Titanic dataset
- Split data into **train/test sets**
- Evaluated model using:
  - Confusion Matrix
  - Accuracy
  - Precision
  - Recall (Sensitivity)
  - F1-Score
  - Specificity, FPR, FNR, NPV (detailed classification metrics)  

📂 File: `LogisticRegression.ipynb`

---

## Task 5 – Hyperparameter Optimization (Titanic Survival Classifier)
- Implemented **hyperparameter tuning** for Titanic survival prediction using Logistic Regression
- Steps:
  - Initialized Logistic Regression model with default parameters (baseline performance)
  - Applied two optimization strategies:
    - **Grid Search (GridSearchCV)** – systematically explored predefined parameter grid
    - **Randomized Search (RandomizedSearchCV)** – sampled hyperparameters from probability distributions
  - Used **cross-validation** for robust evaluation
- Evaluated best models using:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
- Compared performance of:
  - Default model
  - Best Grid Search model
  - Best Randomized Search model
- Documented **optimal hyperparameters** found by each method  

📂 File: `HyperparameterOptimization.ipynb`

---

## 🛠 Tools & Libraries Used
- Python  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  

---

## 👩‍💻 Author
**Arooba Hanif**
