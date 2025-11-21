# California Housing – Machine Learning Regression Project

Main analysis notebook:
- [`notebooks/01_california_housing_ml.ipynb`](notebooks/01_california_housing_ml.ipynb)

This project builds a regression model to predict house prices in California
based on the classic *California Housing* dataset.

## Project goals

- Exploratory Data Analysis (EDA) to understand the dataset.
- Data cleaning and preprocessing (missing values, scaling/encoding if needed).
- Training and comparison of several regression models:
  - baseline models,
  - Random Forest Regressor,
  - XGBoost Regressor.
- Evaluation with metrics: MSE, RMSE, R².
- Interpretation of feature importances and conclusions.

## Tech stack

- Python
- Jupyter Notebook
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- xgboost

## How to run

1. Create and activate a virtual environment (optional, but recommended).
2. Install dependencies:

   ```bash
   pip install -r requirements.txt

jupyter notebook

notebooks/01_california_housing_ml.ipynb

california-housing-ml/
├── notebooks/
│   └── 01_california_housing_ml.ipynb   # main analysis
├── requirements.txt                     # project dependencies
└── README.md                            # this file


---

### 3️⃣ Git lokalnie

W terminalu w katalogu `california-housing-ml`:

```bash
git init
git add .
git commit -m "Initial commit - California Housing ML project"
