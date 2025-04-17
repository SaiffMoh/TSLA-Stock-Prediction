# Tesla Stock Price Prediction with LSTM

A deep learning project that predicts **Tesla (TSLA)** stock prices using a Long Short-Term Memory (LSTM) model. Dive into time-series forecasting and predict the market’s next move! 📈

## 🚀 Features
- Loads and visualizes historical TSLA stock data (Open, High, Low, Close, Volume)
- Preprocesses data with Min-Max scaling for LSTM training
- Trains an **LSTM** model to predict future stock prices
- Evaluates predictions with Mean Squared Error (MSE) and Mean Absolute Error (MAE)
- Visualizes actual vs. predicted prices 📊

## 📂 Project Structure
- `TSLA.ipynb`: Jupyter notebook with the full pipeline (data loading, preprocessing, LSTM training, evaluation)
- `requirements.txt`: Dependency list for reproducibility
- `README.md`: You're reading it! 😎

## 🧠 Model
- **LSTM Model**: Recurrent neural network designed for time-series data, trained on TSLA stock prices
- Built with TensorFlow/Keras and optimized for sequence prediction

👉 **Dataset**: The project uses `TSLA.csv`, containing historical stock data (2010–2022). Download it from a source like [Yahoo Finance](https://finance.yahoo.com/quote/TSLA/history/) or Kaggle and place it in the project root, or update the `pd.read_csv()` path in the notebook.

## 📦 Requirements
Install dependencies using:
```bash
pip install -r requirements.txt
