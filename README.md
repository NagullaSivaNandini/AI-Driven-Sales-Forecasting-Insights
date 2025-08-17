# 🤖 AI-Driven Sales Forecasting & Insights  

This project leverages **Machine Learning, AI, and Power BI** to forecast sales, uncover hidden business insights, and support data-driven decision-making through dashboards and a web app.  

---

## 📌 Overview  
- Forecast sales and revenue using **LSTM, SARIMAX, and XGBoost** (LSTM performed best).  
- Built for **Olist**, a Brazilian e-commerce company.  
- Provides **Power BI dashboards** for sales, logistics, and customer satisfaction.  
- Integrated with a **Streamlit web app** for interactive forecasting.  

---

## 📂 Project Structure  
├── Code/ # ML models & Jupyter Notebooks
├── Data/ # Olist dataset (9 CSV files, 100k+ orders)
├── Power BI/ # Dashboards for insights
├── Web App/ # Streamlit app for deployment
└── README.md # Documentation

---

## ⚙️ Technologies Used  
- **Python** (Pandas, NumPy, TensorFlow, Scikit-learn)  
- **Time Series Models:** SARIMAX, XGBoost, LSTM  
- **Visualization:** Power BI, Matplotlib, Seaborn  
- **Deployment:** Streamlit  
- **Version Control:** Git & GitHub  

---

## 🌟 Key Features  
✅ Robust **time series forecasting** capturing seasonality & trends  
✅ **Interactive Streamlit app** for revenue prediction  
✅ **Power BI dashboards** with sales, logistics & customer insights  
✅ **Comparison of models** (LSTM > SARIMAX > XGBoost)  

---

## 📊 Power BI Dashboards  

### Sales Insight Dashboard  
![Sales Dashboard](PowerBI/Sales_Dashboard.jpg)  

### Logistics Dashboard  
![Logistics Dashboard](PowerBI/Logistics_Dashboard.jpg)  

### Customer Satisfaction Dashboard  
![Customer Dashboard](PowerBI/Customer_Satisfaction.jpg)  

---

## 🚀 How to Run  

1. Clone the repository  
   ```bash
   
2. Install dependencies
   pip install -r requirements.txt

3. Run the web app
   streamlit run app.py


📈 Results
Model	RMSE	MAPE	R²
SARIMAX	xx	xx%	0.xx
XGBoost	xx	xx%	0.xx
LSTM	✅ Lowest	✅ Best	✅ Highest
👉 LSTM gave the most accurate 3-month sales forecast

📝 Recommendations for Olist

1. Launch seasonal promotional events (e.g., Black Friday).

2. Maintain high product quality & competitive pricing.

3. Introduce loyalty programs (discounts, free shipping).

4. Expand into new products & markets.

⚠️ Challenges & Future Work

-> Missing customer registration dates in dataset

-> Extend dataset for longer history & deeper analysis

-> Add external factors (inflation, economy, satisfaction scores)

-> Try FBProphet / ensemble models for improved accuracy
   
