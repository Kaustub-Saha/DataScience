# Python
# DataScience
# Bidirectional LSTM
# Bidirectional GRU
# Fashion Mnist
# Recurrent Neural Network
# Neural Network
In this project a neural network model for fashion-mnist image data classification by using bidirectional RNN (GRU/LSTM) is created. Two bidirectional RNNs were used to scan the image top to bottom and bottom to top, and left to right and right to left. Splitting the training data in 75:25 to create training (75%) and validation (25%) set. 
There are 10 classes in the dataset, so a 10-class classification is performed. It has be experimented with Bidirectional LSTM, Bidirectional GRU, multiple layers of Bidirectional GRU/LSTM, different mini-batch size, different hidden vector size for LSTM/GRU, different epoch, and choosen the combination that yields highest accuracy without overfitting. To make sure that your model is not overfitting, difference between training accuracy and validation accuracy should not be more than 2%.

