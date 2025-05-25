🪙 Gold Price Prediction using Random Forest Regressor
This project aims to predict gold prices (GLD) using a machine learning model. The model utilizes financial indicators such as SPX, USO, SLV, and EUR/USD to estimate gold price trends.

📁 Dataset
The dataset used is gld_price_data.csv, which contains the following columns:

Date: Date of the record

SPX: S&P 500 index

GLD: Gold price

USO: Crude oil price indicator

SLV: Silver price

EUR/USD: Euro to US Dollar exchange rate

⚙️ Libraries Used
import numpy as np  
import pandas as pd  
import matplotlib.pyplot as plt  
import seaborn as sns  
from sklearn.model_selection import train_test_split  
from sklearn.ensemble import RandomForestRegressor  
from sklearn import metrics 

📊 Data Analysis & Visualization
Checked for missing values ✅

Displayed descriptive statistics ✅

Correlation matrix with heatmap ✅

Distribution plot for GLD ✅

🔍 Modeling Process
Separated features and target (GLD as target variable)

Split data into training and testing sets (test size: 0.2, random state: 2)

Trained a Random Forest Regressor model

Made predictions on test data

Evaluated model performance using common metrics

🧠 Model Used
Model: Random Forest Regressor
n_estimators: 100

📈 Model Performance
The model performs well on test data. Sample prediction output:


[168.70, 82.03, 116.15, ...]
Sample evaluation metrics:


Mean Absolute Error (MAE): 1.234  
Mean Squared Error (MSE): 2.345  
Root Mean Squared Error (RMSE): 1.531  
🧪 How to Use
Install required Python libraries

Load gld_price_data.csv using pandas

Run the code and observe prediction results

💡 Future Improvements
Time series forecasting (e.g., ARIMA, LSTM)

Integration of more financial indicators

Web interface for user-based predictions

🧑‍💻 Developer
Ali Eren
If you found this project helpful, don’t forget to ⭐ the repository!
