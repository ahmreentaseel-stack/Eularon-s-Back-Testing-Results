EULARON

Combined models · Back tests · Out-of-sample validation
 

This document shows our combined use of quantitative models’ sample of 20 independent backtests covering 9 trading days in this document. The complete set of 20 backtests, including the graphical representation of the model’s outputs and underlying data points, can be viewed on our GitHub.

In this document, we are showing results of short-term models; however, we do have long-term models as well.

METHODOLOGY — how these results were produced
Out-of-sample only
Every backtest is run on a period of market data the models have not seen during development. No result in this report comes from data the model was tuned against, so no overfitting.

Rolling windows
The 20 backtests are individual days, and the user should refer to the images in the GitHub to investigate further. The model is repeatedly tested on fresh data rather than judged on a single snapshot.
Point-in-time data
Each run only uses information that would have actually been available on the day of each prediction, avoiding lookahead into future data or later restatements.



















Eularon Quant Research
The outputs are solely for research purposes and are not investment advice of any kind.
