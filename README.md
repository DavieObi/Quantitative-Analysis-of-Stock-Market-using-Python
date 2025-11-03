# 📊 Quantitative Analysis of Stock Market using Python

## 🧾 Project Overview

In this project, we performed a **quantitative analysis of stock market data** using Python. The goal was to explore various statistical and analytical concepts to understand the performance, volatility, and relationships between multiple stocks over a specific period.

We utilized data for four major companies — **Apple (AAPL)**, **Alphabet (GOOG)**, **Microsoft (MSFT)**, and **Netflix (NFLX)**. The dataset included essential stock information such as **Open, High, Low, Close, Adjusted Close,** and **Volume** for each trading day.

---

## ⚙️ Tools and Libraries Used

* **Python**
* **Pandas** – for data manipulation and statistical analysis
* **Plotly Express & Graph Objects** – for interactive data visualization
* **Plotly Subplots** – for multi-stock comparisons
* **NumPy** – for numerical computations

---

## 📁 Dataset Description

The dataset (`stocks.csv`) contained the following columns:

| Column        | Description                                                |
| ------------- | ---------------------------------------------------------- |
| **Ticker**    | Stock ticker symbol (AAPL, GOOG, MSFT, NFLX)               |
| **Date**      | Trading date                                               |
| **Open**      | Opening price for the day                                  |
| **High**      | Highest price of the day                                   |
| **Low**       | Lowest price of the day                                    |
| **Close**     | Closing price of the day                                   |
| **Adj Close** | Adjusted closing price (accounts for dividends and splits) |
| **Volume**    | Number of shares traded on that day                        |

---

## 🧮 Analyses Performed

### 1️⃣ Descriptive Statistics

We computed descriptive statistics for the **closing prices** of each stock.
This included **mean, median, standard deviation, minimum, maximum,** and **quartiles**.

#### Key Insights:

* **AAPL** had an average closing price of **$158.24**, with moderate volatility.
* **GOOG** had the lowest mean closing price (**$100.63**) and the lowest volatility, indicating price stability.
* **MSFT** had a higher mean (**$275.04**) with significant variability.
* **NFLX** had the highest mean (**$327.61**) and the greatest standard deviation, showing the highest volatility.

---

### 2️⃣ Time Series Analysis

We plotted the **closing prices over time** for all four stocks using interactive line charts.
This visualization helped identify **trends and fluctuations**.

#### Observations:

* **AAPL** and **MSFT** showed a **general upward trend** over the period.
* **NFLX** exhibited more pronounced **price swings** compared to others.
* **MSFT** and **NFLX** traded at **higher price levels** than AAPL and GOOG throughout the dataset.

---

### 3️⃣ Volatility Analysis

We calculated the **standard deviation** of the closing prices to measure volatility.

#### Insights:

* **NFLX** had the **highest volatility**, indicating frequent and wide price changes.
* **MSFT** followed closely, showing notable fluctuations.
* **AAPL** and **GOOG** were more stable, with **GOOG** being the **least volatile**.

---

### 4️⃣ Correlation Analysis

We computed and visualized the **correlation matrix** of closing prices using a heatmap.

#### Findings:

* Most stocks were **positively correlated**, meaning their prices tended to move in the same direction.
* **AAPL** and **MSFT** exhibited a **strong positive correlation**, suggesting that their stock movements were closely aligned.
* **NFLX** had a weaker correlation with the others, indicating that its price changes were more independent.

---

### 5️⃣ Comparative Performance Analysis

We calculated the **percentage change in closing prices** from the start to the end of the period for each stock.

#### Results:

* **MSFT** showed the **highest positive growth (~+16.10%)**.
* **AAPL** followed with a **+12.23%** increase.
* **GOOG** experienced a **slight decline (-1.69%)**.
* **NFLX** had the **largest drop (-11.07%)**, reflecting a period of underperformance.

---

### 6️⃣ Daily Risk vs. Return Analysis

We calculated the **average daily returns** and their **standard deviations** (used as a proxy for risk).
A scatter plot was used to visualize the **risk-return trade-off**.

#### Insights:

* **AAPL** had the **lowest risk** with a **positive average return**, making it the most stable investment.
* **MSFT** had the **highest average daily return**, though with moderate risk, suggesting an optimal balance for growth-oriented investors.
* **GOOG** had slightly **negative average returns** despite moderate volatility.
* **NFLX** showed **high risk** and **negative returns**, indicating a poor risk-return balance.

---

## 💡 Key Insights Summary

| Stock | Mean Close | Volatility | % Change | Risk | Return | Observation |
|--------|-------------|-------------|-----------|--------|---------|--------------|
| **AAPL** | 158.24 | Moderate | +12.23% | Low | Positive | Stable and consistent |
| **GOOG** | 100.63 | Low | -1.69% | Moderate | Negative | Mild decline, low volatility |
| **MSFT** | 275.04 | High | +16.10% | Moderate | Highest | Strong performer |
| **NFLX** | 327.61 | Very High | -11.07% | High | Negative | Volatile and underperforming |

---

## 🧭 Conclusion

In conclusion, our **quantitative stock market analysis** provided valuable insights into the **performance, volatility, and correlations** among four major technology stocks.

* **MSFT** emerged as the best performer overall, combining **strong returns with moderate risk**.
* **AAPL** demonstrated **steady growth and low volatility**, making it a **safe and stable investment**.
* **GOOG** maintained stability but showed minor negative returns, indicating **neutral performance**.
* **NFLX** stood out as the **most volatile and risky**, with negative returns, suggesting a **poor short-term investment** during this period.

This project showcased how **Python-based quantitative techniques** can effectively reveal market behavior, compare investments, and support data-driven financial decision-making.

---

## 📈 Future Work

In the future, this analysis could be extended by:

* Incorporating **technical indicators** (e.g., Moving Averages, RSI, MACD).
* Performing **portfolio optimization** using **Markowitz’s Modern Portfolio Theory (MPT)**.
* Expanding the dataset to include **more stocks and longer time periods** for broader analysis.
* Using **machine learning models** to forecast future stock prices based on historical data.
