
Trading Sentiment Analysis 

COLAB LINK (FOLDER)
https://drive.google.com/drive/folders/1xUuikPlazupOjnb6fLVuIj2AWuKV-7UD?usp=sharing

NOTEBOOK_1 
https://colab.research.google.com/drive/11wGmuKNxEsebFyJPzDStQABDdUevfy-o?usp=sharing

NOTEBBOK_2
https://colab.research.google.com/drive/1q79WCPmUrFGC8pOHHhVpt993nBHGH9yU?usp=sharing


Project Overview
This project analyzes the relationship between trading behavior and the Fear & Greed Index to uncover how market sentiment influences decision-making, profitability, and risk patterns. It combines quantitative trading data with emotional indicators to surface trends that can guide smarter, sentiment-aware strategies.

Objective

* Examine how emotional states (fear, greed, etc.) influence:

  * Trading volume
  * Profit and loss (PnL)
  * Buy vs sell behavior
  * Leverage and risk exposure
* Identify behavioral patterns that align or diverge from overall market sentiment
* Develop insights to support strategic trading decisions under different sentiment conditions

Dataset
* Columns include:

  * Date, Buy/Sell, Trade Size, Size USD, Closed PnL, Leverage, Net PnL
  * Emotion Label (Extreme Fear, Fear, Neutral, Greed, Extreme Greed)
  * Daily Fear & Greed Index Score

Key Visualizations

1. Trade Volume vs Fear & Greed Index Over Time
2. Average Closed PnL by Emotion
3. Buy vs Sell Volume Across Emotional States
4. Closed PnL vs Fear & Greed Index Over Time
5. Daily Net PnL vs Fear & Greed Index
6. Correlation Heatmap
7. Average Trading Volume by Fear & Greed Level
8. Fear & Greed Index Distribution

Tools and Technologies
Python (Pandas, Seaborn, Matplotlib)
Jupyter Notebooks
GitHub for version control and collaboration

Repository Structure
ds\_mansi/

* notebook\_1.ipynb : Main analysis and primary visualizations
* notebook\_2.ipynb : Extended and additional visual insights
* outputs/ : Saved visualizations
* README.md : Project overview and documentation

Insights and Outcomes

* Emotional states like Extreme Greed correspond to higher average profits but also increased volatility
* Fear triggers more sell orders, reducing overall profitability
* Sentiment data alone does not fully predict profitability, but when combined with trading indicators, it enhances decision-making
* Correlation analysis reveals that trading volume and net PnL have a weak to moderate relationship with sentiment scores

Conclusion

This analysis bridges trading metrics with psychological indicators to better understand how market sentiment affects trader behavior. The findings support the use of sentiment-aware models in risk management, timing entries and exits, and optimizing trading strategies.

