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

* Monthly sales data for shampoo for 3 year period
* Month and sales in the data set


## Long Short Term Memory time series forecasting

* Univariate time series
* Read data, plot data
* Train test split
* Walk forward model validation
  * each time step of the test data set will be walked once a time
  * Make forecast on this data
  * consider next time step data and ake forecast for next time step
* Create baseline persistent model
* Persistent model forecast
* LSTM data preparation
* Transform timeseries data to supervised data
* Transform the time series data so that it is sationary
* LSTM architecture
* LSTM model Development
* Evaluate model
* complete flow in jupyter notebook
* Productize the project
* Packaging the project
* Run in docker
* CI for unit test
* CD for docker to docker registry
* Run in minikube
