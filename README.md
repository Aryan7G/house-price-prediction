# House Price Prediction

A machine learning project to predict house prices using housing features such as area, number of bedrooms, bathrooms, stories, parking, and furnishing status.  
Built with **Python, Pandas, NumPy, Matplotlib, and Scikit-learn**.

---

## Project Overview

This project uses a **Linear Regression** model to predict house prices from a housing dataset.  
The goal of this project was to understand the complete beginner ML workflow:

- loading and exploring a dataset
- preprocessing categorical features
- splitting data into train and test sets
- training a regression model
- evaluating model performance with metrics

---

## Dataset Features

The dataset includes features such as:

- area
- bedrooms
- bathrooms
- stories
- main road access
- guest room
- basement
- hot water heating
- air conditioning
- parking
- preferred area
- furnishing status

**Target variable:** `price`

---

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab / Jupyter Notebook

---

## Workflow

1. Loaded the housing dataset
2. Explored the dataset using `head()`, `shape`, and basic inspection
3. Converted categorical columns using `pd.get_dummies()`
4. Split the data into features (`X`) and target (`y`)
5. Performed train-test split
6. Trained a **Linear Regression** model
7. Predicted house prices on test data
8. Evaluated the model using:
   - MAE
   - MSE
   - R² Score

---

## Model Performance

Results from the current model:

- **MAE:** 970043.40
- **MSE:** 1754318687330.66
- **R² Score:** 0.6529

---

## Project Structure

```bash
house-price-prediction/
├── data/
│   └── Housing.csv
├── notebooks/
│   └── house_price_prediction.ipynb
├── requirements.txt
├── README.md
└── .gitignore
