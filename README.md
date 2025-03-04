This is the code that determines the weight of your financial assets.
Your utility function is represented by the sortino function
Because it pulls data from Yahoo Finance, you can only build portfolios with assets whose tickers exist on that site.
It also takes into account the exchange rate, and the uploaded code was constructed using the Korean-US exchange rate.
One of the unusual things about this portfolio is that it weights the time series differently. You can use uniform_weighting if you want to give equal weight to the past and present, logarithm if you want to give a little more weight to the present, and linear_weighting if you want to give even more weight to the present. (We also considered Exponential, but ruled it out because it would result in an uneven asset allocation.)
It's not the most user-friendly code, but it's also not the most difficult code, so it would be nice to understand it and use it (try Chat gpt).
You can do back testing specific timeframes for a given portfolio.
Please leave a comment with any issues or advice and we'll fix it often
