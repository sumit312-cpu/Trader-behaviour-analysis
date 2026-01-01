# Trader-behaviour-analysis
 Trader Behaviour Analysis with Market Sentiment  

### Project Overview :-
This project analyzes the relationship between *crypto market sentiment* (Fear–Greed Index) and *trader behaviour based on trade outcomes*.  
The goal is to understand whether trading performance changes across different sentiment phases such as *Fear, Neutral, Greed, and Extreme Greed*.

The analysis is performed using Python in Jupyter Notebook with data cleaning, merging, grouping, visualization, and behavioural insights.

---

###  Datasets Used :-
1️⃣ *Fear–Greed Sentiment Dataset*  
Contains daily market sentiment values categorized into phases.

2️⃣ *Trades Dataset*  
Contains individual trade records including timestamp, PnL information, and trade outcomes.

---

### 🛠️ Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Jupyter Notebook  

---

###  Steps Performed in the Project :-
1. *Import datasets & preview structure*  
2. *Data cleaning & timestamp conversion*  
3. *Generate profit–loss flag (pnl_flag)*  
4. *Create date column & align trades with sentiment*  
5. *Group analysis by sentiment & trade outcome*  
6. *Create days-count table (sentiment duration)*  
7. *Generate trade performance summary*  
8. *Visualization of trades vs sentiment*  
9. *Insights & behavioural observations*  
10. *Final conclusion*
11. *Export final merged dataset (CSV)*

---

###  Key Insights :-
- Profit trades occur across all sentiment phases, but trading activity is *higher during Greed periods*.  
- Loss trades are present in every phase, meaning *market risk cannot be eliminated*.  
- Traders tend to show *confidence-driven behaviour in Greed* and cautious participation during Fear.  
- Sentiment affects trading outcomes, but *discipline and risk-management play a major role*.

---

### Final Conclusion :-
Market sentiment has a measurable influence on trader behaviour, but it is *not the only factor* driving performance.  
A balanced strategy combining *sentiment awareness, timing, and risk-management* results in more consistent outcomes in volatile crypto markets.
