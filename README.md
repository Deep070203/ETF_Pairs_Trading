# ETF_Pairs_Trading
Exchange-Traded Funds (ETFs) can often show strong correlations, especially when they're tracking similar sectors or indexes.

A classic example of two highly correlated ETFs would be the SPDR S&P 500 ETF Trust (SPY) and the Invesco QQQ Trust (QQQ). Both of these ETFs track large-cap U.S. equities, with the SPY focused on the broader S&P 500 index and the QQQ focused on the tech-heavy NASDAQ-100 index. Given the large overlap in the companies they track, these two ETFs tend to move together quite closely.

Remember that while these ETFs are generally correlated, they may not always move together perfectly. Market conditions, sector-specific issues, and differences in the exact composition of the ETFs can cause divergences. These divergences are exactly what we are looking for when trading spreads, as they can provide profitable trading opportunities if the prices revert back towards their historical relationship.

I will attempt to generate a trade signal using ETF Pairs. Given the complexity of the problem and the required methods, it will be a sequential process involving several steps. Here is an outline:

Cointegration Analysis and Pair Trading Strategy

Test for cointegration between 2 ETFs. If the prices are cointegrated, construct the spread series and perform a statistical analysis on it. 
Develop a pair trading strategy based on the statistical properties of the spread.

Modeling the Spread Using the Ornstein-Uhlenbeck (OU) Process

Predicting the Spread using Support Vector Machine (SVM) Model



Insipred from a Kaggle Notebook by CHRISTOPHER CHIARILLI
