# 📈 Real-Time Stock Dashboard

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-1.x-brightgreen.svg)

## 📝 Overview

The Real-Time Stock Dashboard is a dynamic and interactive web application built using **Streamlit** and **Plotly**. It allows users to monitor and analyze stock market data in real-time, providing key metrics, technical indicators, and historical data for selected stocks. Whether you're a trader or just interested in tracking the market, this dashboard offers a powerful tool for financial analysis.

![Dashboard Screenshot](https://github.com/GGarv/Trading_dashboard/blob/main/Dashboard.png?raw=true)


## 🌟 Features

- **Real-Time Stock Data**: Fetches up-to-date stock information for multiple symbols using Yahoo Finance.
- **Customizable Chart Parameters**: Choose between different time periods, chart types (Candlestick or Line), and add technical indicators like Simple Moving Average (SMA) and Exponential Moving Average (EMA).
- **Interactive Visualization**: Dynamic charts built with Plotly, offering rich interactivity and customization.
- **Metric Display**: Key stock metrics including last price, price change, percentage change, high, low, and volume are displayed for quick insights.
- **Responsive Layout**: Built with Streamlit for a responsive and user-friendly interface.

## 📊 Technical Indicators

The dashboard supports the following technical indicators:
- **SMA 20**: Simple Moving Average over a 20-day window.
- **EMA 20**: Exponential Moving Average over a 20-day window.

## ⚙️ Installation

### Prerequisites

- Python 3.x
- pip (Python package installer)

### Setup

1. **Clone the repository**:
    ```bash
    git clone https://github.com/garvgupta/real-time-stock-dashboard.git
    cd real-time-stock-dashboard
    ```

2. **Install the required packages**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the application**:
    ```bash
    streamlit run stock_dashboard.py
    ```

## 🧠 Usage

- **Ticker**: Enter the stock ticker symbol (e.g., `AAPL`, `GOOGL`, `AMZN`).
- **Time Period**: Select the period over which you want to analyze the stock (e.g., `1d`, `2wk`, `1mo`, `1yr`, `max`).
- **Chart Type**: Choose between Candlestick and Line chart.
- **Technical Indicators**: Optionally add SMA or EMA indicators to the chart.
- **Real-Time Updates**: The dashboard fetches and displays real-time data for selected stock symbols in the sidebar.

## 👨‍💻 Technologies Used

- **Python**
- **Streamlit** - For the web interface.
- **Plotly** - For interactive charts.
- **Yahoo Finance (yfinance)** - To fetch real-time stock data.
- **TA-Lib** - To compute technical indicators.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🛠️ Contributing

Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.
