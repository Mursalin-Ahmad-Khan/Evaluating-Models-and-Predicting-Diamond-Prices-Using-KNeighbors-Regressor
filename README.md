# 💎 Diamond Price Prediction — Model Evaluation & Price Forecasting

This project focuses on **predicting diamond prices** using regression models, with an emphasis on **model selection, evaluation, and performance comparison**.  
The aim is to identify the most suitable regression algorithm for this dataset and generate accurate price predictions.

---

## 📌 Project Overview
Diamonds have multiple attributes such as **carat**, **cut**, **color**, **clarity**, and dimensional measurements.  
Using the **Diamonds dataset**, this project:
- Performs **data preprocessing** and feature handling.
- Conducts **exploratory data analysis (EDA)** to understand patterns and relationships.
- Trains and evaluates multiple regression models.
- Selects the best-performing model for final predictions.

---

## 📂 Dataset
- **Source:** [Diamonds Dataset](https://www.kaggle.com/datasets/shivam2503/diamonds)  
- **Rows:** 53,940  
- **Columns:** 10 (including target `price`)  
- **Target Variable:** `price` (continuous numeric)

**Key Features:**
- `carat` — weight of the diamond
- `cut` — quality of the cut (Fair, Good, Very Good, Premium, Ideal)
- `color` — diamond color grading from J (worst) to D (best)
- `clarity` — measurement of how clear the diamond is
- Dimensions (`x`, `y`, `z`)

---

## 🛠️ Steps Performed
1. **Data Cleaning & Preprocessing**  
   - Handling missing values  
   - Encoding categorical variables  
   - Feature scaling (where needed)

2. **Exploratory Data Analysis (EDA)**  
   - Distribution of features  
   - Price vs. carat relationship  
   - Correlation heatmaps  
   - Boxplots for categorical features

3. **Model Training & Evaluation**  
   Models tested:
   - Linear Regression
   - Decision Tree Regressor
   - Random Forest Regressor
   - k-Nearest Neighbors Regressor  
   
   **Evaluation Metrics:**
   - R² Score
   - Mean Absolute Error (MAE)
   - Root Mean Squared Error (RMSE)

4. **Model Selection**  
   - Compared model performance  
   - Selected the model with best generalization ability

5. **Price Prediction**  
   - Used the selected model to predict diamond prices on test data

