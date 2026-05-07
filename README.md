# ts-forecasting-spy

Time Series Forecasting: An Exploratory Study Using S&P 500 ETF Data

Background
This study explores time series forecasting methods applied to the SPY-USA ETF using ~10 years of monthly price data (2016–2025). Financial markets are volatile and difficult to predict, making forecasting both valuable and challenging. Several models were tested, including naïve, seasonal naïve, drift, exponential smoothing (ETS), and an ensemble approach. Results show that simple trend-based models outperform seasonal approaches, with the additive ETS model providing the most accurate forecasts.

Methodology
Monthly price data spanning 10 years (2016 to 2025) for the SPY-USA was analyzed from FactSet. Exploratory analysis included trend visualization, autocorrelation, seasonal-trend using LOESS (STL) decomposition, and inflation-adjusted comparisons. The following models were then tested to forecast the SPY-USA ETF price: ETS, drift, naïve, seasonal naïve, and ensemble.

Results
The additive ETS model (Holt’s Linear Trend) performed best, with the drift model performing similarly well, capturing the upward trend. The basic naïve model provided a reasonable baseline but lacked trend modeling. The seasonal naïve approach under‑predicted the strong upward trend and exhibited autocorrelated residuals, making it the least reliable. The ensemble model performance was reduced due to inclusion of the weaker seasonal model.
