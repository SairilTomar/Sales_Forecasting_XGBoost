# Sales_Forecasting_XGBoost

===============================================================================================>

This project builds a predictive model to forecast customer sales using historical data. It leverages **XGBoost**, a powerful gradient boosting algorithm, along with feature engineering techniques to capture seasonality and trends.

---

## 🔍 Key Features

- 🧹 **Data Cleaning**  
  - Duplicate removal  
  - Outlier filtering using IQR method  

- 🧠 **Feature Engineering**  
  - Monthly aggregation of weekly sales  
  - Lag features and rolling averages  
  - Time-based features (month, quarter, holiday flag)  

- 🤖 **Modeling**  
  - XGBoost regression  
  - Min-Max scaling for normalization  

- 📊 **Evaluation**  
  - R² Score: **0.856**  
  - MAE and MSE metrics  

- 📈 **Visualization**  
  - Actual vs predicted sales plotted over time



==================================================================================>
🔹 Motivation

Retail businesses rely heavily on accurate sales forecasting to optimize inventory, reduce costs, and increase profits. Traditional manual forecasting often fails to capture complex sales patterns.
This project applies Machine Learning **(XGBoost)** to forecast sales and compare predicted vs. actual values.

🔹 Dataset

Source: Walmart Sales Forecasting Dataset (Kaggle)

Columns Used:

**Date** – Weekly sales date

**Weekly_Sales** – Sales value (target variable)

Data was preprocessed to remove missing values and keep only the required columns.

🔹 Feature Engineering

Converted Date into time-based features:
Year
Month
Week
Scaled features using MinMaxScaler for better performance.

🔹 Model

Algorithm Used: XGBoost Regressor

Why XGBoost?

Handles large datasets efficiently

Captures complex non-linear sales patterns

Outperforms traditional regression models

🔹 Results & Insights

✅ Model achieved R² ≈ 0.85 (good accuracy)

✅ Captured sales trends and seasonality well

✅ XGBoost performed significantly better than basic linear models

📊 Performance Metrics:
MAE: ~2.6M
MSE: ~31.8M
R²: ~0.85

🔹 Visualization

Example: Actual vs Predicted Sales




🔹 How to Improve Further

Add more features (e.g., promotions, holidays, store types).

Try other models: LightGBM, Prophet, or Deep Learning (LSTM).

Hyperparameter tuning with GridSearchCV.

Deploy as a Flask/Django API or simple Streamlit app.

🔹 Tech Stack

Python 
Pandas, NumPy
Scikit-learn
XGBoost
Matplotlib
## 📂 Notebook

The full implementation is available in the Colab notebook:  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SairilTomar/Sales_Forecasting_XGBoost/blob/main/Sales_Forecast_using_xgBoost.ipynb)

---

## 🚀 How to Run

To replicate or extend this project:

1. **Clone the repository**  
   ```bash
   git clone https://github.com/SairilTomar/Sales_Forecasting_XGBoost.git


2. **Open the notebook in Google Colab**

3. **Upload your dataset (train.csv)**

4. **Run all cells to train and evaluate the model**


================================================================================>
## 📁 Dataset

This project uses `train.csv` as the input dataset.  
If you're cloning this repo, the file is already included.  

