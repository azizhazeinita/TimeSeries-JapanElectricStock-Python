# TimeSeries-JapanElectricStock-Python

**This project was built by a team of four persons including Azizha Zeinita**

**Project Goal**

Japan Exchange Group, Inc. (JPX) is a holding company operating one of the largest stock exchanges in the world, which one of it’s significant stocks is Tokyo Gas stock. This project will compare several models against real future returns& of Tokyo Gas stock after the training phase is complete. Other external datasets that are closely related to stock price, such as Japan GDP, Unemployment Rate, Oil Price, etc., will also involved in different combinations to find the best output.

**Datasets**
1. Stock Data
  Tokyo Gas Stock (JPX)
    
    **Source:**    
      1. Stock_prices.csv: https://drive.google.com/file/d/180kdkDgTpFjTTAX-ZiDRVkuo22nr5hg1/view?usp=sharing
      2. Initial source: https://www.kaggle.com/competitions/jpx-tokyo-stock-exchange-prediction/data
  
2. External Data
  Japan Seasonally Adjusted Gross Domestic Product (GDP)
  Japan Seasonally Adjusted Unemployment Rate
  Daily Crude Oil Price
  Daily Exchange Rate for USD JPY
  Japan Daily 10 year Treasury Bond Interest Rate
  Nikkei 225 index
   
   **Sources:**
    FRED (https://fred.stlouisfed.org/) *via API
    Yahoo Finance (https://finance.yahoo.com/) *via API
    Ministry of Finance in Japan (https://www.mof.go.jp/english/policy/jgbs/reference/interest_rate/index.htm)
    Methods and Evaluation
    Time series models using ARIMA, VAR, PROPHET, Long Short-Term Memory (LSTM) with evaluation metrics MAE, MSE, MAPE, sMAPE, MASE
