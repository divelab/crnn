# Recurrent encoder-decoder networks for time-varying dense prediction
Implementation for submitted paper of KDD 2017 : **" Recurrent encoder-decoder networks for time-varying dense prediction"**, which combined FCN (U-net, DeepEM-net) and CRNN(convolution LSTM and GRU, deconvolution one) as an integrated networks for en-to-end training.
# Required library
Keras, Theano
# Code
Run **train_predict.py** for training or prediction. To predict/train a specific model, you need change mode name accordingly.
# Node:
To use convolutional GRU and Deconvolutional LSTM/GRU layers, copy **extra_conv_recurrent.py** to Keras's layer folder and run " python setup.py install" to install Keras again.
