# Optimizing Pairs Trading: Integrating Regime Switching to Test Various Pairs Trading Strategies
Annabel and Sarah's GISP 0005 Final Project

## Methods
- Test various pair selection strategies: SSD, co-integration, clustering
- Test HMM fitting with 2 states: high and low mean
- Develop various strategies to model the spread of a pair of stocks and experiment with different trading strategies (Vasicek model, 2-state model, rolling mean distance method, and 2-state distance methods)
  - Fit each model on the pair to optimize parameters (e.g., mean and std. dev.) and use these parameters to set thresholds for the trading rules
  - Fit various models over a 1-year formation period, then trade for 1 month. During fitting, re-select top pairs based on various methods and refit the model with new parameters, adjusting the trading strategy. After each trading period, roll the formation window forward by 1 month (21 trading days) and repeat.
- Use profit/returns to assess each strategy

## Proposal
https://docs.google.com/presentation/d/1u7MUJpSb3D-5mXtt4nKKosjoLeSfjl6KNkZ8664gWU0/edit#slide=id.g30b5794653f_0_22

## Final Presentation
https://docs.google.com/presentation/d/1A3yLia2gtrrRuAN6VQju0ivt5U1cEaR2audm3hgLbH8/edit#slide=id.g2d69eb44565_0_89


## References
Ang, Andrew, and Allan Timmermann. "Regime Changes and Financial Markets." Annual Review of Financial Economics 4 (2012): 313-337. https://doi.org/10.1146/annurev-financial-110311-101808

Bai, Y., & Wu, L. (2017). Analytic value function for optimal regime-switching pairs trading rules. Quantitative Finance, 18(4), 637–654. https://doi.org/10.1080/14697688.2017.1336281

Endres, S., & Stübinger, J. (2019). A flexible regime switching model with pairs trading application to the S&P 500 high-frequency stock returns. Quantitative Finance, 19(10), 1727–1740. https://doi.org/10.1080/14697688.2019.1585562

Krauss, Christopher. "Statistical Arbitrage Pairs Trading Strategies: Review and Outlook." Journal of Economics & Statistics, 09 May 2016. https://doi.org/10.1111/joes.12153

(*) Yang, J.-W., Tsai, S.-Y., Shyu, S.-D., & Chang, C.-C. (2016). Pairs trading: The performance of a stochastic spread model with regime switching—Evidence from the S&P 500. International Review of Economics & Finance, 43, 159–174. https://doi.org/10.1016/j.iref.2015.10.036

(*) primary reference paper


## Other Helpful Links
ETF Pairs Trading Kaggle: https://www.kaggle.com/code/christopherchiarilli/etf-pairs-trading-signals-spy-qqq

JK Chelimo's Vasicek Model Dissertation: https://su-plus.strathmore.edu/items/b948c8a0-e9d4-484e-8beb-c198651ad3f4

Hudson Thames Blogs: https://hudsonthames.org/optimal-stopping-in-pairs-trading-ornstein-uhlenbeck-model/, 
https://hudsonthames.org/pairs-trading-with-markov-regime-switching-model/ 


