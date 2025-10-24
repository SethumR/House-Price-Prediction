# House Price Prediction using Machine Learning

## Project Overview
This project is a **Machine Learning model** that predicts house prices based on various features such as area, bedrooms, bathrooms, and number of floors. The project demonstrates the full ML workflow: data collection, preprocessing, exploratory analysis, model training, evaluation, and visualization.

The goal is to provide a **predictive model** that can estimate house prices for real-world use cases, and to showcase a complete end-to-end ML workflow.

---

## Dataset
- Dataset used: **House Sales in King County, USA**  
- Source: [Kaggle Dataset](https://www.kaggle.com/datasets/harlfoxem/housesalesprediction)  
- File: `kc_house_data.csv`  
- Features include:
  - `sqft_living` – Living area in square feet  
  - `bedrooms` – Number of bedrooms  
  - `bathrooms` – Number of bathrooms  
  - `floors` – Number of floors  
  - `price` – Target variable (house price)

---

## Project Steps

### 1. Data Collection
- Downloaded dataset from Kaggle.  
**Why:** Machine Learning models need real-world data to learn patterns.

### 2. Data Exploration (EDA)
- Inspected structure, summary statistics, and missing values.
- Visualized distributions and correlations.  
**Why:** To understand relationships, identify patterns, and spot outliers.

### 3. Data Cleaning and Feature Selection
- Removed irrelevant columns (`id`, `date`)  
- Selected important features (`sqft_living`, `bedrooms`, `bathrooms`, `floors`)  
**Why:** Focus on meaningful data and prevent noise from affecting model performance.

### 4. Split Dataset
- Divided data into **training set (80%)** and **testing set (20%)**  
**Why:** To train the model and test on unseen data for generalization.

### 5. Model Training
- Used **Linear Regression** to train the model  
**Why:** Model learns relationships between house features and prices.

### 6. Model Prediction
- Generated predictions on the test set  
**Why:** Evaluate how well the model can predict new data.

### 7. Model Evaluation
- Metrics used:  
  - Mean Squared Error (MSE)  
  - R² Score  
**Why:** To measure accuracy and performance of the model.

### 8. Visualization
- Plotted Actual vs Predicted prices using scatter plots  
**Why:** Quick visual check of model performance.

### 9. Predict Custom Input
- Tested the model with new example houses  
**Why:** Demonstrates real-world application.

### 10. Save Model (Optional)
- Saved trained model using `joblib`  
**Why:** Makes it reusable for deployment or future predictions.

---

## How to Run
1. Open the project in **Google Colab** or Jupyter Notebook.  
2. Upload `kc_house_data.csv` to the notebook.  
3. Run each cell step-by-step:
   - Import libraries  
   - Load dataset  
   - Clean and select features  
   - Split dataset  
   - Train model  
   - Predict and evaluate  
4. Optionally, test with new inputs or save the trained model.

---

## Libraries Used
- `pandas` – Data manipulation  
- `numpy` – Numerical operations  
- `matplotlib` / `seaborn` – Data visualization  
- `scikit-learn` – Machine Learning models and evaluation  
- `joblib` – Save trained model

---