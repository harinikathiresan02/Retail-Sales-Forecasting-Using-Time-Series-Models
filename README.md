# 🛒 Retail Sales Forecasting using ARIMA, Prophet, XGBoost & LSTM

This project focuses on forecasting daily retail sales using various time series and machine learning models to support better demand planning and inventory management.

---

## 📌 Objective

To predict future daily product-level sales using different forecasting techniques and compare their performance.

---

## 📁 Dataset

- *Source*: [M5 Forecasting - Accuracy](https://www.kaggle.com/competitions/m5-forecasting-accuracy/data)
- *Files Used*:
  - sales_train_evaluation.csv
  - calendar.csv
  - sell_prices.csv

---

## 🧪 Models Implemented

1. *ARIMA*: Traditional time series model
2. *Prophet*: Robust model by Facebook for forecasting
3. *XGBoost*: Gradient boosting on lag features
4. *LSTM*: Deep learning model for sequence prediction

---

## 🛠 Steps

1. Data preprocessing & merging from M5 datasets
2. Feature engineering (lag features for ML models)
3. Train-test split based on time series
4. Model training & forecasting (30 days ahead)
5. Model evaluation using:
   - MAE (Mean Absolute Error)
   - MSE (Mean Squared Error)
   - RMSE (Root Mean Squared Error)
   - R² Score

---

## 📊 Evaluation Summary

| Model   | MAE     | MSE       | RMSE    | R² Score |
|---------|---------|-----------|---------|----------|
| ARIMA   | 0.82    | 1.13      | 1.06    | -0.03    |
| Prophet | 29.42   | 1081.73   | 32.89   | -1.55    |
| XGBoost | 3961.57 | 1.66e+07  | 4078.59 | -16.39   |
| *LSTM*   | *385.06* | *2.52e+05* | *501.57* | *0.76*     |

✅ *LSTM performed best* with the highest R² score.

---

## 📈 Visualization

- Forecast vs Actual Sales plots
- Model performance comparison
- Prophet seasonality components

---

## 📌 Conclusion

LSTM proved to be the most accurate model for forecasting daily sales, demonstrating the power of deep learning in time series prediction.

---

## 📚 Tech Stack

- Python, Jupyter Notebook
- pandas, numpy, matplotlib, seaborn
- statsmodels, prophet, xgboost, tensorflow/keras, scikit-learn

---

## ✨ Author

Harini K – Data Science Enthusiast | Physics Graduate | Machine Learning Learner

## 📬 Contact
📧 harinikathiresan02@gmail.com
🔗 [LinkedIn](http://www.linkedin.com/in/harinithrishi)  
🔗 [Kaggle](https://www.kaggle.com/harinikathiresan)

---
