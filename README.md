# Ai-for-Finance 📈🤖
CAPM Analysis, portfolio optimization, risk management

You can find in this repo different projects, almost all data are pulled with API, otherwise if present please download the datasets in the same directory of the .ipybn before to execute it.
1. CAPM (Capital Asset Price Model) applied to one stock/portfolio with comparison with different timeframe and different balancing of holding during 2008 crisis period to evaluate performance.
2. Multi factor model and Market hedging with S&P500 Futures, I used as explainatory variables:
    * HML, SMB from Fama French
    * S&P500 as market index
    * Difference between BAA and AAA Us corporate bond yields.
    * 10-year treasury constant maturity minus 3-month treasury constant maturity.
3. Probit models to forecast binary outcomes such as recessions :
Find correlation between Recession data and the following variables:
    * HML, SMB from Fama French
    * Federal Funds Rate
    * S&P500 as market index
    * Difference between BAA and AAA Us corporate bond yields.
    * 10-year treasury constant maturity minus 3-month treasury constant maturity
    * GDP Growth.    

Use recession as dependent variable and and lag from 1 up to 12 quarter for the forecast with the difference of treasury yield as explanatory variable, then with the same logic use also the other variables as explanatory.  

4. Garch Volatility, find and use the volatility of the explanatory variables of the previous project and run a Probit model to see te predictive power.
5. High-Frequency-trading project based on forecasting algorithms of the Tesla stock with High-Frequency-Data of 1 min. The data are obtained from the
Refinitv platform since the Trento University provided us the access. The 2 approaches used are a simple linear regression and a more complex Neural Network based on an LSTM. HFT has become a huge market in the last years since it allow good prediction due to the huge amount of data available. The Deep Learning approach based on LSTM (Long-Short-Term-Memory) allows a more precise prediction compared to the classical basic regression model which is not able to fit very well the price oscillation of our stock.


