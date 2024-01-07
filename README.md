TESLA STOCK PREDICTION MODEL

Author : Okeke Felix Emeka

Email : okeke243@gmail.com linkedin : linkedin.com/in/felix-emeka-281629129

**TESLA STOCK PREDICTION MODEL**
In this project, Exploratory Data Analysis is carried out on TESLA Stock data obtained from Yahoo Finande: https://finance.yahoo.com/quote/TSLA/history/
Here, EDA is performed with Python. Furthermore, python keras package is used to predict the stock prices for the month of January and also predicted percentage increase or decrease in the stock prices.

**METHODOLOGY**
**PART A: DATA RETRIEVAL AND PROCESSING**
First and foremost, data is collected from the above mentioned source for the period of 1st January 2019 till 4th January 2024. The gathered data is then pre-processed and cleaned by removing empty rows and duplicates.

**PART B: EXPLORATORY DATA ANALYSIS (EDA)**
The second part of this project is Exploratory Data Analysis (EDA), which is performed in four different ways.
1.	**Assessing basic stock performance**: In this first step, closing prices of TESLA stocks are simply plotted against the timeframe to understand basic movements of stock prices.
2.	T**rend Analysis using Simple Moving Average (SMA)**: Simple Moving Averages of stocks is carried out over a 50 days, 100 days and200 days interval. One of the primary purposes of using SMA in stock analysis is to identify trends in stock prices. SMA smoothens out price fluctuations over a specified period, making it easier to recognize the underlying trend. If the current stock price is consistently above the SMA, it may indicate an uptrend, while prices below the SMA may suggest a downtrend. This helps traders and investors make informed decisions about buying or selling stocks based on the prevailing trend. 
SMA can act as dynamic support and resistance levels. In technical analysis, support is a price level where a stock tends to stop falling, and resistance is a level where it tends to stop rising. SMA lines can serve as these levels, and traders often observe how the stock price interacts with the SMA
3.	**Seasonal Trend Analysis:** Here, stocks are analyzed based on the monthly average of their closing prices. This information can be useful for predicting future stock price movements during specific seasons. It also determines the lag at which stock prices exhibit significant correlations, allowing for the identification of seasonality and potential predictive patterns. By calculating moving averages over specific time intervals that correspond to the seasonal pattern, the function helps in identifying trends and removing short-term noise

4.	**Volatility Analysis:** The following are show the Description and basic functions of the Volatility Analysis:
**a)	Risk Management:**
**Use: Assessing and Managing Market Risk**
**Description**: Volatility is a key indicator of market risk. Higher volatility implies greater price fluctuations, which can result in larger potential losses or gains. Investors and portfolio managers use volatility analysis to quantify and understand the risk associated with specific financial instruments or portfolios. By incorporating volatility measures into risk models, they can adjust portfolio allocations, set stop-loss levels, or implement hedging strategies to mitigate the impact of market fluctuations.

**b)	Option Pricing:**
**Use: **Determining Fair Value of Options
Description: Volatility plays a crucial role in the pricing of financial derivatives, especially options. The Black-Scholes model and other option pricing models incorporate volatility as a key parameter. Higher volatility increases the potential price movement of the underlying asset, leading to higher option premiums. Traders and market participants use volatility analysis to estimate future price movements and, consequently, to determine the fair value of options. This information is valuable for making informed decisions on buying or selling options.

**c)	Trading Strategies:**
**Use:** Developing and Adjusting Trading Strategies
**Description:** Volatility analysis is integral to the development and adjustment of trading strategies. Traders often adapt their strategies based on the prevailing market volatility. For instance, in periods of high volatility, trend-following strategies may be adjusted to account for larger price swings, while in low-volatility periods, range-bound strategies may be more effective. Volatility-based indicators, such as the Average True Range (ATR) or Bollinger Bands, are commonly used by traders to set stop-loss levels, identify potential entry points, and adjust position sizes based on market conditions.
Volatility Analysis is carried out to understand how frequently stock prices can vary. This helps in understanding the risks involved in investing in a stocks and also it shows the tendency of the stock to diverge from its flow frequently.

**PART C: PREDICTING JANUARY STOCK PRICES**
To predict stock prices for the month of January 2024, LSTM regression algorithm is used. LSTM can store memories of trends observed within the data during training process which can help finding patterns with unstable data and making more accurate future predictions. Since stock data in most cases is unstable (frequent changes in stock prices), LSTM can be best used in such situations.

**ANALYSIS**
After performing EDA, the overall analysis suggested that looking at the historical data, it is risky to invest in Tesla stocks at the moment. Tesla stocks have been highly volatile resulting in higher risks in investments. It is recommended for the investors to hold onto the stocks at the moment. 
Second point observed is that Tesla stocks have been declined for over 2 years (since 2021). Hence, even if the stocks are at lower rates at the moment, it is not recommended to invest in them at present due to their gradual decrease in prices over the period of last 2 years (2021 to 2023). 
Also, the stocks have been highly volatile showing increased risks. Although, it is observed that Tesla stock prices tend to increase around end of August till mid of October every time indicating best time to sell the stocks (based on historical data of the last 3 years obtained).

**PREDICTIONS OBTAINED**
Predictions made for Tesla stocks in January were fairly in a good state since it showed a slight increase in stock prices by 4%.
