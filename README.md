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



