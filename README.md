# Titanic Survival Prediction - Data Mining & Warehousing Practical

## Overview
This project was completed as part of the **BTECH Computer Science** course (BCS 402: Data Mining and Warehousing) at Accra Technical University. It involves comprehensive Exploratory Data Analysis (EDA) and building a predictive model on the famous Titanic dataset.

---

## Objectives
- Perform detailed Exploratory Data Analysis on the Titanic dataset
- Handle missing values and outliers effectively
- Develop a **Stacking Ensemble** model to predict passenger survival
- Evaluate the model using Confusion Matrix and key metrics

---

## Key Insights from EDA

1. **Passenger Class** significantly affected survival (1st class had much higher survival rate).
2. **Gender** was a very strong predictor — females had ~74% survival rate.
3. **Age** played an important role, especially for children.
4. Traveling with family improved survival chances.
5. Higher `Fare` (linked to class) was associated with better survival.

---

## Technologies Used
- **Python** in Google Colab
- **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**
- **Scikit-learn**, **XGBoost**
- Stacking Ensemble Model

---

## Model Performance
- **Model**: Stacking Ensemble (Random Forest + XGBoost + Logistic Regression)
- **Accuracy**: 79%
- Strong performance in predicting non-survivors with good overall balance.

---

## Repository Contents
- `Titanic_Data_Mining_Practical.ipynb` → Main Jupyter Notebook
- Screenshots of visualizations and model results

---

## How to Run
1. Open the notebook in Google Colab
2. Upload the `train.csv` dataset
3. Run all cells

---

## Author
**Mary Boaduaa Animpong **  
BTECH Computer Science  
ID:01259670B

Accra Technical University

---

**Submitted for**: Mid-Semester Practical Examination (BCS 402)
