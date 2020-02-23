# Neural Netwoek from Scratch
This is an Implementation of Simple 2-layered NN using Numpy (one hidden layer)

The code is inspired from numerous resources I have went through.

# Dataset
The training and test data are reflections of first 64 whole numbers in binary. Alternate values go into training and testing dataset (starting from training) giving us 32 for training as well as testing. Dataset was then shuffled and the labels given as the second last digit in the representation.

# Network
The network is fed data in two batches of 16 samples each. The hidden layer has 16 neuron. Activation function used is Sigmoid. The test performed here uses first 16 samples of test data.
