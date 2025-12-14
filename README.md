# lstm-univariate-timeseries

LSTM recurrent neural network

# install python libraries

pip install -r requirements.txt

pip install tensorflow

pip install keras

# setup anaconda and deep learning libraries

[setup deep learning library](https://machinelearningmastery.com/setup-python-environment-machine-learning-deep-learning-anaconda/)

conda list

## About Project

- Monthly sales data for shampoo for 3 year period
- Month and sales in the data set

## Long Short Term Memory time series forecasting

- Univariate time series
- Read data, plot data
- Train test split
- Walk forward model validation
  - each time step of the test data set will be walked once a time
  - Make forecast on this data
  - consider next time step data and ake forecast for next time step
  - RMSE for checking performance of model
- Create baseline persistent model (Xt = Xt-1)
- Persistent model forecast
- LSTM data preparation (important step)
- Transform timeseries data to supervised data
- Transform the time series data so that it is sationary by differencing, inverse transform
- Scaling of the data to transform between -1 to 1, and inverse scaling
- LSTM architecture
- Stateful = True and stateless
- LSTM compile (Loss function mean square error, optimization adam)
- LSTM model Development
- Evaluate model on test data
- Hyper parameter optimization on validation data and evaluate on unseen test data
- (train, validation, test) data approach
- bias, variance tradeoff to select best model
- complete flow in jupyter notebook
- Productize the project with packaging
- Run in docker
- CI for unit test with git action
- CD for docker image to send to docker registry
- Run in minikube and
- Run in EC2
