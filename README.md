# Machine-Learning-Model-for-Corporate-Acquisition


Predicting Takeover Targets in the EU: A Data-Driven Approach

Key Insights at a Glance

1. The M&A Boom in Europe 
📈 Deal value surged from $383B (2010) to $1.26T (2021)—a 229% increase (Mergermarket, 2022).  
🌍 28% of global M&A value in 2021 came from the EU, driven by cheap financing, Brexit adjustments, and private equity (42% of deals).  

Takeover activity fluctuated but remained strong, peaking in 2006 and 2008. 

---

2. What Makes a Company a Takeover Target?
The study tested 19 financial variables across 8,684 firms (1,274 targets vs. 7,410 non-targets). Key predictors:  

✅ Undervaluation (Low Tobin’s Q, EBITDA/Firm Value)  
✅ Poor Performance (Low ROCE, Net Profit Margin)  
✅ High Liquidity & Low Leverage (More cash, less debt)  
✅ Smaller Size (Lower market cap = easier acquisition)  

Targets had lower profitability (-1.3% vs. -0.7% net margin) and higher liquidity (8.7% vs. 4.9% working capital/TA).

---

3. Machine Learning Outperforms Traditional Models
The study compared three models:  

| Model               | AUC Score | Key Strength |  
|---------------------|----------|--------------|  
| Logistic Regression | 0.5747  | Simple, interpretable |  
| Lasso Regression   | 0.5924  | Reduces overfitting |  
| Random Forest     | 0.6791 | Best at detecting patterns |  

 
Random Forest’s AUC of 0.68 means it correctly ranks targets **68% of the time**—far better than chance (50%).

---

4. Can You Profit from Predicting Takeovers?
💰 Top 25% Predicted Targets → 8.52% avg. annual return 
📉 Non-Targets → 4.63% avg. annual return
📊 Actual Targets → 10.08% return (statistically significant!) 

After adjusting for risk (Fama-French 5-Factor Model), predicted targets still delivered 1.91% monthly alpha.  

---

5. Limitations & Future Research 
🔍 Sample Bias: Only public firms (excludes private deals).  
📉 Macro Changes: Models don’t adapt to shifting M&A motives over time.  
🤖 Next Steps: Test neural networks, include more sectors, and track post-merger performance.  

---

Final Takeaway
This research proves that financial data + machine learning can identify likely takeover targets—with real investment potential. For investors, it’s a roadmap to spotting undervalued gems. 

---  
*Data Sources: Datastream, SDC Platinum, IMAA, Mergermarket (2022).*  
*Models: Logistic, Lasso, Random Forest (Python).*  

