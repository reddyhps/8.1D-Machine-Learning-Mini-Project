# Sydney Housing Price Prediction

## Overview

This project uses machine learning to predict residential property sale prices in Sydney.

The dataset contains property sales from three suburbs:

- Parramatta
- Ryde
- Mosman

Property features such as bedrooms, bathrooms, land size, building size, and location information were used to predict sale prices.

---

## Dataset

- 150 property records collected
- 139 records used for modelling after cleaning
- 15 predictor variables
- Target variable: `Sale_Price`

### Features Used

- Suburb
- Bedrooms
- Bathrooms
- Car Spaces
- Land Size
- Building Size
- Storeys
- Garage
- Ensuite
- Renovated
- Development Potential
- Distance to Train Station
- Distance to CBD
- Sale Method
- Sale Year

---

## Models Evaluated

Three regression models were compared:

1. Linear Regression
2. Random Forest Regression
3. Gradient Boosting Regression

---

## Results

| Model | Test R² |
|---------|---------|
| Linear Regression | 0.016 |
| Random Forest | 0.389 |
| Gradient Boosting | 0.457 |

Random Forest was selected as the final model because it achieved the best overall cross-validation performance.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Key Findings

- Mosman had the highest average property prices.
- Building size and location were important predictors.
- Ensemble models outperformed Linear Regression.
- Data quality and feature availability significantly affected prediction accuracy.

---

## Decision Support System

A simple property price estimator was developed using the trained Random Forest model.

Users can enter property details and receive an estimated sale price.

---

## Author

**Satyanarayana Reddy Karri**

Melbourne, Australia
