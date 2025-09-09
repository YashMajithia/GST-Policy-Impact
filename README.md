# GST-Policy-Impact
Analysing the impact of GST reforms announced by the Indian Government on Stock and Commodity Markets

# GST Changes Impact Analyzer  

## 📌 Project Overview  
This project is designed as a **case study** to understand the **macroeconomic and market impacts** of Goods and Services Tax (GST) changes in India.  

Through a combination of **simulated financial data** and analytical modeling, the project demonstrates how GST reforms can ripple across:  
- Stock market indices (Nifty 50 & Sensex)  
- Commodity markets (Gold & Cement)  
- Consumer purchasing power  

---

## ⚙️ Methodology  
1. **Data Simulation**  
   - Created synthetic datasets representing stock indices and commodity prices before and after GST changes.  
   - Focused on cement (affected by GST tax cut) and gold (safe-haven asset).  

2. **Market Impact Analysis**  
   - Measured direction and magnitude of changes in Nifty 50, Sensex, cement prices, and gold prices.  

3. **Purchasing Power Modeling**  
   - Built a **linear regression model** predicting a **Purchasing Power Index (PPI)** based on commodity price changes.  
   - Evaluated model accuracy using **Mean Squared Error (MSE ≈ 0.43)**.  

---

## 📊 Results  

### 1. Stock Market  
- **Nifty 50** → rose after GST changes, reflecting positive investor sentiment.  
- **Sensex** → showed volatility, with some decline despite overall GST optimism.  

### 2. Commodities  
- **Cement** → prices dropped as GST tax cuts lowered costs, boosting infrastructure potential.  
- **Gold** → surged as investors hedged against policy uncertainty, reflecting its **safe-haven appeal**.  

### 3. Consumer Impact  
- Purchasing Power Index increased post-GST changes.  
- Regression model confirmed cement price declines had a **positive relationship** with consumer purchasing power.  

---

## 🔑 Key Insights  
- GST changes can simultaneously **stimulate consumption** and **trigger market volatility**.  
- Investors often move to **safe-haven assets like gold** during uncertain policy rollouts.  
- Predictive modeling shows commodity prices can be strong **proxies for consumer welfare**.  

---

## 📚 Tools & Libraries  
- Python 3.x  
- Pandas  
- Matplotlib  
- Scikit-learn (Linear Regression)  
- Jupyter Notebook  

---

## 🚀 Future Extensions  
- Use **real GST event data** from NSE/BSE and commodity exchanges.  
- Extend analysis to **FMCG and automobile sectors** (direct GST beneficiaries).  
- Apply **time-series forecasting** to predict long-term GST policy impacts.  

---

## 📜 License  
This project is licensed under the MIT License.  
