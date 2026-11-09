* About the source code:
* Objective & Dataset: The project predicts future hourly PM2.5 air pollution levels using an LSTM (Long Short-Term Memory) neural network built with PyTorch, based on historical air quality data from India (2017–2022).
* Data Preprocessing: Timestamps are parsed and resampled into an hourly frequency, missing values are filled via linear interpolation, and the PM2.5 values are scaled to a $[0, 1]$ range using MinMaxScaler.
* Sequence Creation & Splitting: Sequences of past 24 hours (look_back = 24) are created to predict the next hour. The dataset is chronologically split into 70% for training, 15% for validation, and 15% for testing.
* Model Architecture & Training: The model uses a 2-layer LSTM with a hidden size of 64 and a dropout rate of 0.2, followed by a fully connected output layer. It is trained using Mean Squared Error (MSE) loss, the Adam optimizer, and early stopping to prevent overfitting.  
