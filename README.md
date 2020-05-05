# Prospective Utility - Amos Tversky and Daniel Kahneman 

Objective: Explore whether prospect theory creates excess demand for certain stocks on the stock market.

Data: Monthly returns for all the NYSE stocks from 1980 to today.

Steps taken:

(1) Sorted stocks based on their prospective utility at the end of the month t. Then, created 10 portfolios with equal-weights based on these sorts. For each of these 10 portfolios, I computed the average log-market capitalization, the average raw monthly return in month t + 1, the resulting CAPM α, and the resulting market β.

(2) Computed the monthly returns of a strategy that goes long P1 (the bottom portfolio of stocks with low prospective utility) and short P10 (the top portfolio of stocks with high prospective utility). Then, I computed the excess returns, CAPM α and Sharpe ratio of this strategy over the whole sample period.

(3) Analyzed how the strategy’s CAPM α changes if the investor perceives probability correctly (γ = δ = 1)

(4) Analyzed how the strategy’s CAPM α changes if the investor’s preferences only exhibit loss aversion (i.e. α = 1)
