
# Samsung Electronics Stock Price Analysis

This repository contains a comprehensive analysis of Samsung Electronics' stock price data from 2000 onwards. The analysis includes data exploration, visualization, seasonal decomposition, volatility analysis, and time series forecasting using advanced methods like Holt-Winters, Prophet, and ARIMA models. 

## About Samsung Electronics

Samsung Electronics Co., Ltd., a major subsidiary of the Samsung Group, is a global leader in technology and consumer electronics. Founded in 1938 by Lee Byung-chul, Samsung initially started as a trading company and has since expanded into various industries, including electronics, shipbuilding, and construction. Samsung Electronics, established in 1969, has become one of the world's largest manufacturers of smartphones, semiconductors, and electronic devices. Headquartered in Suwon, South Korea, Samsung Electronics is renowned for its innovative products and technological advancements, significantly impacting the global market.

## Dataset

The dataset provides a comprehensive record of Samsung Electronics' stock price changes since 2000. It includes the following columns:
- **Date**: The date of the stock price record.
- **Open**: The opening price of the stock on that day.
- **High**: The highest price of the stock on that day.
- **Low**: The lowest price of the stock on that day.
- **Close**: The closing price of the stock on that day.
- **Adj Close**: The adjusted closing price of the stock on that day, which accounts for corporate actions.
- **Volume**: The number of shares traded on that day.

This extensive data is invaluable for conducting historical analyses, forecasting future stock performance, and understanding long-term market trends related to Samsung Electronics' stock.

## Analysis

The analysis is provided in a Jupyter notebook (`Samsung_Stock_Analysis.ipynb`) and includes the following sections:

### 1. Data Exploration
- Understanding the structure and content of the dataset.

### 2. Data Visualization
- Visualizing key features such as closing price and trading volume over time.

### 3. Seasonal Decomposition
- Decomposing the time series to analyze trend, seasonality, and residuals.

### 4. Volatility Analysis
- Analyzing stock price volatility using rolling statistics and Bollinger Bands.

### 5. Time Series Forecasting
- Forecasting future stock prices using:
  - Holt-Winters Exponential Smoothing
  - Prophet Model
  - ARIMA Model

### 6. Autocorrelation and Partial Autocorrelation
- Examining autocorrelation and partial autocorrelation of the stock prices.

### 7. Model Evaluation
- Evaluating the performance of forecasting models using Mean Squared Error (MSE) and Mean Absolute Error (MAE).

### 8. Insights and Conclusion
- Summarizing the key insights and conclusions from the analysis.

## How to Use

1. Clone the repository:
   ```sh
   git clone https://github.com/debjit-mandal/samsung-stock-analysis.git
   cd samsung-stock-analysis
   ```

2. Install the required dependencies:
   ```sh
   pip install -r requirements.txt
   ```

3. Open the Jupyter notebook:
   ```sh
   jupyter notebook Samsung_Stock_Analysis.ipynb
   ```

4. Run the notebook cells to perform the analysis.

## Dependencies

- pandas
- numpy
- matplotlib
- seaborn
- statsmodels
- prophet
- scikit-learn

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The dataset can be found on Kaggle: [Samsung Stock Price Dataset 📱🏭📈](https://www.kaggle.com/datasets/mayankanand2701/samsung-stock-price-dataset)
  
- Thanks to the contributors of the open-source libraries used in this project.
