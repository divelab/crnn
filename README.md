# Recurrent encoder-decoder networks for time-varying dense prediction
Implementation for submitted paper of KDD 2017 : **" Recurrent encoder-decoder networks for time-varying dense prediction"**, which combined FCN (U-net, DeepEM-net(DenseNet)) and CRNN(convolution LSTM and GRU, deconvolution one) as an integrated networks for en-to-end training.
# Required libraries
Keras, Theano
# Data
(1). Register first at:
http://brainiac2.mit.edu/SNEMI3D/user/register

(2). Login in and download data at:
http://brainiac2.mit.edu/SNEMI3D/downloads

(3) Convert image files into h5 file that contains **\data** and **\label** sets.  
# Code
Run **train_predict.py** for training or prediction. To predict/train a specific model, you need change **mode_name** accordingly.
# Note:
To use convolutional GRU and Deconvolutional LSTM/GRU layers, copy **extra_conv_recurrent.py** to Keras's layer folder and run " python setup.py install" to install Keras again.
# Code reference:
Convolutional LSTM Network: A Machine Learning Approach for Precipitation Nowcasting  
(http://arxiv.org/pdf/1506.04214v1.pdf)

https://github.com/fchollet/keras/blob/master/keras/layers/convolutional_recurrent.py
