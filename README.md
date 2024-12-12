Download 4 files from here:

1. https://github.com/WegraLee/deep-learning-from-scratch/raw/master/dataset/t10k-images-idx3-ubyte.gz
2. https://github.com/WegraLee/deep-learning-from-scratch/raw/master/dataset/t10k-labels-idx1-ubyte.gz
3. https://github.com/WegraLee/deep-learning-from-scratch/raw/master/dataset/train-images-idx3-ubyte.gz
4. https://github.com/WegraLee/deep-learning-from-scratch/raw/master/dataset/train-labels-idx1-ubyte.gz

if you get an error from mnist.py

=============================================================================================================

DOIT.py: This file runs the neural network training process.

functions.py: Contains utility functions for building layers.
  - sigmoid, softmax, im2col & col2im (functions to facilitate convolution operations).

layers.py: Defines classes for layers used in neural network implementation.
  - Includes classes like Convolution, ReLU, Affine, SoftmaxWithLoss, Pooling, and numerical_gradient function.
  - Also contains the implementation of a sample neural network, `SimpleConvNet`.

mnist.py: Code for downloading and preparing the MNIST dataset.

optimizer.py: Implements optimization functions for parameter updates.

trainer.py: Provides a class that automates the neural network training process.

=============================================================================================================

reference : '밑바닥부터 시작하는 딥러닝'
