# Portfolio_Construction
Our strategy is to invest in a combination of low-risk assets, such as government bonds, and high-risk assets, such as technology stocks. The goal of this strategy is to balance the potential for higher returns from the high-risk assets with the stability provided by the low-risk assets.

## stock data
To implement this strategy, we chose 4 technology stocks based on Nasdaq 100 and S&P 500, respectively APPL (APPLE INC.), AMZN (AMAZON COM INC.), GOOGL (ALPHABET INC.) and TSLA (TESLA MOTORS INC.) as our high-risk(and possibly high returns) assets. We then selected 10 Year Treasury Bond ETF (TLH) as our risk-free asset.

## project structure
This jupyter notebook built a static portfolio that buy once and does not rebalance. Our portfolio allocation based on the historical performance of these assets, mainly based on the log excess returns computed from the data. We used a Markowitz's portfolio optimization theory and decided our weighted allocation based on the max-sharpe ratio to balance the level of risk and return, choosing the portfolio with the highest expected return at a certain risk level. We're just doing a long portfolio, which means that we just want to go long and don't short our holding stocks. Moreover, we ran a Monte-Carlo simulation to simulate the portfolio's performance in the upcoming 6 month, calculated the possibility of losing 20% of the returns, to see if we can take the loss and stick with our strategy.
