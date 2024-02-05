## Stock Price Prediction using LSTM

This repository contains a deep learning model implemented with Long Short-Term Memory (LSTM) networks to predict Apple Inc.'s stock prices. The model is trained using historical stock price data and aims to forecast future price movements.

### Dataset

The dataset used for training and evaluation includes historical daily stock price data for Apple Inc. The dataset contains features such as open, high, low, close prices, adjusted close prices, and trading volume.

### Methodology

1. **Data Preprocessing**:
   - The dataset is preprocessed to handle missing values and to scale the data using Min-Max scaling to ensure the data falls within a specific range.

2. **Model Architecture**:
   - The LSTM model is constructed using the Keras library.
   - The model consists of multiple LSTM layers with dropout regularization to prevent overfitting.
   - The output layer is a dense layer that predicts the next closing price.

3. **Training**:
   - The model is trained on a subset of the data, with the majority used for training and a smaller portion for validation.

4. **Evaluation**:
   - The trained model's performance is evaluated using Root Mean Squared Error (RMSE) to measure the difference between predicted and actual stock prices.

5. **Prediction**:
   - The trained model is used to predict future stock prices based on the last 60 days of available data.

### Usage

1. Clone the repository to your local machine.
2. Ensure you have the required dependencies installed (Pandas, NumPy, Matplotlib, Scikit-learn, Keras).
3. Prepare your historical stock price dataset or use the provided example datasets.
4. Train the model using the provided notebook or script.
5. Evaluate the model's performance and adjust hyperparameters as needed.
6. Use the trained model to predict future stock prices.

### Results

The LSTM model demonstrates the ability to capture patterns and trends in historical stock price data. It provides valuable insights into potential future price movements, aiding investors and analysts in making informed decisions.

### Future Improvements

- Experiment with different architectures and hyperparameters to improve model performance.
- Explore additional features and data sources to enhance prediction accuracy.
- Implement more advanced techniques such as attention mechanisms for better sequence modeling.

### Contributors

- [Srihari Kamath](https://github.com/SrihariKamath))
- Shikha Punjabi


Contributions to the project are welcome. Please feel free to submit bug fixes, feature enhancements, or suggestions for improvement.
