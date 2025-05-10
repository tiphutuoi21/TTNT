<h1 align="center">
    Stock Price Forecasting Using xLSTM
    <br>
</h1>



## Dependencies
| Library  | Version |
| -------- | ------- |
| `Python` | `3.10.12` |
| `torch`  | `2.4.1` |
| `torch-summary` | `1.4.5` |
| `xlstm`    | `1.0.7`  |
| `cuda` | `12.1` |
| `matplotlib` | `3.7.1` |
| `numpy` | `1.26.4` |
| `pandas` | `2.2.2` |
| `scikit-learn` | `1.5.2` |
| `yfinance` | `0.2.44` |
| `Ninja`    | `1.11.1.1` |



## Configuration and Hyperparameters
| Library  | Version |
| -------- | ------- |
| `Batch Size` | `64` |
| `Epochs`  | `50` |
| `Learning Rate Schedule` | `ReduceLROnPlateau` |
| `Init. Learning Rate` | `1e-4` |
| `Train-Val-Test Split`    | `64% - 16% - 20%`  |
| `Scaler` | `MinMaxScaler` |
| `Number of mLSTM blocks` | `3` |
| `Embedding dimension` | `128` |
| `Moving average kernel size` | `25` |
| `Loss Function` | `MSE loss` |
| `Optimization Algorithm` | `RAdam` |



## Model Architecture
The architecture we used is as depicted in the
following figure.
<p align="center">
  <img src="https://github.com/tiphutuoi21/TTNT/blob/main/assets/architecture.png" width="1000"/>
</p>



