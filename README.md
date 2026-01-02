
##  Trader Behaviour Analysis :-

This project explores how *market sentiment (Fear–Greed Index)* influences  
*trader behaviour, risk-taking patterns, and trade performance (Profit/Loss)* using real trading execution data.


##  Objective :-
To analyze whether traders behave differently across market sentiment phases, and identify
behavioural patterns such as *cautious trading during fear* vs *risk-seeking behaviour during greed*.

---

##  Datasets Used :-
1️⃣ *Bitcoin Market Sentiment (Fear/Greed Index)*  
- Columns: timestamp, value, classification, date

2️⃣ *Trader Execution Data (Hyperliquid)*  
- Columns: account, symbol, execution price, size, side, leverage, pnl_flag, time, etc.

## Final merged dataset is exported as  
*final_trader_sentiment_dataset.csv* (stored using Git LFS due to file size)


##  Tools & Libraries :-
- Python  
- Jupyter Notebook  
- pandas, numpy  
- matplotlib / seaborn

##  Analysis Workflow :-
1. Data cleaning & preprocessing  
2. Timestamp normalization & date-level merging  
3. Sentiment-wise trade distribution  
4. Profit vs Loss trade summary  
5. Behavioural insights across sentiment phases  
6. Visualization of trade outcomes

## Key Insights (Summary) :-

-  *Fear Phases* → Traders show *defensive behaviour* and cautious trade execution  
-  *Greed Phases* → Higher trading activity & *greater risk-taking tendency*  
-  *Extreme Greed* → Signs of *over-confidence*, probability of losses increases 
-  *Most trades still close in profit*, but loss trades remain & require disciplined risk-management
-   Traders in extreme Greed phases showed increased trade count but lower average P&L ratio.
- During Fear phases, profitable trades were fewer but more disciplined (lower variance)

These findings highlight how *market psychology influences trading behaviour and outcomes*.

##  How to Run the Notebook :-
1. Clone or download the repository  
2. Ensure the dataset file is in the same directory  
3. Open trader_behaviour_analysis.ipynb in Jupyter Notebook  
4. Run all cells sequentially

##  Project Files :-
- trader_behaviour_analysis.ipynb — Full analysis notebook  
- final_trader_sentiment_dataset.csv — Final processed dataset (LFS)  
- Screenshots — Output & result evidence  

## Role Relevance :-
This project demonstrates:

- Data cleaning & preprocessing  
- Behavioural analytics & trend interpretation  
- Exploratory Data Analysis (EDA)  
- Real-world trading dataset handling  
- Insight-driven storytelling for decision-making


## 🧑‍💻 Author
*Sumit Tiwari*  
B.Tech — Computer Science (2025)  
Email: sumittiwari62642004@gmail.com
