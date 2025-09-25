# CNN-BiLstm-Stock-Prediction

Comprehensive time series analysis of major technology stocks (AAPL, AMZN, GOOG, MSFT) using Yahoo Finance data. This project includes data visualization, risk analysis, and a hybrid CNN-BiLSTM deep learning model to predict Apple's stock price. Model performance is evaluated using RMSE, MSE, and MAE metrics.

## Features

- **Data Collection:** Fetches historical stock data from Yahoo Finance.
- **Visualization:** Plots trends, volatility, and risk metrics for selected stocks.
- **Risk Analysis:** Calculates and visualizes risk indicators.
- **CNN-BiLSTM Model:** Implements a hybrid Convolutional Neural Network (CNN) and Bidirectional LSTM (BiLSTM) for time series prediction.
- **Performance Evaluation:** Uses RMSE, MSE, and MAE to assess prediction accuracy.

## Tech Stack

- **Language:** Jupyter Notebook (Python)
- **Libraries:** `pandas`, `numpy`, `matplotlib`, `yfinance`, `sklearn`, `tensorflow`/`keras`

## Getting Started

### Prerequisites

- Python 3.7+
- Jupyter Notebook
- Install dependencies:

```bash
pip install pandas numpy matplotlib yfinance scikit-learn tensorflow
```

### Usage

1. **Clone the repository:**
    ```bash
    git clone https://github.com/ZidanMau24/CNN-BiLstm-Stock-Prediction.git
    cd CNN-BiLstm-Stock-Prediction
    ```

2. **Open the Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
    - Run the notebook step by step to collect data, visualize, analyze risk, train, and evaluate the model.

## Project Structure

```
.
├── notebooks/             # Jupyter Notebooks for analysis and modeling
├── README.md              # Project documentation
└── requirements.txt       # Python dependencies
```

## Model Overview

- **CNN-BiLSTM Architecture:** Combines feature extraction from CNN with sequence learning from BiLSTM, tailored for time series stock prediction.
- **Target Stock:** Apple (AAPL)
- **Metrics:** Root Mean Square Error (RMSE), Mean Squared Error (MSE), Mean Absolute Error (MAE)

## Results

- Visualizations of historical stock prices and risk metrics.
- Model achieves competitive prediction accuracy (see notebook for details).

## Contributing

Contributions are welcome! Please open issues or submit pull requests for improvements or new features.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

- **Author:** [ZidanMau24](https://github.com/ZidanMau24)
