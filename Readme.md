# 📊 Multi-Asset Volatility & Correlation Analysis  
### Bitcoin (BTC), Ethereum (ETH), NSE Index, TSX Composite (XIC)

This project analyzes the price behavior, volatility patterns, return distributions, and correlations of major cryptocurrencies (BTC, ETH) against traditional equity indices (NSE & XIC). It highlights how different asset classes behave under varying market conditions and what this means for risk, diversification, and market behavior.

---

## 🚀 Objectives
- Compare volatility across crypto and equity markets  
- Analyze log-return distributions  
- Measure cross-asset correlations  
- Study time-varying rolling correlations  
- Identify volatility spikes and market stress events  
- Build a complete financial time-series analysis workflow  

---


## 📥 Data Sources
Data is downloaded using `yfinance` for:

- **BTC-USD** (Bitcoin)  
- **ETH-USD** (Ethereum)  
- **^NSEI** (Nifty 50 Index)  
- **^GSPTSE** (TSX Composite Index – used as XIC proxy)**  

Time Period: **2022-01-01 to 2025-11-15**

---

## 🧪 Methodology

### **1. Data Extraction**
Daily historical price data fetched via `yfinance`.

### **2. Return Calculations**
- Daily log returns  
- 60-day rolling volatility  

### **3. Correlation Analysis**
- Full-period correlation matrix  
- Rolling 60-day correlations  

### **4. Visualizations**
- Price Trends  
- Log-Return Distributions  
- Correlation Heatmap  
- Rolling Volatility  
- Price vs Volatility (BTC)  
- Volatility Spike Detection  
- Rolling Correlation Plots  

---

## 📈 Key Findings

### **1. Cryptocurrencies Are Extremely Volatile**
- BTC & ETH volatility spikes reach **0.8–1.2+**  
- Equity indices stay around **0.05–0.15**  
➡ Crypto = higher risk, event-driven volatility

### **2. Crypto Has Fat-Tailed Return Distributions**
- Wide, fat-tailed log returns  
- More extreme positive/negative movements  
➡ Equity markets have narrow return distributions

### **3. BTC & ETH Have Strong Correlation**
- BTC–ETH correlation: **0.8–0.9**  
➡ Crypto behaves like a single macro asset class

### **4. Crypto & Equity Correlation is Low**
- BTC/ETH ↔ NSE/XIC correlations: **0.1–0.4**  
➡ Useful for diversification

### **5. Rolling Correlation Fluctuates**
- Correlations change over time  
- Spike during major global events  
➡ Market relationships are dynamic

### **6. Volatility Spikes Mark Turning Points**
Spikes occur during:
- Reversals  
- Flash crashes  
- Global macro announcements  
➡ Good for anomaly detection

### **7. Price Crash → Volatility Spike**
- Volatility surges during downturns  
➡ Confirms volatility clustering theory

---

## 🖼️ Screenshots  
(Add files inside `/images` and these will display automatically)

### **Price Trends**
![Price Trends](images/price_trends.png)

### **Log Return Distribution**
![Log Return Distribution](images/log_return_distribution.png)

### **Correlation Heatmap**
![Correlation Heatmap](images/correlation_heatmap.png)

### **Rolling Volatility**
![Rolling Volatility](images/rolling_volatility.png)

### **BTC Price vs Volatility**
![BTC Price vs Volatility](images/btc_price_volatility.png)

### **Volatility Spikes**
![Volatility Spikes](images/vol_spikes.png)

### **Rolling Correlation**
![Rolling Correlation](images/rolling_correlation.png)

---

## ⚙️ How to Run the Project

### **Clone the Repository**
git clone https://github.com/your-username/Multi-Asset-Volatility-Analysis.git

### **Install Dependencies**
pip install -r requirements.txt

### **Launch Notebook**
jupyter notebook

Open:
notebooks/volatility_correlation_analysis.ipynb

---

## 📦 Requirements
pandas
numpy
matplotlib
seaborn
yfinance
scipy

---

---

## 👤 Author
**Souvik Ghorui**  
*(Add GitHub/LinkedIn profile here)*


