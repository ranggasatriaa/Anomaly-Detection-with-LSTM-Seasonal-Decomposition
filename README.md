# Anomaly Detection with LSTM Seasonal-Decomposition

This algoritm use seasonal decomposition to separate the data into 3 component (trend, seasonal, and residual). The separate data then through LSTM training to get prediction resoult before combine again into one complete prediction. The prediction compared with the real data to detect is there any gap which would be considered an anomaly.

# How to used
1. Install the environment with enviroment.yml
2. Run "Training.ipynb" file to train the model. By default the model will be saved into "log" folder.
3. Run "Testing.ipynb" file to test the testing data. The result and performance will be export into .csv format in "log" folder.

# Sintetic Anomaly Generator
If the data is not contain anomaly, you can use "Anomaly_generator.ipynb" file to generate some sintetic anomaly into test dataset
