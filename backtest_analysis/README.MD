EULARON
Combined models · Back tests · Out-of-sample validation
 

This document shows our combined use of quantitative models’ sample of 20 independent backtests covering 9 trading days in this document. The complete set of 20 backtests, including the graphical representation of the model’s outputs and underlying data points, can be viewed on our GitHub.

BACKTEST RESULTS — 09 out-of-20 sample runs
RUN	PERIOD TESTED	REGIME 01	Time
(GMT + 3)	% Drawdown	% Move	Exit Time
(GMT + 3)	Regime 02	Time
(GMT +3)	% Drawdown	% Move	Exit time
(GMT + 3)
XAUUSD	25/09/2026	BUY	10.00	-0.08	+0.52	12.36	SELL	16.00	-0.11	+0.65	17.08
XAUUSD	24/09/2026	BUY	14.12	-0.05	+0.62	16.00					
XAUUSD	23/09/2026	SELL	09.50	-0.11	+0.75	14.00	BUY	18.40	-0.13	+0.36	21.00
XAUUSD	22/09/2026	BUY	11.24	-0.20	+0.73	12.00	BUY	19.00	-0.05	+0.85	20.58
XAUUSD	21/09/2026	BUY	12.36	-0.00	+0.61	14.40					
XAUUSD	18/09/2026	BUY	08.00	-0.10	+0.70	09.45	SELL	12.12	-0.50	+0.47	12.47
XAUUSD	18/09/2026	BUY	18.30	-0.20	+0.89	20.30					
XAUUSD	17/09/2026	BUY	08.40	-0.05	+0.80	08.40	SELL	15.55	-0.15	+0.45	18.05
XAUUSD	16/09/2026	SELL	18.08	-0.21	+1.05	21.30					
XAUUSD	15/09/2026	SELL	10.00	-0.16	+0.55	11.10	BUY	12.50	-0.11	+0.45	14.55

In this document, we are showing results of short-term models, however we do have long-term models as well.

METHODOLOGY — how these results were produced
Out-of-sample only
Every backtest is run on a period of market data the models have not seen during development. No result in this report comes from data the model was tuned against, so no overfitting.

Rolling windows
The 20 backtests are individual days, and the user should refer to the images in the GitHub to investigate further. The model is repeatedly tested on fresh data rather than judged on a single snapshot.
Point-in-time data
Each run only uses information that would have actually been available on the day of each prediction, avoiding lookahead into future data or later restatements.



















Eularon Quant Research
The outputs are solely for research purposes and are not investment advice of any kind.
