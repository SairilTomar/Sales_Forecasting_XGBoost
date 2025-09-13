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

