# Monero Price Prediction Website

A sleek and modern website that predicts short-term price movements of Monero (XMR) using technical indicators like SMA, RSI, MACD, and Bollinger Bands. The website also suggests buy/sell price targets based on the prediction.

## Features

- **Real-Time Price Data**: Fetches the current price of Monero using the CoinGecko API.
- **Technical Indicators**:
  - Simple Moving Average (SMA)
  - Relative Strength Index (RSI)
  - Moving Average Convergence Divergence (MACD)
  - Bollinger Bands
- **Weighted Prediction Logic**: Combines multiple indicators for accurate predictions.
- **Buy/Sell Price Targets**: Suggests optimal buy/sell prices based on the prediction.
- **Dark Theme**: Sleek and modern design with a dark theme for better readability.
- **Responsive Design**: Works seamlessly on all devices.

- ## How It Works

1. **Fetch Data**: The website fetches the current price and historical data for Monero using the CoinGecko API.
2. **Calculate Indicators**: It calculates technical indicators like SMA, RSI, MACD, and Bollinger Bands.
3. **Make Prediction**: A weighted prediction score is calculated based on the indicators.
4. **Suggest Targets**: If the price is predicted to go up, a sell target is suggested. If the price is predicted to go down, a buy target is suggested.
5. **Display Results**: The prediction and price targets are displayed on the website.

6. ## Technologies Used

- **Frontend**:
  - HTML, CSS, JavaScript
  - [TensorFlow.js](https://www.tensorflow.org/js) (for future AI integration)
- **APIs**:
  - [CoinGecko API](https://www.coingecko.com/en/api) for price and historical data.
- **Styling**:
  - Google Fonts (Roboto)
  - CSS Animations

---

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/monero-price-prediction.git
   cd monero-price-prediction
Open the project:

Open the index.html file in your browser.

Run the website:

Click the "Predict Short-Term Movement" button to see the prediction and price targets.

Usage
Open the website.

View the current price of Monero.

Click the "Predict Short-Term Movement" button.

See the prediction and suggested buy/sell price targets.

Use the data to make informed trading decisions.

Acknowledgments
CoinGecko for providing the cryptocurrency data API.

TensorFlow.js for enabling machine learning in the browser.

Google Fonts for the Roboto font.

Contact
For questions or feedback, feel free to reach out:

GitHub: https://github.com/xmrtools
Website: https://xmrtools.github.io/xmr_price_predict/
Made with ❤️ by xmrtools
