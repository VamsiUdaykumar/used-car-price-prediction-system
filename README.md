# Used Car Price Prediction System

This repository contains a machine learning project that predicts the market price of used cars based on various features such as brand, mileage, year, fuel type, and transmission. Built using PySpark for scalable data processing and trained on a 3 million+ row dataset.

---

## Project Summary

Used car pricing is often inconsistent and subjective. Our goal is to build a data-driven pricing model that improves fairness and accuracy in the used car market. We used a large Kaggle dataset, processed it using PySpark, and trained models to predict car prices using Spark MLlib and scikit-learn.

---

## Files

```
.
├── ucpps-notebook.ipynb       # Main notebook containing full pipeline
└── README.md             # This file
```

---

## Dataset

- **Source**: [Kaggle - US Used Cars Dataset](https://www.kaggle.com/datasets/ananaymital/us-used-cars-dataset)
- **Size**: ~10GB
- **Records**: 3,000,000+
- **Fields**: Make, Model, Year, Mileage, Fuel Type, Transmission, Location, Price

---

## Model Overview

We trained and compared:

- **Linear Regression** (baseline)
- **Random Forest Regressor** (best model)

**Performance:**

| Model              | MAE   | RMSE  | R² Score |
|-------------------|-------|-------|----------|
| Linear Regression | 1750  | 2200  | 0.67     |
| Random Forest     | 1185  | 1605  | 0.83     |

---

## Technologies

- Python 3.8+
- PySpark
- Spark MLlib
- scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

---

## How to Run

1. Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/used-car-price-predictor.git
cd used-car-price-predictor
```

2. Install dependencies:
```bash
pip install pyspark pandas numpy scikit-learn matplotlib seaborn
```

3. Start Jupyter Notebook and run `ucpps-notebook.ipynb` cell by cell.


