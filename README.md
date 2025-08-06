# SmartStock AI
SmartStock AI is a Python-powered inventory management tool designed to help restaurants forecast ingredient demand, minimize food waste, and optimize procurement. Built using real-world restaurant data, this project blends data preprocessing, financial analysis, and machine learning to provide accurate predictions for kitchen operations.

## Overview

- **Goal**: Forecast ingredient demand using historical sales and recipe data.
- **Models**: Exponential Smoothing + XGBoost hybrid
- **Output**: Ingredient-level demand predictions per quarter

## Tech Stack

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost

## Project Structure

```
SmartStock-AI/
├── data/                    # Raw and cleaned datasets
├── notebooks/
│   └── smartstock_ai.ipynb  # Jupyter Notebook with full implementation
├── src/                     # (Optional) Python modules for reuse
├── requirements.txt
└── README.md
```

## Features

- Data preprocessing & standardization
- Ingredient-level demand calculation
- 5% static wastage buffer simulation
- Outlier detection using Z-score
- Heatmaps, time series plots, dish-ingredient mapping
- Forecasting with XGBoost using quarterly trends

## How to Run

```bash
# Step 1: Install dependencies
pip install -r requirements.txt

# Step 2: Open the notebook
jupyter notebook notebooks/smartstock_ai.ipynb
```

## Future Improvements

- NLP-based ingredient normalization
- Real-time dashboards
- Deep learning models (LSTM, Transformers)
- External data integration (weather, holiday trends)

## Creator
**Sarah Selama**
