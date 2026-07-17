# Stock Price Forecasting Using LSTM and GRU

This project compares LSTM and GRU deep-learning models for stock price forecasting.

The models are tested using two configurations:

* Without sentiment data
* With sentiment data

The models are evaluated using RMSE, MAE, and Directional Accuracy.

## Project Files

* `data/Dataset.csv` – Dataset used for training and testing
* `Stock_Forecasting_LSTM_GRU.ipynb` – Main Google Colab notebook
* `results/results_data/` – Training history and prediction results
* `results/results_plots/` – Model prediction and loss graphs
* `results/results_summary/` – Final performance metrics

## Models

The project uses two recurrent neural-network models:

* Long Short-Term Memory (LSTM)
* Gated Recurrent Unit (GRU)

Both models contain:

* First recurrent layer with 100 units
* 20% dropout
* Second recurrent layer with 50 units
* 20% dropout
* Dense layer with 25 units
* Output layer with 1 unit

## How to Run

1. Download or clone this repository.
2. Upload the project folder to Google Drive.
3. Open `Stock_Forecasting_LSTM_GRU.ipynb` in Google Colab.
4. Select a GPU runtime.
5. Run all notebook cells in order.
6. Allow Google Colab to access Google Drive when requested.

## Requirements

* Python
* TensorFlow
* Keras
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
