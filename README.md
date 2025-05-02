# Gold Price Sentiment Analysis

This project analyzes historical gold price data and related news headlines to uncover patterns, sentiment trends, and financial insights. It combines time series analysis with natural language processing to better understand how sentiment impacts gold market behavior.

## 📊 Dataset Overview

The dataset includes the following columns:

- `timestamp`: Date of the record
- `open`, `high`, `low`, `close`: Gold price metrics
- `volume`: Trading volume
- `currency`: Currency of the price
- `unit`: Unit of measurement (e.g., ounce)
- `headlines`: News headlines related to gold prices
- `range`: Daily price range (`high - low`)
- `year`, `month`: Extracted year and month
- `daily_change`: Absolute daily change in closing price
- `MA30`, `MA100`: 30-day and 100-day moving averages
- `price_change`: Daily % change in closing price
- `sentiment_score`: Sentiment polarity score from headlines
- `sentiment_label`: Sentiment classification (`positive`, `negative`, `neutral`)
- `inflation`, `recession`: Flags for presence of keywords in headlines

## 📌 Key Insights

- **Average Closing Price**: Measured over the dataset’s time span
- **High/Low Extremes**: Identified peaks and dips in gold closing prices
- **Daily Ranges**: Examined intraday volatility
- **Monthly/Yearly Trends**: Assessed seasonality and annual shifts
- **Moving Averages**: Visualized trends using MA30 and MA100
- **Sentiment Influence**: Correlated headlines with price fluctuations
- **Keyword Impact**: Analyzed the effect of terms like “recession” and “inflation”

## 📈 Visualizations

- **Line Plots**: Gold price trends and moving averages
- **Box Plots**: Distribution of price changes by sentiment or keyword presence

## 🛠 Tools and Libraries

- **Python**
- **Pandas** – Data handling
- **Matplotlib** & **Seaborn** – Visualization
- **TextBlob** – Sentiment analysis
- **Statsmodels** – Time series decomposition

## ▶️ How to Run

1. Clone the repo and navigate to the project folder:
    ```bash
    git clone https://github.com/AkshayBani08/gold-price-sentiment-analysis.git
    cd gold-price-sentiment-analysis
    ```

2. Install dependencies:
    ```bash
    pip install pandas matplotlib seaborn textblob statsmodels
    ```

3. Open and run the Jupyter Notebook (`.ipynb` file) step-by-step.

## ✅ Results Summary

- Negative sentiment (e.g., from "recession" headlines) often aligns with short-term gold price drops.
- Moving averages highlight consistent long-term trends.
- Sentiment analysis supports the potential of NLP in financial data forecasting.

## 🚀 Future Work

- Expand keyword tracking for broader economic themes
- Build machine learning models to predict price direction
- Integrate macroeconomic indicators for enriched analysis

## 👤 Author

Developed as part of a data analytics learning journey to combine time series, sentiment analysis, and data storytelling.
