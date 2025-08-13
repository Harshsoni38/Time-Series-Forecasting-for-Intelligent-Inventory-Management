# 📈 Time-Series Demand Forecasting & Inventory Optimization

## 📌 Project Overview
This project focuses on **demand forecasting** and **inventory optimization** using Python, with a strong emphasis on **time series analysis**.  
By leveraging **statistical modeling** and **forecasting techniques**, we predict future demand for products and calculate optimal inventory control parameters such as **order quantity**, **reorder point**, and **safety stock**.

The project applies **real-world supply chain concepts** to reduce stockouts, minimize holding costs, and maintain high service levels.

---

## 🚀 Key Features
- **Demand Forecasting:** Predict future product demand using time-series modeling.
- **ACF & PACF Analysis:** Visualize autocorrelation patterns for model selection.
- **Inventory Optimization:** Calculate optimal order quantity, reorder point, and safety stock.
- **Cost Minimization:** Combine holding cost and stockout cost to optimize total cost.
- **Customizable Parameters:** Easily adjust service level, lead time, and cost factors.

---

## 🛠️ Technologies Used
- **Python**
- **Pandas** – Data handling
- **NumPy** – Mathematical operations
- **Matplotlib** – Data visualization
- **Statsmodels** – ACF & PACF plots, statistical modeling

---

## 📂 Project Workflow
1. **Data Preprocessing**
   - Load the dataset
   - Convert `Date` column to datetime format
   - Set time series index
2. **Exploratory Data Analysis**
   - Plot historical demand trends
   - Analyze seasonality and trends
3. **Differencing for Stationarity**
   - Apply first-order differencing
   - Plot **ACF** and **PACF** to identify ARIMA parameters
4. **Model Building**
   - Forecast demand for the desired period
5. **Inventory Optimization**
   - Calculate:
     - **Optimal Order Quantity** (Newsvendor model)
     - **Reorder Point**
     - **Safety Stock**
     - **Total Cost**
6. **Visualization**
   - Forecast plot
   - Inventory policy insights

---

## 📊 Formulas Used
- **Order Quantity (Q\*)** = Mean Forecast + *z*-score for desired service level
- **Reorder Point (ROP)** = (Mean Daily Demand × Lead Time) + Safety Stock
- **Safety Stock (SS)** = z × Standard Deviation of Demand × √Lead Time
- **Total Cost** = Holding Cost + Stockout Cost

---



---
---

## 📅 Use Cases
- Retail product demand forecasting
- Warehouse inventory management
- E-commerce supply chain optimization
- Manufacturing production planning

---

---

## 📌 Future Improvements
- Integrate **ARIMA/SARIMA/Prophet** models for better forecasting.
- Add **seasonality adjustments** for more accurate predictions.
- Create **interactive dashboards** using Plotly/Dash.
- Automate parameter tuning with grid search.

---

## 🤝 Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements.

---

