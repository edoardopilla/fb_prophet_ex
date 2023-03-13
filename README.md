# fb_prophet_ex

**_Showcasing effect of outliers and exposing seasonality in GameStop and JPY/USD datasets using Prophet._**

Time series data about GameStop market prices and exchange rates between the Japanese Yen and the American Dollar are used to highlight two of the most important factors captured by Facebook's Prophet model, namely the effect outliers have on the forecast, including confidence intervals, and the seasonality contained in a dataset.

GameStop dataset is transformed into returns from prices to move from a non stationary series to a stationary one, and to show how the aforementioned library is robust to missing data.
