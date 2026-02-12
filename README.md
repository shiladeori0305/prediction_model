# 🚀 Real-Time Indian Commodity Price Forecasting Dashboard (ML Powered)

An end-to-end Machine Learning dashboard that analyzes and forecasts commodity prices in INR using live financial data, feature-engineered time series inputs, and ensemble learning.This project demonstrates applied Data Science, Financial Modeling, and Production-Oriented ML engineering using Streamlit.

---

## 🌟 Why This Project Stands Out

✔ Real-time financial data integration  
✔ Currency-aware modeling (USD → INR conversion)  
✔ Feature-engineered time series forecasting  
✔ Ensemble ML model (Random Forest)  
✔ Interactive analytics dashboard  
✔ Production-ready structure  

This is not just a model — it is a complete ML pipeline from data ingestion to user-facing visualization.

---

## 📊 Live Commodities Tracked

- 🟡 Gold (24K, ₹/10g)
- ⚪ Silver (₹/kg)
- 🛢 Crude Oil
- 🔥 Natural Gas
- 🟤 Copper

All prices are dynamically converted into INR using real-time USDINR exchange rates.

---

## 🧠 Machine Learning Architecture

### 🔹 Feature Engineering
- Lag features (1–5 days)
- Rolling mean & rolling standard deviation
- USDINR exchange rate as macroeconomic feature
- Crude oil correlation feature

### 🔹 Model
- Random Forest Regressor
- 400 estimators
- Depth-controlled to reduce overfitting
- Multi-step recursive forecasting (Next 5 days)

---

## 📈 Dashboard Capabilities

- Historical trend visualization
- Short-term forward predictions
- Interactive charts (Plotly)
- Dynamic commodity selection
- Clean responsive UI using Streamlit

---

## 🛠 Technology Stack

- Python
- Streamlit
- Pandas
- NumPy
- Scikit-learn
- yFinance API
- BeautifulSoup
- Requests
- Plotly
- Matplotlib


---

## ⚙️ Installation Guide

Clone the repository:

git clone https://github.com/shiladeori0305/prediction_model.git  
cd prediction_model  

Install dependencies:

pip install -r requirements.txt  

Run the app locally:

streamlit run app.py  

---

## 🎯 Engineering Highlights

• Built a complete ML workflow from raw financial data to deployable dashboard  
• Integrated macroeconomic indicators into commodity prediction  
• Implemented recursive forecasting strategy  
• Applied ensemble learning for improved generalization  
• Structured project for production-style deployment  


---

## ⚠️ Disclaimer

This project is intended for educational and research purposes only.  
Predictions are generated using statistical models and should not be considered financial advice.

