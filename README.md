# House Price Prediction

## Description

This project predicts house prices using a dataset and Linear Regression. It involves data cleaning, analysis, and model evaluation.

## Dataset

- **File:** `house_data.csv`
- **Features:** Includes details like `bedrooms`, `sqft_living`, `price`, etc.
- **Rows:** 21,613
- **Features:** 20 (excluding the target variable `price`)

## Data Preparation

- **Removed Columns:** `date`, `id`
- **Target Variable:** `price`
- **Features Used:** All columns except `price`

## Analysis

- **Correlation Matrix:** Shows relationships between features and `price`.

- **Statistics & Missing Values:** No missing values found.

## Model

- **Type:** Linear Regression
- **Data Split:** 80% training, 20% testing

### Performance

- **Mean Squared Error (MSE):** 45,173,046,132.79
- **R-squared (R²):** 0.7012



## Visuals

- **Actual vs Predicted Prices:** Shows how close the predicted prices are to actual prices.

  
## How to Use

1. **Clone the Repo:**

   ```bash
   git clone https://github.com/Lamrotibsa/PRODIGY_ML_01.git
   ```
2 **Install Dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
3 **Run Analysis:**
    ```bash
    Execute the Jupyter notebook or Python scripts provided.
    ```

