
====================================================================
            # STOCK PRICE PREDICTION USING COLLECTIVE NSE DATASET    
====================================================================

📅 Dataset Duration  :  02-Jan-1991 to 05-Jul-2024  
📊 Data Source       :  Consolidated NSE Historical Stock Prices  
📌 Project Type      :  Time Series Forecasting with User Input  
🧠 Libraries Used    :  Python, Pandas, NumPy, Scikit-learn, Matplotlib  

--------------------------------------------------------------------
📁 PROJECT DESCRIPTION
--------------------------------------------------------------------

This project demonstrates stock price prediction by utilizing a 
COMPREHENSIVE NSE dataset containing historical data of ALL 
listed companies from 1991 to 2024.

Unlike previous models which focused on individual datasets (e.g., 
TCS.csv), this model is designed to dynamically filter and process 
data based on USER INPUT, making it more SCALABLE and EFFICIENT.

--------------------------------------------------------------------
🔍 KEY FEATURES
--------------------------------------------------------------------

✔ Input-based dynamic filtering (e.g., "TCS", "INFY")  
✔ Supports over 30 years of data across NSE-listed companies  
✔ Data preprocessing and feature scaling  
✔ ML-based prediction model (Linear Regression/LSTM/Custom Model)  
✔ Visualizations of actual vs predicted stock trends  
✔ Error metric evaluations (MSE, RMSE, R²)

--------------------------------------------------------------------
🛠 HOW IT WORKS
--------------------------------------------------------------------

1. User enters a valid stock name (e.g., "TCS")
2. The model filters the collective dataset for that company
3. Data is cleaned, scaled, and split into train/test sets
4. A machine learning model is trained on historical prices
5. Future prices are predicted and visualized

--------------------------------------------------------------------
📦 FILE STRUCTURE
--------------------------------------------------------------------

- Stock_Price_prediction__Collective_Dataset.ipynb   # Main notebook
- collective_nse_data.csv                            # Full dataset (not included here)
- README.txt                                          # Project overview

--------------------------------------------------------------------
📈 FUTURE SCOPE
--------------------------------------------------------------------

- Develop a web app using Flask/Django for user interaction  
- Integrate with live stock APIs (e.g., Alpha Vantage, Yahoo Finance)  
- Include sentiment analysis from financial news or tweets  
- Save trained models using joblib/pickle for faster deployment  
- Add comparative performance between stocks over time  

--------------------------------------------------------------------
📃 LICENSE
--------------------------------------------------------------------

Apache License 2.0  
You are free to use, modify, and distribute this project with 
proper attribution.

--------------------------------------------------------------------
👤 AUTHOR
--------------------------------------------------------------------

Raakesh Kripal VUK  
Project Title : Stock Price Prediction from Collective Dataset  
Date         : July 2024  
