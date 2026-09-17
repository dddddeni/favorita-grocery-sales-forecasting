# Favorita Grocery Sales Forecasting

A machine learning project for analyzing and predicting grocery sales trends using the Favorita dataset.

The project combines historical sales data with store information, transactions, promotions, holidays, and oil prices to build classification models for predicting whether product sales will increase compared to the previous week.

---

## Features

- Data cleaning and preprocessing
- Integration of multiple data sources
- Exploratory data analysis
- Time-based feature engineering
- Lag and rolling features
- Time-based train-test split
- Comparison of multiple machine learning models
- Model evaluation using classification metrics

---

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- LightGBM
- Jupyter Notebook

---

## Machine Learning Models

- Logistic Regression
- Random Forest
- LightGBM
- Dummy Classifier as a baseline

---

## Model Evaluation

The models were evaluated using accuracy, F1-score, classification reports, confusion matrices, and ROC-AUC.

LightGBM achieved the strongest overall performance, with approximately **71% accuracy** and a **ROC-AUC score of 0.78**.

---

## Dataset

The project uses the Favorita grocery sales dataset, containing historical sales information together with store, transaction, promotion, holiday, and oil price data.
