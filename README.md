# 📈 Managing an Option Portfolio Using Python
### FIN F414 – Financial Risk Analytics & Management

This project focuses on analyzing and managing an options portfolio using real stock market data from the NIFTY/NSE universe. It includes data extraction, statistical analysis, Black-Scholes-Merton pricing, Greeks computation, implied volatility estimation, portfolio hedging, and Value-at-Risk (VaR) analysis.

---

## 🔍 Project Overview

### **Part A — Data & Statistics**
- Selected a stock from NIFTY 200  
- Extracted 3 months of daily prices (yfinance)  
- Calculated log returns, annualized volatility, skewness, and kurtosis  

### **Part B — BSM Option Pricing**
- Defined 5 strike prices (ATM, ±2%, ±5%)  
- Considered 3 maturities (30, 60, 90 days)  
- Priced call and put options using the Black-Scholes-Merton model  

### **Part C — Greeks & Volatility**
- Computed Delta, Gamma, Vega, Theta, Rho  
- Estimated Implied Volatility from option chain  
- Built a volatility surface (strike × maturity × IV)

### **Part D — Portfolio & Hedging**
- Constructed an options portfolio  
- Computed portfolio-level Greeks  
- Performed Delta and Gamma hedging  
- Simulated PnL under ±1% and ±2% price changes  

### **Part E — Risk Analysis (VaR)**
- Calculated 95% & 99% VaR using:
  - Parametric (variance–covariance) method  
  - Historical simulation (60-day window)
- Compared hedged vs unhedged portfolio risk  

---

## 📂 Repository Contents
- **Part_A_Statistical_Analysis.xlsx**  
- **Part_B_BSM_Option_Pricing.xlsx**  
- **Part_C_Greeks_Volatility_Analysis.xlsx**  
- **Part_D_Portfolio_Hedging.xlsx**  
- **Part_E_VaR_Analysis.xlsx**  
- **options_pricing_project.ipynb**  
- **README.md**

---

## 👤 Author
**Divyanshu**  
BITS Pilani | Course: FIN F414 – Financial Risk Analytics & Management
