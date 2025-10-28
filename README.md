
##  Datasets
1. **Historical Trader Data (Hyperliquid)**  
   Columns include: `account`, `execution price`, `size tokens`, `size usd`, `closed pnl`, `timestamp ist`, etc.

2. **Bitcoin Market Sentiment (Fear & Greed Index)**  
   Columns include: `timestamp`, `value`, `classification`, `date`.

Both datasets are publicly provided by the Web3 Trading Team as part of the assessment.


##  Steps Performed
1. Data cleaning and preprocessing  
2. Timestamp conversion and date extraction  
3. Merging datasets by `date`  
4. Feature engineering (PnL, Volume, Fees, Sentiment Value)  
5. Exploratory data analysis (EDA)  
6. Visualization and insight generation  
7. PDF report creation with summary and plots  


##  Key Insights
- **Greed phases** show higher trade volume and transaction fees, reflecting risk-seeking behavior.  
- **Fear phases** lead to smaller trades but slightly improved average PnL, suggesting disciplined decision-making.  
- Correlation between sentiment value and profitability is weak, implying that market optimism doesn’t always translate to better returns.


##  Report
All findings, visualizations, and interpretations are summarized in [`ds_report.pdf`](./ds_report.pdf).

---

##  Google Colab Link
[View Notebook](https://colab.research.google.com)


**Tanvi Sundarkar**  
3rd Year CSE, MANIT Bhopal | BS Data Science, IIT Madras  
