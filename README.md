# Recrrent encoder-decoder networks for time-varying dense predition
Implementation for submitted paper of KDD 2017 : " Recrrent encoder-decoder networks for time-varying dense preditio", which combined FCN (U-net, DeepEM-net) and CRNN(convolution LSTM and GRU, deconvolution one) as a integrated networks for en-to-end training.
# Required library
Keras, Theano
# Code
Run train_predict.py for training or prediction. To predict/train a specific model, you need change modename accordingly.
# Node:
To use convolutional GRU and Deconvolutional LSTM/GRU layers, copy extra_conv_recurrent.py to Keras's layer folder and run " python setup.py install" to install Keras again.
